Furima h1
ライフコーチが学習するためのアプリ

## usersテーブル

| Column           | Type      | Options  |
| ---------------- | --------- | ---------|
| nick_name        | string    | not null |
| email            | string    | not null |
| password         | string    | not null |
| password_check   | string    | not null |
| first_name       | string    | not null |
| last_name        | string    | not null |
| first_name_kana  | string    | not null |
| last_name_kana   | string    | not null |
| birthday         | date      | not null |

## itemsテーブル

| Column          | Type          | Options  |
| --------------- | ------------- | -------- |
| item_image      | ActiveStorage |          |
| item_name       | string        | not null |
| item_concept    | text          | not null |
| item_category   | string        | not null |
| item_version    | string        | not null |
| delivery_fee    | string        | not null |
| delivery_area   | string        | not null |
| delivery_day    | string        | not null |
| item_fee        | string        | not null |


## ordersテーブル

| Column       | Type       | Options  |
| -----------  | ---------- | -------- |
| card_number  | string     | not null |
| card_id      | string     | not null |
| timestamps   |            |          |
| post_number  | string     | not null |
| prefectures  | string     | not null |
| city         | string     | not null |
| city_number  | string     | not null |
| building     | string     | not null |
| phone_number | string     | not null |