# SJC Portfolio

## About the Project

<img src="https://github.com/ito-ito/sjc-portfolio/assets/1092010/eb9508ad-ca3b-413a-989a-71bc53469c14">

検証のためのポートフォリオです  
掲載されている情報はダミーデータで事実とは異なります

## Technology Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,ruby,rails,postgres,docker&perline=4" />
  </a>
</p>

## Getting Started

1. clone the repo

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

3. setup for DB

   ```zsh
   docker compose run back bundle exec rails db:setup
   ```

4. access to page

   access to [localhost:8000/](http:localhost:8000)

## Stopping container

```zsh
docker compse down
```
