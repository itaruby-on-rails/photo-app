・rails command
rails g controller welcome index
bundle install --without production
heroku create
heroku rename itaru-photo-app
git push
git push Heroku master
<!-- platform エラー発生 -->
bundle lock --add-platform x86_64-linux
bundle install --without production
bundle update
#git add. git commitする
git push Heroku master
<!-- H10エラー発生
heroku run rails consoleでエラーの詳細を調べる。
cannot load such file -- net/pop (LoadError) エラー
-->
下記をgemに追加
https://stackoverflow-com.translate.goog/questions/70500220/rails-7-ruby-3-1-loaderror-cannot-load-such-file-net-smtp?_x_tr_sl=en&_x_tr_tl=ja&_x_tr_hl=ja&_x_tr_pto=sc#:~:text=101-,Rails%206%20%E3%81%AE%E5%A0%B4%E5%90%88,-Gemfile%E3%81%AB%E8%BF%BD%E5%8A%A0
----
gem 'net-smtp', require: false
gem 'net-imap', require: false
gem 'net-pop', require: false
----
bundle install --without production
bundle update
#git add. git commitする
