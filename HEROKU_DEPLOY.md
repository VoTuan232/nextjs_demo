+ Deploy with github: https://github.com/mars/heroku-nextjs
+ Change package.json:
  + "start": "next start -p $PORT"
+ heroku login
+ heroku git:remote -a nextjs-demo-1
+ heroku create --buildpack https://github.com/mars/heroku-nextjs.git