# Olá! Sou a Carol Vaz 👋

Seja bem-vindo(a) ao meu perfil! Vamos embarcar juntos em uma jornada incrível da programação, explorando, aprendendo e crescendo como desenvolvedores 💻🌟. Entre em contato e vamos compartilhar o entusiasmo pela programação! 😄✨

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

    env:
      # a github token is required to fetch the contribution calendar from github API
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## Tecnologias Utilizadas 💻
<div style="display: inline-block;">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="javascript" width="55"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="nodejs" width="55"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="html" width="55"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="css" width="55"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="vscode" width="55"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="git" width="55"/>
</div>

## Como Entrar em Contato 📫
<div>
<a href="https://www.linkedin.com/in/caroline-v-b95019121/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href = "mailto:carolvaz98@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
</div>

## Curiosidades ⚡

⚡ Curiosidade: Além de mergulhar no mundo da programação, sou uma gamer entusiasta! Sempre que posso, dedico um tempo para explorar novos jogos e me aventurar em mundos virtuais. Afinal, aprender sobre novas tecnologias é fascinante, mas também é importante equilibrar com momentos de diversão e entretenimento. 😄🎮

