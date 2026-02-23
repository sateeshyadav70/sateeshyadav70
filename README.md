<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,100:203a43&height=180&section=header&text=SATEESH%20KUMAR&fontSize=40&fontColor=00F7FF&animation=fadeIn"/>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=28&duration=3000&color=00F7FF&center=true&vCenter=true&width=600&lines=UI+Motion+Architect;Frontend+Systems+Builder;Crafting+Digital+Realities;React+%7C+Node+%7C+System+Design" />
</h1>

---

## ⚡ About Me

```bash
> whoami
Sateesh Kumar

> role
Frontend Systems Builder

> currently_building
Cinematic 3D Web Interfaces

> exploring
System Design • Scalable Backends • AI Integrations

> tech_stack
React | Tailwind | Node.js | MongoDB | System Design
name: Generate Snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: sateeshyadav70
          outputs: |
            dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
