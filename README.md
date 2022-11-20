## usersテーブル
| Column            | Type       | Options                        |
| ------            | ---------- | ------------------------------ |
| email             | string     | null: false,                   |
| encrypted_password| string     | null: false,                   |
| name              | string     | null: false,                   |
| profile           | text       | null: false,                   |
| occupation        | text       | null: false,                   |
| position          | text       | null: false,                   |

##prototypesテーブル
| Column            | Type       | Options                        |
| ------            | ---------- | ------------------------------ |
| title             | string     | null: false,                   |
| catch_copy        | text       | null: false,                   |
| concept           | text       | null: false,                   |
| user              | reference  | null: false,                   |
##commentsテーブル
| Column            | Type       | Options                        |
| ------            | ---------- | ------------------------------ |
| content           | text       | null: false,                   |
| prototype         | reference  | null: false,                   |
| user              | reference  | null: false,                   |