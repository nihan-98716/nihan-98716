<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                   ANIMATED HEADER                          -->
<!-- ═══════════════════════════════════════════════════════════ -->

<svg width="800" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00f5c4;stop-opacity:1">
        <animate attributeName="stop-color" values="#00f5c4;#7b61ff;#00f5c4" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#7b61ff;stop-opacity:1">
        <animate attributeName="stop-color" values="#7b61ff;#00f5c4;#7b61ff" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Share+Tech+Mono&amp;display=swap');
      .name-text {
        font-family: 'Share Tech Mono', 'Courier New', monospace;
        font-size: 52px;
        font-weight: bold;
        fill: url(#nameGrad);
        filter: url(#glow);
        opacity: 0;
        animation: fadeIn 1s ease forwards 0.3s;
      }
      .cursor {
        fill: #00f5c4;
        animation: blink 0.9s step-end infinite;
      }
      .scanline {
        fill: none;
        stroke: #00f5c4;
        stroke-width: 0.5;
        opacity: 0.15;
      }
      @keyframes fadeIn {
        to { opacity: 1; }
      }
      @keyframes blink {
        50% { opacity: 0; }
      }
    </style>
  </defs>

  <!-- Scanlines for CRT feel -->
  <line class="scanline" x1="0" y1="20" x2="800" y2="20"/>
  <line class="scanline" x1="0" y1="40" x2="800" y2="40"/>
  <line class="scanline" x1="0" y1="60" x2="800" y2="60"/>
  <line class="scanline" x1="0" y1="80" x2="800" y2="80"/>
  <line class="scanline" x1="0" y1="100" x2="800" y2="100"/>

  <!-- Corner brackets -->
  <path d="M10,10 L10,30 M10,10 L30,10" stroke="#00f5c4" stroke-width="2" fill="none" opacity="0.6"/>
  <path d="M790,10 L790,30 M790,10 L770,10" stroke="#00f5c4" stroke-width="2" fill="none" opacity="0.6"/>
  <path d="M10,110 L10,90 M10,110 L30,110" stroke="#00f5c4" stroke-width="2" fill="none" opacity="0.6"/>
  <path d="M790,110 L790,90 M790,110 L770,110" stroke="#00f5c4" stroke-width="2" fill="none" opacity="0.6"/>

  <!-- Name text -->
  <text x="400" y="75" text-anchor="middle" class="name-text">NIHAN</text>

  <!-- Blinking cursor -->
  <rect x="582" y="40" width="3" height="42" class="cursor"/>
</svg>

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                    TECH INTRO BADGE ROW                    -->
<!-- ═══════════════════════════════════════════════════════════ -->

<br/>

![](https://img.shields.io/badge/Junior%20Year-Computer%20%26%20Communications%20Eng-0d1117?style=flat-square&labelColor=00f5c4&color=0d1117&logoColor=white)
![](https://img.shields.io/badge/Focus-AI%20%7C%20ML%20%7C%20Computer%20Vision-0d1117?style=flat-square&labelColor=7b61ff&color=0d1117)
![](https://img.shields.io/badge/IEEE-Core%20Committee-0d1117?style=flat-square&labelColor=00c8f5&color=0d1117)

<br/>

```
▸ B.Tech · Computer & Communications Engineering · Amrita School of Engineering, Chennai
▸ Interests  →  AI · ML · Computer Vision · Embedded Systems · Graph Networks
▸ Building   →  RAG Chatbots · Security Graphs · CV Pipelines · IoT Systems
▸ Stack      →  Python · C/C++ · TypeScript · PyTorch · TensorFlow · FastAPI · ESP32
▸ Currently  →  Hackathon team Eidos  |  IEEE Core Committee
```

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--               GITHUB CONTRIBUTION GRAPH                    -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

### `[ CONTRIBUTION MATRIX ]`

[![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=nihan-98716&theme=react-dark&bg_color=0d1117&color=00f5c4&line=7b61ff&point=00f5c4&area=true&hide_border=true)](https://github.com/nihan-98716)

<br/>

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nihan-98716&show_icons=true&theme=transparent&hide_border=true&title_color=00f5c4&icon_color=7b61ff&text_color=c9d1d9&bg_color=0d1117)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nihan-98716&layout=compact&theme=transparent&hide_border=true&title_color=00f5c4&text_color=c9d1d9&bg_color=0d1117)

</div>

---

<!-- ═══════════════════════════════════════════════════════════ -->
<!--                     PROJECT INDEX                          -->
<!-- ═══════════════════════════════════════════════════════════ -->

<div align="center">

### `[ PROJECT INDEX ]`

</div>

<br/>

| # | Project | Description | Stack |
|---|---------|-------------|-------|
| `01` | [**NodeFlux**](https://github.com/nihan-98716/NodeFlux) | Real-time MySQL cluster monitoring and management dashboard | `Python` `MySQL` `Dashboard` |
| `02` | [**AEGIS — Adaptive Enterprise Graph Intelligence for Security**](https://github.com/nihan-98716/AEGIS-Adaptive-Enterprise-Graph-Intelligence-for-Security) | Graph-based enterprise security system leveraging GraphSAGE for threat detection | `Python` `GraphSAGE` `GNN` `Security` |
| `03` | [**Cognitive-Aware Dijkstra for Indoor Pathfinding**](https://github.com/nihan-98716/Cognitive-Aware-Dijkstra-for-Indoor-Pathfinding) | Enhanced pathfinding algorithm with cognitive load awareness + XAI panel via Claude API | `Python` `Flask` `Three.js` `Algorithms` |
| `04` | [**Multi-Session RAG Chatbot with PostgreSQL & pgvector**](https://github.com/nihan-98716/Multi-Session-RAG-Chatbot-with-PostgreSQL-pgvector) | Retrieval-augmented generation chatbot with persistent multi-session memory | `FastAPI` `PostgreSQL` `pgvector` `RAG` |
| `05` | [**BankBot — AI Chatbot for Banking FAQs**](https://github.com/nihan-98716/Bankbot-AI_Chatbot_For_Banking_FAQs) | Offline RAG-powered chatbot for banking FAQ resolution | `Python` `RAG` `NLP` `LLM` |
| `06` | [**MailSync — Fully Automated Meeting Scheduler**](https://github.com/nihan-98716/__Mail_Sync-Fully_Automated_Meeting-Scheduler__) | End-to-end automated meeting scheduling via email parsing and calendar integration | `Python` `Automation` `NLP` |
| `07` | [**AI Plant Disease Detection**](https://github.com/nihan-98716/AI-Plant-Disease-Detection) | Computer vision model for identifying plant diseases from leaf imagery | `Python` `TensorFlow` `CV` `CNN` |
| `08` | [**CASIE AI — Carbon Emissions Auditor**](https://github.com/nihan-98716/casie-ai) | AI-powered carbon emissions auditing and sustainability reporting tool | `Python` `ML` `FastAPI` `Sustainability` |

---

<div align="center">

<sub>
<code>// built with caffeine and compiler errors</code>
</sub>

</div>
