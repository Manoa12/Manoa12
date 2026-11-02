<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff41,100:0d1117&height=220&section=header&text=FT_AFA_AFA_BE&fontSize=48&fontColor=00ff41&fontAlignY=35&desc=Cybersecurity%20%26%20Python%20Enthusiast&descAlignY=55&descSize=18&descColor=00ff41&animation=fadeIn" width="100%"/>

<img src="https://github.com/Manoa12.png" width="130" style="border-radius: 50%; border: 2px solid #00ff41;" alt="FT_Afa_Afa_Be"/>

<br/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=00FF41&center=true&vCenter=true&width=600&lines=root%40manoa%3A~%23+whoami;Cybersecurity+Enthusiast;42+Antananarivo+Student;Python+%26+C+Networking • Security • Ethical Hacking Developer;Networking+%E2%80%A2+Security+%E2%80%A2+Ethical+Hacking" alt="Typing SVG" />

![Profile views](https://komarev.com/ghpvc/?username=Manoa12&label=Profile%20views&color=00ff41&style=flat)
![Followers](https://img.shields.io/github/followers/Manoa12?label=Followers&style=flat&color=00ff41)

</div>

---

```bash
┌──(manoa㉿FT_AFA_AFA_BE)-[~]
└─$ cat about_me.txt

[+] Name        : Manoa
[+] Role        : Student @ École 42 Antananarivo
[+] Focus       : Defensive cybersecurity, networking, system administration
[+] Languages   : Python, C, Bash
[+] OS          : Kali Linux (daily driver) + Linux (school workstation)
[+] Status      : Building tools, breaking things (ethically), writing it all up
[+] Contact     : manoalk760@gmail.com

┌──(manoa㉿FT_AFA_AFA_BE)-[~]
└─$ _
```

---

### 🛠️ Stack & tools

<div align="center">

![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=00ff41)
![C](https://img.shields.io/badge/C-000000?style=for-the-badge&logo=c&logoColor=00ff41)
![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=00ff41)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-000000?style=for-the-badge&logo=kalilinux&logoColor=00ff41)
![Bash](https://img.shields.io/badge/Bash-000000?style=for-the-badge&logo=gnubash&logoColor=00ff41)
![Neovim](https://img.shields.io/badge/Neovim-000000?style=for-the-badge&logo=neovim&logoColor=00ff41)
![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=00ff41)
![Wireshark](https://img.shields.io/badge/Wireshark-000000?style=for-the-badge&logo=wireshark&logoColor=00ff41)

</div>

---

### 🚀 Featured projects

| Project | Description |
|---|---|
| 🧩 [Codexion42](https://github.com/Manoa12/Codexion42) | Dining-philosophers-style concurrency exercise in C — threads, mutexes, deadlock & burnout handling |
| 🔎 [network-port-scanner](https://github.com/Manoa12/network-port-scanner) | Simplified nmap-style TCP port scanner in Python, with service detection |
| 📡 [SysAdmin-Network-Checkup](https://github.com/Manoa12/SysAdmin-Network-Checkup) | Read-only Windows network security audit: firewall, ports, shares, ARP |
| 🌍 [IP-Location-Finder](https://github.com/Manoa12/IP-Location-Finder) | Python CLI to geolocate an IP address via ip-api.com |
| 📧 [Email_header_analizer_using_python](https://github.com/Manoa12/Email_header_analizer_using_python) | Email header analysis: routing, SPF/DKIM/DMARC |
| 🔑 [Weak-Password-Finder](https://github.com/Manoa12/Weak-Password-Finder) | Local password-strength auditor (dictionary + capped brute-force) |
| 📶 [wifi-extractor](https://github.com/Manoa12/wifi-extractor) | Recovers WiFi passwords already saved on your own machine |

*(check repo names match what's actually pushed — rename links if needed)*

---

### 📊 GitHub stats

<div align="center">

<img src="https://github-stats-extended.vercel.app/api?username=Manoa12&show_icons=true&theme=react&bg_color=0d1117&title_color=00ff41&icon_color=00ff41&text_color=c9d1d9&border_color=00ff41&hide_border=false" width="48%"/>
<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Manoa12&layout=compact&theme=react&bg_color=0d1117&title_color=00ff41&text_color=c9d1d9&border_color=00ff41&hide_border=false" width="40%"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Manoa12&theme=react&background=0d1117&stroke=00ff41&ring=00ff41&fire=00ff41&currStreakLabel=00ff41&border=00ff41" width="60%"/>

</div>

> Cards powered by [GitHub Stats Extended](https://github.com/stats-organization/github-stats-extended), the actively maintained successor to the now-archived `github-readme-stats`. If a card still doesn't load, that instance may also be rate-limited — consider self-hosting it on your own free Vercel account for full reliability.

---

### 🐍 Contribution snake

<div align="center">

<img src="https://raw.githubusercontent.com/Manoa12/Manoa12/output/github-contribution-grid-snake.svg" width="100%"/>

</div>

<details>
<summary>⚙️ How to enable the snake animation (one-time setup)</summary>

1. In this repo, go to **Settings → Secrets and variables → Actions** — no secret needed, `GITHUB_TOKEN` is automatic.
2. Create `.github/workflows/snake.yml` with:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Manoa12
          outputs: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Push it, run the workflow once manually (**Actions → Generate Snake → Run workflow**), and the animation above will populate.

</details>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00ff41,100:0d1117&height=120&section=footer"/>

*"Networking • Security • Ethical Hacking"* ⚡

</div>
