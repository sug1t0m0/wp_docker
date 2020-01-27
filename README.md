### これは何?

WordPressをDockerでさっと立てるやつ

### 起動

```shell script
docker-compose up -d
```

### 注意しなければいけないところ

- wp-contentフォルダだけをマウントしてるからそれを忘れてはいけない
- mysqlのバージョン
