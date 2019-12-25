# filter-word

## Domain

フィルタ対象のワードの管理を行う

## Method

### GET

- default

全てのフィルタワードを返却する

- query param

| key  | contents             |
| ---- | -------------------- |
| id   | フィルタワードの id  |
| word | 部分一致させる文字列 |

- example

```bash:example-query
// all
GET filter-word/

// only get target with param.
Get filter-word/?id=1
```

### POST

:construction:WIP

### PUT

:construction:WIP

### DELETE

:construction:WIP
