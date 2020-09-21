# Rails の ActionTextを試してみる

```
rails new.
rails g scaffold post title:string content:text
rails db:migrate
```

```
rails action_text:install
rails db:migrate
```

https://railsguides.jp/action_text_overview.html

```
rails s
```

http://localhost:3000/posts/new
