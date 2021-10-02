# README
### 開発環境

- ruby '2.6.6'
- rails '6.1.4'
- PostgreSQL '13.3'

### database

|users|data type|
|-----|-----|
|id|integer|
|name|string|
|email|string|
|password|string|

|tasks|data type|
|-----|-----|
|id|integer|
|user_id|integer|
|title|string|
|content|text|
|expiration_date|datetime|

|labels|data type|
|-----|-----|
|id|integer|
|name|string|

|labelings|data type|
|-----|-----|
|id|integer|
|task_id|integer|
|label_id|integer|
