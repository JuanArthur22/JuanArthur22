# 💫 About Me:
Sou Juan Arthur, atualmente com 18 anos, estou cursando Bacharelado em Ciência de Dados e Inteligência Artificial no SENAI Cimatec.

Atualmente atuo como jovem aprendiz na X Mold, como assistente administrativo, onde desenvolvo habilidades como organização, análise de processos, responsabilidade e atenção aos detalhes — competências que também aplico na área de tecnologia, especialmente no tratamento de dados e resolução de problemas.

Tenho me dedicado à construção de uma base sólida em tecnologia, com interesse em desenvolvimento de software, banco de dados, cibersegurança e linguagens de programação como Python e C. Busco aplicar esses conhecimentos na criação de soluções eficientes, orientadas a dados e alinhadas às necessidades do negócio.

Minha experiência administrativa, aliada à formação em tecnologia, me permite ter uma visão mais estratégica, compreendendo tanto os processos organizacionais quanto as soluções tecnológicas que podem otimizá-los. Dessa forma, estou apto a atuar tanto na área de TI quanto em funções administrativas com foco em melhoria de processos e análise de dados.

Tenho como objetivo evoluir profissionalmente na área de tecnologia, especialmente em Ciência de Dados e Inteligência Artificial, mantendo sempre uma abordagem prática e orientada a resultados.

Além disso, estou me aprimorando na língua inglesa, com foco na ampliação das minhas oportunidades no cenário global.

Possuo familiaridade com diversas tecnologias e ferramentas, incluindo:

Linguagens e Frameworks: HTML5, CSS3, JavaScript, PHP, Python, C, Bootstrap, Node.js

Ferramentas e plataformas: Git, GitHub, XAMPP, Canva, Figma, GIMP, Notion, Insomnia, Jira

Testes e Qualidade: Cypress, Cucumber

Banco de Dados: MySQL

Sistemas Operacionais: Kali Linux

Estou comprometido com o aprendizado contínuo e preparado para contribuir tanto em projetos tecnológicos quanto em atividades administrativas que demandem organização, análise e melhoria de processos.<br><br>


# 💻 Tech Stack:
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![CYPRESS](https://img.shields.io/badge/CYPRESS-33c30.svg?style=for-the-badge&logo=cypress&logoColor=black) ![CUCUMBER](https://img.shields.io/badge/CUCUMBER-%376B36.svg?style=for-the-badge&logo=cucumber&logoColor=black) ![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![Gimp](https://img.shields.io/badge/Gimp-657D8B?style=for-the-badge&logo=gimp&logoColor=FFFFFF) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![KALI LINUX](https://img.shields.io/badge/KALI%20LINUX-blue.svg?style=for-the-badge&logo=kalilinux&logoColor=black) ![Jira](https://img.shields.io/badge/jira-%230A0FFF.svg?style=for-the-badge&logo=jira&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![XAMPP](https://img.shields.io/badge/XAMPP-orange?style=for-the-badge&logo=xampp&logoColor=white) 
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=JuanArthur22&theme=dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=JuanArthur22&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=JuanArthur22&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=JuanArthur22&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=JuanArthur22&icon=0&color=0)](https://visitcount.itsvg.in)

# GitHub Action for generating a contribution graph with a snake eating your contributions.

name: Generate Snake

# Controls when the action will run. This action runs every 6 hours.

on:
  schedule:
      # every 6 hours
    - cron: "0 */6 * * *"

# This command allows us to run the Action automatically from the Actions tab.
  workflow_dispatch:

# The sequence of runs in this workflow:
jobs:
  # This workflow contains a single job called "build"
  build:
    # The type of runner that the job will run on
    runs-on: ubuntu-latest

    # Steps represent a sequence of tasks that will be executed as part of the job
    steps:

    # Checks repo under $GITHUB_WORKSHOP, so your job can access it
      - uses: actions/checkout@v2

    # Generates the snake  
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: mishmanners
          # these next 2 lines generate the files on a branch called "output". This keeps the main branch from cluttering up.
          gif_out_path: dist/github-contribution-grid-snake.gif
          svg_out_path: dist/github-contribution-grid-snake.svg

     # show the status of the build. Makes it easier for debugging (if there's any issues).
      - run: git status

      # Push the changes
      - name: Push changes
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          branch: master
          force: true

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          # the output branch we mentioned above
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
