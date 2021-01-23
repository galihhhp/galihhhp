### Hi there 👋

- 🔭 I’m currently attending bootcamp on Binar Academy
- 🌱 I’m currently learning Full Stack Javascript and Basic Devops
- 📫 How to reach me: 
  - LinkedIn: Pangestu Galih Pambayun
  - Instagram, Twitter & others: galihhhp
  
name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'
  workflow_dispatch:
jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ 876b75e3-f525-4002-b855-f814f9defd77 }}
          GH_TOKEN: ${{ 15eeffd6f0dadbe228a499fd89de6b1dda8e081e }}
          SHOW_OS: "True"
          SHOW_PROJECTS: "True"
  
  [![galihhhp's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=galihhhp&v=2)](https://wakatime.com/@galihhhp)
