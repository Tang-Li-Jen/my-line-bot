# my-line-bot


# Launch Chatbot to Heroku
- Login
```
cd my-line-bot
heroku login -i
```

- Git2Heroku
```
heroku git:remote -a {heroku_app_name}
git push heroku master
```

- heroku config
```
heroku config:set CHANNEL_ACCESS_TOKEN={YOUR_CHANNEL_ACCESS_TOKEN}
heroku config:set CHANNEL_SECRET={YOUR_CHANNEL_SECRET}
```

- monitoring
```
heroku logs --tail --app {heroku_app_name}
```





## Reference
- [LINE Developer](https://developers.line.biz/en/)
- [LINE BOT SDK PYTHON](https://github.com/line/line-bot-sdk-python)
- [使用 Heroku 建立範例聊天機器人](https://developers.line.biz/zh-hant/docs/messaging-api/building-sample-bot-with-heroku/#%E9%83%A8%E7%BD%B2-kitchensink-%E7%AF%84%E4%BE%8B%E8%81%8A%E5%A4%A9%E6%A9%9F%E5%99%A8%E4%BA%BA-app)