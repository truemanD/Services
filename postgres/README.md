- edit kong config ./kong/config.sh
- launch kong
```
docker-compose up -d
```

- for test use
```
curl -i -X GET --url http://localhost/ --header 'Host: example.com'
```

or
```
http://localhost:1337/#!/login
```
admin/ adminadminadmin