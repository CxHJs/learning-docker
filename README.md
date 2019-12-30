# learning-docker: Dockerの練習

## ミニレポート

### Q1-1: 同じ `docker container run` コマンドを2回実行すると、1回目と2回目で違いはありますか？どう違いますか？

【回答欄】
二回目はすぐ Hello world 表示します

### Q1-2: なぜ違いますか？

【回答欄】
一回目は最初からダウンロードするから

### Q1-3: `docker container ls` と `docker container ls -a` はどう違いますか？

【回答欄】
docker container ls は実行してないものを表示する、docker container ls -a は実行してると実行してないどっちも表示する

### Q1-4: `docker image ls` と `docker container ls -a` はどう違いますか？（間違ってもいいので、自分の考えを述べてください）

【回答欄】docker container ls -a は docker image ls より詳しく表示する

### Q1-5: `ubuntu` イメージでの `cat /etc/issue` の結果をペーストしてください

【回答欄】
Ubuntu 18.04.3 LTS \n \l

### Q1-6: `docker image ls` と `docker container ls -a` はどう変化しましたか？

【回答欄】
docker image ls はまにも変わってない
docker container ls -a は新しいのcontainerを起動した

### Q2-1: `-d` (デタッチド・モード) でコンテナを起動すると、どのような状態になりましたか？

【回答欄】
新たなイメージが起動した

### Q2-2: http://localhost/ をブラウザで開くと、何が表示されましたか？

【回答欄】
Welcome to nginx!

### Q3-1: `docker build -t sample-image .` 実行時に表示されている `building...` は、Dockerfileのどの行から実行されましたか？

【回答欄】
新しいのbuildをした

### Q3-2: `docker run sample-image` を実行すると、どうなりましたか？

【回答欄】
Hello, from Docker container!
