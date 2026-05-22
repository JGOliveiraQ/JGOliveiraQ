
<!-- TYPING ANIMATION -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=20&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=650&lines=Ol%C3%A1%2C+sou+Jo%C3%A3o+Guilherme+%F0%9F%91%8B;Building+digital+solutions+from+Recife+%F0%9F%8C%8A;Python+%7C+JavaScript+%7C+TypeScript+%7C+Java;AI+Builder+%7C+Cybersecurity+Enthusiast+%F0%9F%94%90;Always+learning%2C+always+evolving+%F0%9F%9A%80" alt="Typing SVG"/>
  </a>
</p>

<!-- SOCIAL BADGES -->
<div align="center">
  <a href="https://www.linkedin.com/in/joaoguilhermeo/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <a href="mailto:jgoliveiraqm@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  &nbsp;
  <a href="https://bit.ly/3QejHXT" target="_blank">
    <img src="https://img.shields.io/badge/Portfólio-FF5722?style=for-the-badge&logo=firefox-browser&logoColor=white" alt="Portfolio"/>
  </a>
  &nbsp;
  <a href="https://www.instagram.com/jgoliveiraq" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=jgoliveiraqm&style=for-the-badge&color=302b63&label=VISITANTES" alt="Profile Views"/>
</div>

<br/>

---

## 🙋‍♂️ Sobre mim

<img align="right" height="200" src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="coding gif"/>

```yaml
name:       João Guilherme Oliveira
location:   Recife, Pernambuco 🇧🇷
education:
  - ADS @ Senac PE — Embarque Digital (2025–2027)
  - Administração @ Faculdade Ouro Moderno (2026–2027)
role:       IT Intern @ Agência Castelo (Remoto)
focus:
  - Software Development
  - Artificial Intelligence
  - Cybersecurity
  - DevOps & CI/CD
certifications: 10+
fun_fact:   "18 anos, 2 graduações, 1 estágio e infinita vontade de inovar 🔥"
```

> *"A tecnologia só cumpre seu papel quando une **confiança**, **clareza** e **inovação**."*

<br/>

---

## 🛠️ Arsenal Tecnológico

<div align="center">

### ⚡ Linguagens

<img src="https://skillicons.dev/icons?i=python,javascript,typescript,java,html,css&perline=6&theme=dark"/>

### 🧰 Ferramentas & Plataformas

<img src="https://skillicons.dev/icons?i=git,github,vscode,figma,linux,postgres&perline=6&theme=dark"/>

### 🤖 Explorando Ativamente

<img src="https://skillicons.dev/icons?i=docker,nodejs,react,bash&perline=4&theme=dark"/>

</div>

<br/>

---

## 🚀 Projetos Reais — O que eu já construí

> Sem estar formado. Sem esperar permissão. Só código que funciona em produção.

<br/>

<!-- PROJETO 1: INSTAGRAM MONITOR -->
<table>
  <tr>
    <td width="58" align="center">📊</td>
    <td>
      <h3>Instagram Monitor — Automação + Dashboard de Métricas</h3>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <p>
        Sistema completo para monitoramento automático de perfis do Instagram de clientes de uma agência de marketing.
        Coleta seguidores e posts diariamente, processa crescimento semanal/mensal e exibe tudo num dashboard web com login individualizado por cliente.
      </p>
      <p><strong>Destaques técnicos:</strong></p>
      <ul>
        <li>Scraping autenticado da API interna do Instagram com sessão persistida</li>
        <li>Roteamento de tráfego pela <strong>rede Tor (SOCKS5)</strong> com rotação automática de circuito entre requisições — evita banimento de IP</li>
        <li><strong>GitHub Actions CI/CD</strong> agendado diariamente às 11h — roda sem intervenção humana</li>
        <li>Credenciais protegidas como <strong>GitHub Secrets</strong>, restauradas em runtime no pipeline</li>
        <li>Integração com <strong>Google Sheets API</strong> como banco de dados de séries temporais</li>
        <li>Flask com multi-tenant: cada cliente só acessa seus próprios dados; admin vê todos</li>
        <li>API REST com análise de crescimento (7d / 30d) e detecção de tendência (up/down/stable)</li>
      </ul>
      <br/>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
      <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white"/>
      <img src="https://img.shields.io/badge/Tor-7D4698?style=flat-square&logo=torproject&logoColor=white"/>
      <img src="https://img.shields.io/badge/Google_Sheets-34A853?style=flat-square&logo=google-sheets&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white"/>
      <img src="https://img.shields.io/badge/CI%2FCD-Agendado%20Diariamente-a78bfa?style=flat-square"/>
    </td>
  </tr>
</table>

<br/>

<!-- PROJETO 2: GMB REVIEWS AI -->
<table>
  <tr>
    <td width="58" align="center">🤖</td>
    <td>
      <h3>GMB Reviews AI — Resposta Automática de Avaliações com IA</h3>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <p>
        Plataforma fullstack que conecta ao <strong>Google My Business API</strong> para gerenciar avaliações de clientes
        e gera respostas profissionais e empáticas automaticamente usando IA — sem custo de API externa, rodando um LLM local.
      </p>
      <p><strong>Destaques técnicos:</strong></p>
      <ul>
        <li>Autenticação via <strong>Google OAuth2</strong> com escopo <code>business.manage</code></li>
        <li>Backend <strong>Node.js + Express</strong> integrado ao Google Business API</li>
        <li>Frontend em <strong>Next.js</strong> (React + TypeScript)</li>
        <li>IA de resposta usando <strong>Ollama (LLaMA 3)</strong> rodando localmente — zero custo de inference</li>
        <li>Prompt engineering contextualizado com nota da avaliação + comentário do cliente</li>
        <li>Arquitetura desacoplada com REST API separando frontend e backend</li>
      </ul>
      <br/>
      <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white"/>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Google_Business_API-4285F4?style=flat-square&logo=google&logoColor=white"/>
      <img src="https://img.shields.io/badge/LLaMA_3-FF6B35?style=flat-square&logo=meta&logoColor=white"/>
      <img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white"/>
      <img src="https://img.shields.io/badge/OAuth2-EB5424?style=flat-square&logo=auth0&logoColor=white"/>
    </td>
  </tr>
</table>

<br/>

<!-- PROJETO 3: BIGU -->
<table>
  <tr>
    <td width="58" align="center">🚌</td>
    <td>
      <h3>Bigu — App de Mobilidade Urbana do Grande Recife</h3>
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <p>
        Solução de mobilidade urbana para a Região Metropolitana do Recife, apresentada como projeto acadêmico de impacto real.
        Atuei desde o planejamento estratégico até a identidade visual e arquitetura tecnológica — transformando um problema urbano em produto digital.
      </p>
      <br/>
      <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-a78bfa?style=flat-square"/>
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white"/>
      <img src="https://img.shields.io/badge/Recife-PE-302b63?style=flat-square"/>
    </td>
  </tr>
</table>

<br/>

---

## 📜 Certificações & Conquistas

<div align="center">

| 🏅 Certificação | 🏛️ Instituição | 📅 Ano |
|:---|:---:|:---:|
| 🤖 AI Fluency: Framework & Foundations | **Anthropic** | 2026 |
| 🧠 Agentes de IA | **Porto Digital** | 2026 |
| 🔐 Introduction to Cybersecurity | **Cisco** | 2026 |
| ⚙️ Engenharia de Prompt | **Senac** | 2026 |
| 🧪 Qualidade de Software | **Senac** | 2026 |
| 🔒 Segurança da Informação | **Enap** | 2026 |
| 💻 HTML, CSS, JavaScript & TypeScript | **Senac + Rocketseat** | 2026 |
| 🚀 CI/CD com GitHub | **Porto Digital** | 2025 |
| ☕ Linguagem Java | **Fundação Bradesco** | 2024 |
| 📊 Power BI | **Fundação Bradesco** | 2024 |

</div>

<br/>

---

## 🌍 Idiomas

<div align="center">

![Português](https://img.shields.io/badge/Português-Nativo-4ade80?style=for-the-badge)
&nbsp;
![Espanhol](https://img.shields.io/badge/Espanhol-Básico%2FIntermediário-facc15?style=for-the-badge)
&nbsp;
![Inglês](https://img.shields.io/badge/English-Basic-60a5fa?style=for-the-badge)

</div>

<br/>

---

## 📬 Vamos construir algo incrível juntos?

<div align="center">

<p>Seja para colaborar em projetos, trocar ideias sobre tecnologia ou apenas bater um papo — estou sempre aberto! 🚀</p>

<a href="mailto:jgoliveiraqm@gmail.com">
  <img src="https://img.shields.io/badge/✉️%20Enviar%20Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>
&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/joaoguilhermeo/">
  <img src="https://img.shields.io/badge/💼%20Conectar%20no%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
&nbsp;&nbsp;
<a href="https://bit.ly/3QejHXT">
  <img src="https://img.shields.io/badge/🎨%20Ver%20Portfólio-FF5722?style=for-the-badge" alt="Portfolio"/>
</a>

<br/><br/>

<sub>Feito com 💜 em Recife, Pernambuco 🌊 · Alimentado por café e curiosidade ☕</sub>

</div>

<!-- FOOTER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=130&section=footer"/>
