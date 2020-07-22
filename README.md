### MONGO DB

Error: couldn't connect to server 127.0.0.1:27017, connection attempt failed: SocketException: Error connecting to 127.0.0.1:27017 :: caused by :: No connection could be made because the target machine actively refused it. :
connect@src/mongo/shell/mongo.js:341:17 [here](https://www.youtube.com/watch?v=xgpGmi0EgcA) probably need to start mongodb from task manager.

**_Local connection:_** <ins>MONGO_URI = 'mongodb://127.0.0.1:27017/database_name'</ins>

**_remote connection:_** <ins>MONGO_URI = 'mongodb+srv://Bepul:password@cluster0-lo1zs.mongodb.net/Dababase_name?retryWrites=true&w=majority'</ins>

**_MONGO DB Cheat sheat_** 1. [MongoDB commands](https://gist.github.com/ondrejsika/ded2a9a22c96cda7098d69b5f158cd8a) 2. [SQL to MongoDB Mapping Chart](https://gist.github.com/aponxi/4380516) 3. [Essential MongoDB Shell Commands](https://www.opentechguides.com/how-to/article/mongodb/118/mongodb-cheatsheat.html) 4. cheat sheat pdf [here](https://github.com/Bepul-Hossain/my-regular-learning/blob/master/assets/pdf/MongoDB-CheatSheet-v1_0.pdf)

** Mongo doc** 1. [Coursera Exercise (Instructions): Introduction to MongoDB](https://docs.google.com/document/d/1Cvzz4izfvO67k_AwIeEENX8hQ6P1fANcoPqdTAvp19s/edit?usp=sharing)

 ### All node modules docfile [here](https://docs.google.com/document/d/1uj0gDlVw6b-JE93-Su1ZrbAMTCIypofRrkFp_JAaLRc/edit?usp=sharing)



### Less

Set-RestrictionPolicy for less file
[1. Tutorial](https://tecadmin.net/powershell-running-scripts-is-disabled-system/)
[2. Video](https://www.youtube.com/watch?v=Q2uLUuq0Ft4)
[4. MySolveImage](img/lessFileErrorSolve.png)

```
Doing for run:
PS E:\Web Development\coursera> cd css
PS E:\Web Development\coursera\css> less styles.less styles.css
```

## scss

1. npm install --save-dev node-sass
2. open your package.json file and add the following line into the scripts object "scss": "node-sass -o css/ css/"

```
"scripts": {
    "start": "npm run lite",
    "test": "echo \"Error: no test specified\" && exit 1",
    "lite": "lite-server",
    "scss": "node-sass -o css/ css/"
  },
```

3. npm run scss

### git hub

[Awesome git-cheatsheet](http://ndpsoftware.com/git-cheatsheet.html#loc=local_repo)

Back to specific older HEAD on git commit [image](assets/img/Back_o_git_specific_commit.PNG) [video](https://www.youtube.com/watch?v=yLNl6kpaVD4&t=1s)

Switch github one accout to another by Credential manager [video ](https://www.youtube.com/watch?v=aSTTJd5JMXg) [ image](assets/img/credential_manager.png)

Git disable so cannot perform hold changes [@builtin git](https://www.youtube.com/watch?v=nFzQnl44_70)

| mongodb | node module |     |     |     |
| ------- | ----------- | --- | --- | --- |
|         |             |     |     |     |
|         |             |     |     |     |
|         |             |     |     |     |
