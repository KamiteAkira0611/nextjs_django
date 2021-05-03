# start
```
$ cd docker
$ ./command start
$ ./command exec_react
/app # npm run dev
```

本番環境の確認
```
/app # npm run build
/app # npm start
```

# stop
```
$ cd docker
$ ./command stop
```

## webpack not foundと言われた場合
```
# docker-compose run rails bundle exec rails webpacker:install
```
