
     ### 👋 Olá! Eu sou o Giovani Dias.

- 🌱 I’m currently learning Python, para entrar no mundo da programação.
- 👯 I’m looking to collaborate on  prjetos simples para iniciantes.
- 🤔 I’m looking for help with conseguiur a primeira vaga!
- 😄 Pronouns: Ele/Dele

-->




##
<div>

<a href="mailto:giovani.eb3@gmail.com" ><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>

<a href="https://www.instagram.com/giovanii.dias" target="_blank"><img src= 
"https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>

<a href= "https://www.linkedin.com/in/giovani-dias-de-abreu-b5b272192" target="_blank"><img src= "https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
</div>


![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=GiovaniiDias&show_icons=true&theme=gruvbox)

@@ -10,14 +10,6 @@ jobs:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Summary Cards
      - uses: actions/checkout@v2
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}

      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: GiovaniiDias
          svg_out_path: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          
          </div>

