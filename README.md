# Flask_Practice
1. 概要
PythonのフレームワークであるFlaskで作ったコードです。


2. 説明

2-1. BookReview
「flask, pymongo」をインストールしてください。
題名通り、読んだ本のレビューを書き、入力するとデータベースにセーブされ、下に表示されるプログラムです。
一番目のinputに本の題名、二番目に著者の名前、三番目に感想を140字以内で書き、ボタンを押すとMongoDBにレビューの情報が記載されます。


2-2. AloneMemo
「flask, pymongo, requests, bs4」　をインストールしてください。 
青いボタンを押すと、Posting Boxを開くことが出来ます。
Naver Moiveで好きな映画を選択し、そのURLを一番目のinputに入力し、二番目のinputに簡単なコメントを入力すると
URLをクローリングし、映画に関する情報、イメージが含まれたカードにコメントが記載されます。


2-3. MovieStar
「flask, pymongo, requests, bs4」　をインストールしてください。 
Naver Movieの俳優の情報を「init_db.py」でクローリングし、MongoDBに載せて置きました。

app.pyを起動することで「http://localhost:5001 」にFlaskサーバーができ、そのアドレスに訪れると、 
ajaxにより、MongoDBの中にある情報を基に、俳優たちが入っているカードが表示されます。

「いいね」が多い順で整列され、いいねを押すと、いいねの数がMongoDBに入力され、どんどん変わるようになっています。

