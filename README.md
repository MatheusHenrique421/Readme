# Olá, eu sou o Matheus Henrique Schumliak ✌️

# [![Website](https://img.shields.io/website-up-down-green-red/http/monip.org.svg)](https://matheushenrique421.github.io/Portifolio_MatheusHenrique/)

[![steam](https://img.shields.io/badge/Steam-000000?style=for-the-badge&logo=steam&logoColor=white)]()

![MatheusHenrique421's GitHub stats](https://github-readme-stats.vercel.app/api?username=MatheusHenrique421&show_icons=true&theme=merko)

## Tecnologias utilizadas diariamente 🤓🤓🤓

<div>
<img aligin="center" alt="" height="50" wisth="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" />
 
<img aligin="center" alt="" height="50" wisth="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
 
<img aligin="center" alt="" height="50" wisth="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dot-net/dot-net-original.svg" />
 
<img aligin="center" alt="" height="50" wisth="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" />
 
<img aligin="center" alt="" height="50" wisth="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original-wordmark.svg" />
 
<img aligin="center" alt="" height="50" wisth="50" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original-wordmark.svg" />
</div>

#
## Snake on commit
![Snake animation](https://github.com/MatheusHenrique421/MatheusHenrique421/blob/output/github-contribution-grid-snake.svg)
jobs:
  generate:
    runs-on: ubuntu-latest
    timeout-minutes: 10

    steps:
      # generates a snake game from a github user (<github_user_name>) contributions graph, output a svg animation at <svg_out_path>
      - name: generate github-contribution-grid-snake.svg
        uses: Platane/snk@master
        with:
          github_user_name: ${{ github.repository_owner }}
          svg_out_path: dist/github-contribution-grid-snake.svg

      # push the content of <build_dir> to a branch
      # the content will be available at https://raw.githubusercontent.com/<github_user>/<repository>/<target_branch>/<file> , or as github page
      - name: push github-contribution-grid-snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v2.5.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
# 

[![]()]()
