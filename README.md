name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:
  push:
    branches: [main]

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark&color_snake=#10B981&color_dots=#161b22,#064e3b,#047857,#10b981,#34d399

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}<td width="50%">

### Building

- TT2DNN
- Knowledge Minds Scheduler
- PondiMediTourism
- BookYourSlots

</td>
<td width="50%">

### Exploring

- ROS & ROS2
- Reinforcement Learning
- LLM Systems
- AI Research

</td>
</tr>
</table>

---

## Tech Arsenal

### Languages

<p>
<img src="https://skillicons.dev/icons?i=python,ts,js,cpp,c" />
</p>

### Frontend

<p>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,html,css" />
</p>

### Backend

<p>
<img src="https://skillicons.dev/icons?i=nodejs,fastapi,php,mysql,postgres" />
</p>

### AI • Data

<p>
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv" />
</p>

### Tools

<p>
<img src="https://skillicons.dev/icons?i=git,github,vscode,docker,figma" />
</p>

---

## Featured Projects

<table>
<tr>
<td width="50%">

### TT2DNN

AI-powered university timetable generator using Deep Neural Networks.

**Stack**

- Python
- ML
- Streamlit
- MLX

</td>
<td width="50%">

### Knowledge Minds Scheduler

Automated academic scheduling platform.

**Stack**

- React
- PHP
- MySQL

</td>
</tr>

<tr>
<td width="50%">

### PondiMediTourism

Medical tourism platform for Puducherry.

**Stack**

- Next.js
- Fastify
- PostgreSQL

</td>
<td width="50%">

### BookYourSlots

Healthcare appointment platform.

**Stack**

- Next.js
- Firebase
- MongoDB

</td>
</tr>
</table>

---

## GitHub Analytics

<p align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=koorumahey&show_icons=true&theme=github_dark&hide_border=true&title_color=10B981&icon_color=10B981"/>

<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=koorumahey&layout=compact&theme=github_dark&hide_border=true&title_color=10B981"/>

</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com?user=koorumahey&theme=github-dark&hide_border=true&ring=10B981&fire=10B981&currStreakLabel=10B981"/>
</p>

---

## Contribution Universe

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=koorumahey&theme=github-dark&hide_border=true&color=10B981&line=10B981&point=FFFFFF"/>
</p>

---

## Knowledge Minds

```text
Small Steps.
Build Big Worlds.

BUILD  <  LEARN  <  EXPLORE  <  IMPACT
```

---

## Currently Learning

- Deep Learning
- Robotics Engineering
- ROS2
- Reinforcement Learning
- LLM Architecture
- AI Systems Design

---

## Vision

> Building intelligent technology that bridges research and real-world impact.

Whether it's AI, Robotics, Full Stack Development, or future autonomous systems—

**I'm building one project at a time.**

---

<div align="center">

### Connect

[Portfolio](https://koorumahey.com) • [GitHub](https://github.com/koorumahey)

**Thalaivar Nerantharam**

</div>
