## Olá! eu sou  Willams Antônio - 👨‍💻
#### •🌐cursando Análise e Desenvolvimento de Sistemas
#### •⚓Aprovado no CORPO DE FUZILEIROS NAVAIS em 4 meses
#### • Trabalhando atualmente com C
#### •🥊Muay Thai ムエボラン



## Contatos
[![instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/willams_antoni0/)
[![telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/+5581993575384)
[![gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:willamss547@gmail.com)

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=WillamsAntoni0&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=merko&locale=en&hide_border=false&order=1" height="150" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=WillamsAntoni0&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=merko&hide_border=false&order=2" height="150" alt="languages graph"  />
</div>

###

<img src="https://raw.githubusercontent.com/WillamsAntoni0/WillamsAntoni0/output/snake.svg" alt="Snake animation" />
name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

###


## Uso atual
<div style="display: inline_block">  
<img align="center" alt="python"  src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img align="center" alt="python"  src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
<img align="center" alt="c"     src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
</div>

## ÚLTIMOS VÍDEOS:
#### Criação de vídeos com IA
•https://youtu.be/jku-Mlibl84?si=1A6oj17QHqhBD_0g

•https://youtu.be/RDems9qdD7E?si=2whv52qlzQnQaDMx


