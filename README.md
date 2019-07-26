# 💾 mongo-clone
CLI tool for cloning mongoDB database from one server to another. <br>
It is useful for DB backups from DB hostings that doesn't support free backup plan. (e.g. [mlab](https://mlab.com))

## 🔧 Installation
*From [npm](http://npmjs.org) (the recommended way)*:<br>
`npm i mongo-clone -g`<br><br>
_or_<br><br>
*From git repo:*
1. clone repo: ```git clone https://github.com/fr1sk/mongo-clone.git```
2. cd to repo: ```cd mongo-clone```
3. install mongo-clone: ```npm i -g```

## 👨🏻‍💻 Usage
Start cloning: <br>
```mongo-clone -s <SOURCE_MONGO_DB_URL> -t <TARGET_MONGO_DB_URL> [-f]```<br>
`-s` _source mongoDB server that you want to clone from_<br>
`-t` _target mongoDB server (empty DB) that you want to clone to_<br>
`-f` _(optional) force deletion of target mongoDB before copying_<br><br>
Mongo URL example: <br>
```mongodb://USER:PASS@HOST:PORT/DBNAME```

## 🔎 Other info - Good to know
* It won't clone all of system.indexes! 🗂️
* Keep in mind that this is beta version and if you have some problems please report it! My email is `fr1sk@live.com` 📧
* Feel free to contribute - just open PR! 👋🏻
* If you like it buy me a beer 🍺 <br>
My BTC addresse: `1KUxHZT6H9aSHQrNZvb1qw6ZvRJ6VEApWu`

## 📺 Demo
![mongo-clone demo1](https://raw.githubusercontent.com/fr1sk/mongo-clone/master/demo/mongo-clone1.png "mongo-clone: without arguments")<br>
_mongo-clone: without arguments!_<br><br>
![mongo-clone demo2](https://raw.githubusercontent.com/fr1sk/mongo-clone/master/demo/mongo-clone2.png "mongo-clone: cloning in progress")<br>
_mongo-clone: cloning in progress!_<br><br>
![mongo-clone demo3](https://raw.githubusercontent.com/fr1sk/mongo-clone/master/demo/mongo-clone3.png "mongo-clone: cloning done")<br>
_mongo-clone: cloning completed!_<br><br>
