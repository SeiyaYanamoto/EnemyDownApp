## はじめに
- 本リポジトリは、Java学習者の「Seiya」（Xアカウント： [@Seiya_engineer]( https://x.gd/daily_study)）が作成した『EnemyDownApp』に関するものです。
- ご利用いただくことによるトラブル等につきましては、一切の責任を負いかねますことを予めご了承ください。

## アプリ概要
- REST APIを用いて、ゲーム時間や難易度などのデータ取得する機能のアプリです。
- データベースの登録・更新はPostmanを用いて、データベースに情報を追加します。

## データベース設計　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　
| 属性 | 設定値 |
|-----|-----|
| データベース名 | enemy_down |
| テーブル名 | 以下の通り |

- game_config
- player_score
- spawn_enemy

## データベース構成
### game_config
|カラム名　　　　 |説明　　 |
|-----|-----|
| id | 主キー、自動採番 |
| game_time | ゲーム時間 |
| difficulty | 難易度 | 

### player_score
|カラム名　　　　 |説明　　 |
|-----|-----|
| id | 主キー、自動採番 |
| player_name | プレイヤー名 |
| score | 倒した敵の得点 |
| difficulty | 難易度 | 
| registered_at | 登録日時 | 

### spawn_enemy
|カラム名　　　　 |説明　　 |
|-----|-----|
| id | 主キー、自動採番 |
| difficulty | 難易度 | 
| enemy_name | 敵の名前 |
| score | 敵の得点 |

## アプリから情報を取得
https://github.com/user-attachments/assets/c34697a3-ef66-497f-8b93-88bcac84fe62

## アプリへの情報追加・更新
https://github.com/user-attachments/assets/b14f19b3-86cc-417f-a992-2c93cc75affd

## 主な使用技術・環境

| |技術・環境   |
|-----|-----|
| バックエンド |![badge](https://img.shields.io/badge/Oracle%20OpenJDK-21.0.8-grey.svg?style=plastic&logo=openjdk&labelColor=red)&nbsp;![badge](https://img.shields.io/badge/SpringBoot-3.5.7-grey.svg?style=plastic&logo=springboot&labelColor=6DB33F&logoColor=white) |
| データベース |![badge](https://img.shields.io/badge/MySQL-8.0.44-grey.svg?style=plastic&logo=mysql&labelColor=4479A1&logoColor=white) | 
| 使用ツール |![badge](https://img.shields.io/badge/GitHub-181717.svg?style=plastic&logo=github)&nbsp;![badge](https://img.shields.io/badge/MyBatis-DD0700.svg?style=plastic)&nbsp;![badge](https://img.shields.io/badge/Postman-FF6C37.svg?style=plastic&logo=postman&logoColor=white)&nbsp;![badge](https://img.shields.io/badge/intellij%20IDEA-2025.2.3-grey.svg?style=plastic&logo=intellijidea&labelColor=000000)| 

## おわりに
* Java学習者のアウトプットして、リポジトリ公開させていただきました。
* 感想・コメント等あればXアカウントまでご連絡くださると幸いです。
