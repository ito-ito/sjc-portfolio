## コンテナの起動

1. clone

   ```zsh
   git clone --recursive https://github.com/ito-ito/sjc-portfolio.git
   ```

   もし options をつけ忘れた場合は以下を実行してください

   ```zsh
   git submodule update --init --recursive
   ```

2. run container

   ```zsh
   docker compose up -d
   ```

3. DB setup(optional)

   ```zsh
   docker compose run back bundle exec rails db:setup
   ```

4. access
   [localhost:8000/](localhost:8000)

### コンテナの停止

```
docker compse down
```
