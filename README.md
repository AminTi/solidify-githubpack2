# solidify-githubpack2

1 npm int -y

2 -$ npm login --scope=@OWNER --registry=https://npm.pkg.github.com

> Username: USERNAME
> Password: TOKEN
> Email: PUBLIC-EMAIL-ADDRESS

3 Create npmrc fileand add 
@aminti:registry=https://npm.pkg.github.com

4 Edit json file and add 

 "publishConfig": {
  "registry":"https://npm.pkg.github.com"
},
"repository":{
    "url": "git://github.com/aminti/solidify-githubpack2"
  },


4 npm publish enjoy!

