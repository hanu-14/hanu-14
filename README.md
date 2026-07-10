<p align="center">
  <svg width="100%" height="300" viewBox="0 0 1000 300" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#05080f"/>
        <stop offset="50%" stop-color="#0a0e1a"/>
        <stop offset="100%" stop-color="#05080f"/>
      </linearGradient>
      <linearGradient id="aurora1" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#58a6ff" stop-opacity="0.08"/>
        <stop offset="50%" stop-color="#8b5cf6" stop-opacity="0.05"/>
        <stop offset="100%" stop-color="#06d6a0" stop-opacity="0"/>
      </linearGradient>
      <linearGradient id="aurora2" x1="100%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#8b5cf6" stop-opacity="0.06"/>
        <stop offset="50%" stop-color="#58a6ff" stop-opacity="0.04"/>
        <stop offset="100%" stop-color="#e11d48" stop-opacity="0"/>
      </linearGradient>
      <linearGradient id="textGlow" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#58a6ff"/>
        <stop offset="50%" stop-color="#8b5cf6"/>
        <stop offset="100%" stop-color="#06d6a0"/>
      </linearGradient>
      <filter id="neonGlow">
        <feGaussianBlur stdDeviation="4" result="blur1"/>
        <feGaussianBlur stdDeviation="8" result="blur2"/>
        <feGaussianBlur stdDeviation="16" result="blur3"/>
        <feMerge>
          <feMergeNode in="blur3"/>
          <feMergeNode in="blur2"/>
          <feMergeNode in="blur1"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <filter id="softGlow">
        <feGaussianBlur stdDeviation="2" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <rect width="1000" height="300" fill="url(#bgGrad)"/>

    <rect width="1000" height="300" fill="url(#aurora1)">
      <animate attributeName="opacity" values="0.6;1;0.6" dur="8s" repeatCount="indefinite"/>
    </rect>
    <rect width="1000" height="300" fill="url(#aurora2)">
      <animate attributeName="opacity" values="0.4;0.8;0.4" dur="10s" repeatCount="indefinite"/>
    </rect>

    <g stroke="#1a2332" stroke-width="0.5" opacity="0.4">
      <line x1="0" y1="75" x2="1000" y2="75"/>
      <line x1="0" y1="150" x2="1000" y2="150"/>
      <line x1="0" y1="225" x2="1000" y2="225"/>
      <line x1="250" y1="0" x2="250" y2="300"/>
      <line x1="500" y1="0" x2="500" y2="300"/>
      <line x1="750" y1="0" x2="750" y2="300"/>
    </g>

    <rect x="0" y="146" width="1000" height="8" fill="url(#textGlow)" opacity="0.15">
      <animate attributeName="opacity" values="0.1;0.25;0.1" dur="5s" repeatCount="indefinite"/>
    </rect>

    <text x="500" y="130" text-anchor="middle" font-family="'Courier New', monospace" font-size="64" font-weight="900" fill="url(#textGlow)" filter="url(#neonGlow)" letter-spacing="4">
      MOHAMMED HANAN
      <animate attributeName="opacity" values="0.8;1;0.8" dur="4s" repeatCount="indefinite"/>
    </text>

    <text x="500" y="175" text-anchor="middle" font-family="'Courier New', monospace" font-size="17" fill="#8b949e" filter="url(#softGlow)" letter-spacing="6" text-transform="uppercase">
      AI ENTHUSIAST · AUTOMATION ARCHITECT · BOUNTY HUNTER
      <animate attributeName="opacity" values="0.6;1;0.6" dur="6s" repeatCount="indefinite"/>
    </text>

    <circle cx="120" cy="60" r="1.5" fill="#58a6ff">
      <animate attributeName="opacity" values="0;1;0" dur="3s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="60;55;60" dur="2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="250" cy="90" r="1" fill="#8b5cf6">
      <animate attributeName="opacity" values="0;1;0" dur="4s" repeatCount="indefinite" begin="1s"/>
      <animate attributeName="cy" values="90;83;90" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="750" cy="45" r="1.5" fill="#06d6a0">
      <animate attributeName="opacity" values="0;1;0" dur="3.5s" repeatCount="indefinite" begin="0.5s"/>
      <animate attributeName="cy" values="45;39;45" dur="2.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="880" cy="70" r="1" fill="#58a6ff">
      <animate attributeName="opacity" values="0;1;0" dur="4.5s" repeatCount="indefinite" begin="2s"/>
      <animate attributeName="cy" values="70;64;70" dur="3s" repeatCount="indefinite"/>
    </circle>
    <circle cx="400" cy="40" r="1" fill="#8b5cf6">
      <animate attributeName="opacity" values="0;1;0" dur="3.8s" repeatCount="indefinite" begin="1.5s"/>
    </circle>
    <circle cx="600" cy="55" r="1.5" fill="#06d6a0">
      <animate attributeName="opacity" values="0;1;0" dur="3.2s" repeatCount="indefinite" begin="3s"/>
    </circle>
    <circle cx="350" cy="230" r="1" fill="#58a6ff">
      <animate attributeName="opacity" values="0;1;0" dur="5s" repeatCount="indefinite" begin="0.8s"/>
    </circle>
    <circle cx="680" cy="250" r="1.5" fill="#8b5cf6">
      <animate attributeName="opacity" values="0;1;0" dur="4.2s" repeatCount="indefinite" begin="2.5s"/>
    </circle>
    <circle cx="150" cy="240" r="1" fill="#06d6a0">
      <animate attributeName="opacity" values="0;1;0" dur="3.7s" repeatCount="indefinite" begin="1.8s"/>
    </circle>
  </svg>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=20&duration=2200&pause=600&color=58A6FF&center=true&vCenter=true&width=700&lines=AI+Enthusiast;I+Automate+Anything;RAG+%7C+Hermes+Agent+%7C+Clawbot;Hugging+Face+%7C+Computer+Vision;Open+Source+Bounty+Hunter" alt="Typing SVG" /></a>
</p>

<br/>

<p align="center">
  <a href="https://github.com/hanu-14"><img src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/mohammed-hanan-m-t-p-92ba5437a/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:hananmtp313@gmail.com"><img src="https://img.shields.io/badge/email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://itsmehanan.netlify.app/"><img src="https://img.shields.io/badge/portfolio-000000?style=for-the-badge&logo=webpack&logoColor=white"/></a>
</p>

<br/>
<br/>

<!-- 3D CARD SVG -->
<p align="center">
  <svg width="720" height="280" viewBox="0 0 720 280" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="cardBg" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#0d1117"/>
        <stop offset="100%" stop-color="#090c14"/>
      </linearGradient>
      <linearGradient id="cardBorder" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#58a6ff" stop-opacity="0.5"/>
        <stop offset="50%" stop-color="#8b5cf6" stop-opacity="0.3"/>
        <stop offset="100%" stop-color="#06d6a0" stop-opacity="0.5"/>
      </linearGradient>
      <linearGradient id="accentBar" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#58a6ff"/>
        <stop offset="50%" stop-color="#8b5cf6"/>
        <stop offset="100%" stop-color="#06d6a0"/>
      </linearGradient>
      <filter id="cardShadow">
        <feDropShadow dx="0" dy="10" stdDeviation="20" flood-color="#000" flood-opacity="0.7"/>
      </filter>
    </defs>

    <rect x="0" y="0" width="720" height="280" rx="16" ry="16" fill="#000" opacity="0.5" transform="translate(0,8)" filter="url(#cardShadow)"/>

    <rect x="0" y="0" width="720" height="280" rx="16" ry="16" fill="url(#cardBg)" stroke="url(#cardBorder)" stroke-width="1.5"/>

    <rect x="24" y="16" width="4" height="16" rx="2" ry="2" fill="url(#accentBar)">
      <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
    </rect>

    <text x="40" y="30" font-family="'Courier New', monospace" font-size="13" font-weight="700" fill="#58a6ff" letter-spacing="3">PROFILE</text>

    <!-- divider line -->
    <line x1="24" y1="48" x2="696" y2="48" stroke="#58a6ff" stroke-opacity="0.08" stroke-width="1"/>

    <g font-family="'Courier New', monospace" font-size="12">
      <text x="36" y="80" fill="#8b949e">designation:</text>
      <text x="200" y="80" fill="#c9d1d9" font-weight="700">Automation Architect</text>

      <text x="36" y="106" fill="#8b949e">location:</text>
      <text x="200" y="106" fill="#c9d1d9" font-weight="700">Kerala, India</text>

      <text x="36" y="132" fill="#8b949e">education:</text>
      <text x="200" y="132" fill="#c9d1d9" font-weight="700">B.Tech Electrical &amp; Electronics Engineering</text>

      <text x="36" y="158" fill="#8b949e">stack:</text>
      <text x="200" y="158" fill="#c9d1d9" font-weight="700">Hugging Face, RAG, Hermes Agent, Clawbot, PyTorch, OpenCV</text>

      <text x="36" y="184" fill="#8b949e">ethos:</text>
      <text x="200" y="184" fill="#58a6ff" font-weight="700">I automate anything — code, workflows, agents, the physical world.</text>

      <text x="36" y="210" fill="#8b949e">status:</text>
      <text x="200" y="210" fill="#06d6a0" font-weight="700">
        Building the next autonomous system.
        <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite"/>
      </text>
    </g>

    <line x1="24" y1="238" x2="696" y2="238" stroke="#58a6ff" stroke-opacity="0.06" stroke-width="1"/>

    <circle cx="30" cy="260" r="2.5" fill="#58a6ff">
      <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite"/>
    </circle>
    <text x="42" y="264" font-family="'Courier New', monospace" font-size="10" fill="#30363d">active since 2023</text>
    <text x="678" y="264" text-anchor="end" font-family="'Courier New', monospace" font-size="10" fill="#30363d">automated@cosmiq</text>
  </svg>
</p>

<br/>
<br/>

<!-- GRID + ABOUT -->
<table>
<tr>
<td width="60%" valign="top">

### the mission

I build systems that make other work obsolete.

Electrical & Electronics Engineering student who crossed into AI and never looked back. I've built autonomous agents that hunt freelance jobs while you sleep, visual intelligence platforms that search CCTV footage with natural language, and RAG pipelines that give machines memory.

I work with **Hugging Face**, **RAG**, **Hermes Agent**, **Clawbot**, **PyTorch**, **OpenCV** — whatever it takes to make a system run itself.

**If it can be automated, I automate it.**

</td>
<td width="40%" align="center" valign="top">

<img src="https://github-readme-stats.vercel.app/api?username=hanu-14&show_icons=true&theme=radical&hide_border=true&count_private=true&include_all_commits=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&custom_title=stats" width="100%"/>

</td>
</tr>
</table>

<br/>

<p align="center">
  <img src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg" width="100%"/>
</p>

<br/>

<details open>
<summary><b>highlights</b></summary>

<br/>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=hanu-14&theme=radical&no-frame=true&no-bg=true&row=2&column=3&margin-w=15&margin-h=15" width="70%"/>
</p>

<br/>

<table>
<tr>
<td width="33%" align="center">🏆 <b>National AIR 1</b><br/><sub>ARC Dubai 2024</sub></td>
<td width="33%" align="center">📜 <b>Patent Filed</b><br/><sub>Battery-free biometrics</sub></td>
<td width="33%" align="center">⚡ <b>1,500+</b><br/><sub>Contributions this year</sub></td>
</tr>
</table>

<br/>

<table>
<tr>
<td width="50%">

**PhotonIQ** — AI visual intelligence platform. Search CCTV footage with natural language.

</td>
<td width="50%">

**Perpetual** — Autonomous agent that finds and wins freelance jobs. You sleep — it works.

</td>
</tr>
<tr>
<td width="50%">

**Bounty-Hunters** — Fixed Solidity vulns (LiquidityPool, CrossChainBridge, MultiSigWallet).

</td>
<td width="50%">

**Pipedream** — Contributed actions (Voice Download, LinkupAPI V2) to 11.5k star repo.

</td>
</tr>
</table>

</details>

<br/>
<br/>

<svg width="100%" height="1" viewBox="0 0 1000 1" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="0" x2="1000" y2="0" stroke="url(#textGlow)" stroke-width="1" opacity="0.3"/>
</svg>

<br/>

## arsenal

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/LangChain-1C3D5A?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Neovim-57A143?style=for-the-badge&logo=neovim&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

<br/>

<svg width="100%" height="1" viewBox="0 0 1000 1" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="0" x2="1000" y2="0" stroke="url(#textGlow)" stroke-width="1" opacity="0.3"/>
</svg>

<br/>

## builds

<br/>

<table>
<tr>
<td width="50%" valign="top">

### [PhotonIQ](https://github.com/hanu-14/photoniq)

> Search CCTV footage with natural language. AI visual intelligence.

`PyTorch` `RT-DETR` `OpenCV` `FastAPI`

</td>
<td width="50%" valign="top">

### [Perpetual](https://github.com/hanu-14/perpetual)

> An autonomous agent that finds, applies, and wins freelance jobs.

`Python` `Hermes Agent` `Automation` `Telegram API`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [CosmIQ](https://github.com/hanu-14/cosmiq)

> AI automation tools, developer products, and systems that run themselves.

`AI` `Automation` `RAG` `Developer Tools`

</td>
<td width="50%" valign="top">

### [Computer Vision](https://github.com/hanu-14/computer-vision)

> Object detection, inference optimization, model evaluation.

`PyTorch` `OpenCV` `Clawbot` `RT-DETR`

</td>
</tr>
</table>

<br/>

<svg width="100%" height="1" viewBox="0 0 1000 1" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="0" x2="1000" y2="0" stroke="url(#textGlow)" stroke-width="1" opacity="0.3"/>
</svg>

<br/>

## grind

<br/>

<p align="center">
  <a href="https://github.com/ashutosh00710/github-readme-activity-graph">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=hanu-14&theme=react-dark&hide_border=true&area=true&custom_title=pulse" width="95%"/>
  </a>
</p>

<br/>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=hanu-14&theme=black-ice&hide_border=true&stroke=58A6FF&background=0D1117&fire=58A6FF&currStreakLabel=58A6FF" width="70%"/>
</p>

<br/>

<svg width="100%" height="1" viewBox="0 0 1000 1" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="0" x2="1000" y2="0" stroke="url(#textGlow)" stroke-width="1" opacity="0.3"/>
</svg>

<br/>

## bounties

<br/>

<table>
<tr>
<th>repo</th>
<th>hit</th>
</tr>
<tr>
<td>UnsafeLabs/Bounty-Hunters</td>
<td>LiquidityPool — first-depositor manipulation fix</td>
</tr>
<tr>
<td>UnsafeLabs/Bounty-Hunters</td>
<td>CrossChainBridge — replay attack fix</td>
</tr>
<tr>
<td>UnsafeLabs/Bounty-Hunters</td>
<td>MultiSigWallet — confirmation race condition fix</td>
</tr>
<tr>
<td>PipedreamHQ/pipedream</td>
<td>Download Voice Message action (new)</td>
</tr>
<tr>
<td>PipedreamHQ/pipedream</td>
<td>LinkupAPI V2 — auth update</td>
</tr>
</table>

<br/>

<svg width="100%" height="1" viewBox="0 0 1000 1" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="0" x2="1000" y2="0" stroke="url(#textGlow)" stroke-width="1" opacity="0.3"/>
</svg>

<br/>

## right now

<br/>

<p align="center">
  <code>🏗️ building</code> CosmIQ — autonomous agent suite<br/>
  <code>📚 learning</code> Distributed systems, advanced RAG, agent orchestration<br/>
  <code>🎯 hunting</code> Open source bounties across high-impact repos<br/>
  <code>📖 reading</code> AI papers, system design, embedded systems<br/>
</p>

<br/>

<svg width="100%" height="1" viewBox="0 0 1000 1" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
  <line x1="0" y1="0" x2="1000" y2="0" stroke="url(#textGlow)" stroke-width="1" opacity="0.3"/>
</svg>

<br/>

## connect

<br/>

<p align="center">
  <a href="mailto:hananmtp313@gmail.com"><img src="https://img.shields.io/badge/hananmtp313@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://itsmehanan.netlify.app/"><img src="https://img.shields.io/badge/portfolio-000000?style=for-the-badge&logo=netlify&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/mohammed-hanan-m-t-p-92ba5437a/"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/hanu-14"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

<br/>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=hanu-14&label=glances&color=58A6FF&style=flat" />
</p>

<br/>

<!-- FOOTER SVG -->
<p align="center">
  <svg width="100%" height="180" viewBox="0 0 1000 180" preserveAspectRatio="xMidYMid meet" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="footerBg" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" stop-color="#05080f" stop-opacity="0"/>
        <stop offset="100%" stop-color="#05080f"/>
      </linearGradient>
      <linearGradient id="footerGlow" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#8b5cf6" stop-opacity="0"/>
        <stop offset="50%" stop-color="#58a6ff" stop-opacity="0.3"/>
        <stop offset="100%" stop-color="#06d6a0" stop-opacity="0"/>
      </linearGradient>
    </defs>

    <rect width="1000" height="180" fill="url(#footerBg)"/>

    <rect x="0" y="0" width="1000" height="2" fill="url(#footerGlow)">
      <animate attributeName="opacity" values="0.2;0.6;0.2" dur="6s" repeatCount="indefinite"/>
    </rect>

    <text x="500" y="70" text-anchor="middle" font-family="'Courier New', monospace" font-size="14" fill="#30363d" letter-spacing="8">
      MOHAMMED HANAN
    </text>

    <text x="500" y="100" text-anchor="middle" font-family="'Courier New', monospace" font-size="11" fill="#21262d" letter-spacing="4">
      IF IT CAN BE AUTOMATED, I AUTOMATE IT.
    </text>

    <circle cx="200" cy="140" r="1" fill="#58a6ff">
      <animate attributeName="opacity" values="0;0.6;0" dur="5s" repeatCount="indefinite" begin="1s"/>
    </circle>
    <circle cx="500" cy="150" r="1" fill="#8b5cf6">
      <animate attributeName="opacity" values="0;0.6;0" dur="4s" repeatCount="indefinite" begin="3s"/>
    </circle>
    <circle cx="800" cy="145" r="1" fill="#06d6a0">
      <animate attributeName="opacity" values="0;0.6;0" dur="6s" repeatCount="indefinite" begin="0.5s"/>
    </circle>
  </svg>
</p>
