Application
===


Rails
---

### sample

```
# topページ作成
$ rails g controller top index

# Topの表示設定
$ vim config/routes.rb

Rails.application.routes.draw do
    root :to => 'info#index'
end

# routes設定更新
$ rake routes

# rails起動
$ rails s
```

http://localhost:3000/

