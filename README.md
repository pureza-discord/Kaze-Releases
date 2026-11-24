<a id="top"></a>

<div align="center">

<!-- HERO BANNER -->
<a href="https://github.com/pureza-discord/Kaze-Releases/releases/latest">
  <img src="./assets/thumb.png" alt="Kaze Launcher Banner" width="100%" />
</a>

<br />

# 風 Kaze Launcher

<!-- ANIMATED TYPING SUBTITLE -->
<a href="https://github.com/pureza-discord/Kaze-Releases/releases/latest">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=18&duration=3200&pause=1000&color=EAB308&center=true&vCenter=true&width=720&lines=Multi-Account+Isolation+%26+2-Layer+Proxy+Kill-Switch;Build+Planner+%26+Hunt+Analyzer+for+LoL+Idle;Automatic+SHA-512+Verified+Updates+for+Windows+x64;Built+for+Performance%2C+Privacy+%26+Total+Control" alt="Kaze Launcher Highlights" />
</a>

<p>
  <strong>Canal oficial de distribuição e atualizações automáticas para Windows.</strong><br />
  <sub>Official Windows installer &amp; automatic update distribution channel.</sub>
</p>

<!-- DYNAMIC LIVE BADGES -->
<p>
  <a href="https://github.com/pureza-discord/Kaze-Releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/pureza-discord/Kaze-Releases?style=for-the-badge&color=eab308&labelColor=18181b&label=LATEST" alt="Latest Release" />
  </a>
  <a href="https://github.com/pureza-discord/Kaze-Releases/releases">
    <img src="https://img.shields.io/github/downloads/pureza-discord/Kaze-Releases/total?style=for-the-badge&color=22c55e&labelColor=18181b&label=DOWNLOADS" alt="Total Downloads" />
  </a>
  <a href="https://github.com/pureza-discord/Kaze-Releases/releases/latest">
    <img src="https://img.shields.io/github/release-date/pureza-discord/Kaze-Releases?style=for-the-badge&color=a855f7&labelColor=18181b&label=UPDATED" alt="Last Release Date" />
  </a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011%20(x64)-0ea5e9?style=for-the-badge&labelColor=18181b&logo=windows&logoColor=white" alt="Windows 10/11 x64" />
  <img src="https://img.shields.io/badge/Source-Closed%20%2F%20Private-71717a?style=for-the-badge&labelColor=18181b" alt="Closed Source" />
</p>

<br />

<!-- QUICK NAVIGATION BAR -->
<p>
  <a href="#pt-br"><strong>🇧🇷 Português (BR)</strong></a> &nbsp;·&nbsp;
  <a href="#en-us"><strong>🇺🇸 English (US)</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/pureza-discord/Kaze-Releases/releases/latest"><strong>⬇️ Download Latest</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/pureza-discord/Kaze-Releases/releases"><strong>📜 Changelog</strong></a>
</p>

</div>

---

<a id="pt-br"></a>

## 🇧🇷 Português (BR)

Este repositório é o **canal público oficial** de distribuição de binários e manifestos de atualização automática do **Kaze Launcher** para Windows x64. O código-fonte permanece fechado e privado; os executáveis compilados são publicados e verificados aqui.

### ⬇️ Download

<div align="center">

[![Baixar última versão](https://img.shields.io/badge/BAIXAR%20ÚLTIMA%20VERSÃO-Windows%20x64-eab308?style=for-the-badge&logo=windows&logoColor=18181b&labelColor=facc15)](https://github.com/pureza-discord/Kaze-Releases/releases/latest)

</div>

Na aba **Assets** da última release, escolha o formato ideal para o seu uso:

| Artefato | Formato | Recomendação |
| :--- | :---: | :--- |
| `Kaze.Launcher-Setup-<versão>-x64.exe` | **Instalador (Setup)** | Cria atalhos no Menu Iniciar e Área de Trabalho e mantém todos os seus dados intactos nas atualizações **(recomendado)**. |
| `Kaze.Launcher-Portable-<versão>-x64.exe` | **Portátil (Portable)** | Executável único para rodar diretamente de qualquer pasta ou pendrive, sem instalação no sistema. |

> [!NOTE]
> **Aviso do Windows SmartScreen:** por ser uma distribuição independente sem certificado comercial EV, o Windows pode exibir um alerta na primeira execução. Clique em **Mais informações → Executar assim mesmo**.

<details>
<summary><strong>⚙️ Requisitos do Sistema &amp; Armazenamento Local</strong></summary>

<br />

* **Sistema Operacional:** Windows 10 ou Windows 11 (64-bit / x64).
* **Armazenamento de Dados:** 100% local em `%APPDATA%\Kaze` (sessões, perfis, credenciais e backups JSON criptografados).
* **Integração de Votos (opcional):** Chrome, Edge, Brave ou Firefox instalado para abertura de perfil isolado com proxy.

</details>

---

### 🔄 Arquitetura de Atualização Automática

Você só precisa baixar o instalador manualmente **uma única vez**. A partir daí, o próprio launcher cuida de todo o ciclo de atualização com integridade criptográfica:

```mermaid
flowchart LR
    A["Kaze Launcher<br/>(Windows x64)"] -->|"1. Checa latest.yml"| B["GitHub Releases<br/>(Kaze-Releases)"]
    B -->|"2. Canal isolado<br/>Setup vs Portable"| C{"Validação<br/>SHA-512"}
    C -->|"Hash válido"| D["Atualizar · Reiniciar<br/>(Dados preservados)"]
    C -->|"Hash inválido"| E["Download abortado"]
```

* **Verificação em segundo plano:** detecta novas releases automaticamente sem interromper sua sessão.
* **Integridade via SHA-512:** cada binário é validado contra o manifesto `latest.yml`, mantendo builds **Setup** e **Portable** estritamente separadas.
* **Zero perda de dados:** ao clicar em **Atualizar · Reiniciar**, suas contas, proxies, extensões e configurações permanecem intactos.

---

### ✨ Recursos Principais

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🪟 Sessões Multi-Conta Isoladas</h4>
      Grupos e contas ilimitadas com cookies, cache e zoom (<code>30%–200%</code>) totalmente independentes. Layouts flexíveis (<code>Auto</code>, <code>3+2</code>, grade customizada até <code>4×4</code>, abas e modo foco) com paginação sem recarregar contas.
    </td>
    <td width="50%" valign="top">
      <h4>🛡️ Controle de IP &amp; Proxies</h4>
      <strong>Slot 0</strong> (IP real) + suporte a proxies <strong>HTTP / HTTPS / SOCKS5</strong> com <em>kill-switch</em> em 2 camadas, proteção contra vazamento WebRTC e contador mensal de tráfego por proxy.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>⚔️ Build Planner &amp; Hunt Analyzer</h4>
      3 motores independentes para LoL Idle (<strong>PvE</strong>, <strong>Dungeon</strong> com as 7 Dungeons oficiais e <strong>PvP 1v1</strong>), importação direta do personagem, comparador <strong>Build A vs B</strong> e <strong>Recomendação da Kaze</strong>.
    </td>
    <td width="50%"
