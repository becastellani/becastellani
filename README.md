<div style="width: 100%;">
  <a href="https://github.com/becastellani/becastellani/blame/main/welcome.svg">
    <img src="welcome.svg" style="width: 100%;" alt="Click to see the source">
  </a>
</div>

<div align="center">
  <a href="https://github.com/becastellani">
    <img height="160em" src="https://github-readme-stats.vercel.app/api?username=becastellani&show_icons=true&theme=dark&hide_border=false&show_owner=true"/>
    <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=becastellani&theme=dark&hide_border=false&&layout=compact"/>
  </a>
</div>

<div align="center"> 
  <a href="https://instagram.com/bernardo_castell/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:becastellani10@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/bernardo-castellani-b515a0203/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  
</div>

- uses: Platane/snk@v2
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    becastellani ${{ github.repository_owner }}

    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

