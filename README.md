![Snake animation](https://github.com/AYUSHMOHANTY10/github-readme/blob/output/github-contribution-snake.svg)
name: Contribution snake

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update snake grid
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: AYUSHMOHANTY10
          svg_out_path: dist/github-contribution-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
          
<!--![GitHub stats](https://github-readme-stats.vercel.app/api?username=AYUSHMOHANTY10&count_private=true&show_icons=true&hide=issues,contribs)-->
<img src="https://github-readme-streak-stats.herokuapp.com/?user=AYUSHMOHANTY10&theme=tokyonight" alt="mystreak"/>
<img src="https://myreadme.vercel.app/api/embed/AYUSHMOHANTY10?panels=userstatistics,toprepositories,toplanguages,commitgraph" alt="reimaginedreadme" />


### Hey there 👋 

- 🌍 I am from Odisha, India
- 🖥️ Currently a final-year computer science student.
- 🖤 Loves Python Development.
- ✨ Aspiring Data scientist in consulting.
- 🧠 Passionate about Football.
- 👒 Watching anime is a hobby.
- 💀 Loves watching true crime documentaries.
- 📫 Reach me at ayush.mohanty2002@gmail.com

## (◕‿◕) Do drop a follow
