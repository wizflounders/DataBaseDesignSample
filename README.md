# Database Design Sample

## DB設計　

## users table
|column|type||options|
|name|string|index: true, null: false, unique: true|
|email|string|null: false|

• has_many :tweets
• has_many :comments
