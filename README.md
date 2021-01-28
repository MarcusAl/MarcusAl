### Hi there 👋



👋🏼 Hello! I've always enjoyed working with technology, ever since I was a little kid. In 2020 I gave up my career in music production to start to learn programming, and it has been great ever since. The first project I ever worked on was for a fictional sushi restaurant ["The Sakoi"](https://cachemegifyoucan.github.io/SakoiWebsite/). Since then I have been fascinated with web development and programming, trying to learn and build as much as possible. Currently I am studying at [@Microverse](https://www.microverse.org) to become a Full Stack Developer. Besides programming I enjoy [📷 music](https://www.youtube.com/channel/UCOJLc_BTPc2Yq8sJxDOCsog), Muay Thai, 🚶🏼‍♂️ hiking, and hanging out with friends.




<div align="center">
    Here are some of my GitHub stats:
    <br>
    <img src="https://github-readme-stats.vercel.app/api?username=CacheMeGifYouCan&show_icons=true&theme=radical&title_color=37B256&icon_color=37B256&count_private=true&hide_title=true&show_owner=true&hide_border=true&hide=commits,contribs">
    <br>
    Not including Private Repositories
</div>

name: Profile Stack

on: [push]

jobs:
  profile_stack:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: Matt-Gleich/profile_stack@master
        with:
          path: config/stack.yml
          badges: false
          technology_emoji: 👨🏻‍💻
          project_emoji: ✨
