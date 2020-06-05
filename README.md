### MONGO DB
Error: couldn't connect to server 127.0.0.1:27017, connection attempt failed: SocketException: Error connecting to 127.0.0.1:27017 :: caused by :: No connection could be made because the target machine actively refused it. :
connect@src/mongo/shell/mongo.js:341:17 [here](https://www.youtube.com/watch?v=xgpGmi0EgcA) probably need to start mongodb from task manager.

***Local connection:*** <ins>MONGO_URI = 'mongodb://127.0.0.1:27017/database_name'</ins> 

***remote connection:*** <ins>MONGO_URI = 'mongodb+srv://Bepul:password@cluster0-lo1zs.mongodb.net/Dababase_name?retryWrites=true&w=majority'</ins>

***MONGO DB Cheat sheat*** 1. [MongoDB commands](https://gist.github.com/ondrejsika/ded2a9a22c96cda7098d69b5f158cd8a) 2. [SQL to MongoDB Mapping Chart](https://gist.github.com/aponxi/4380516) 3. [Essential MongoDB Shell Commands](https://www.opentechguides.com/how-to/article/mongodb/118/mongodb-cheatsheat.html) 4. cheat sheat pdf [here](https://github.com/Bepul-Hossain/my-regular-learning/blob/master/assets/pdf/MongoDB-CheatSheet-v1_0.pdf)

### node module
1. [passport-jwt](https://www.npmjs.com/package/passport-jwt)
2. [auth0](https://www.youtube.com/watch?v=QcO8hzIC79A)
3. lite-server [documentation][1] [video][2]

[1]: https://www.coursera.org/learn/bootstrap-4/supplement/JTkjO/exercise-instructions-basics-of-node-js-and-npm
[2]: https://www.coursera.org/learn/bootstrap-4/lecture/L3Q8S/exercise-video-basics-of-node-js-and-npm

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

Switch github one accout to another by Credential manager [video ](https://www.youtube.com/watch?v=aSTTJd5JMXg) [  image](assets/img/credential_manager.png)

|  mongodb |  node module |   |   |   |
|---|---|---|---|---|
|   |   |   |   |   |
|   |   |   |   |   |
|   |   |   |   |   |