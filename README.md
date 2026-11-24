<a id="top"></a>

<div align="center">

# 風 Kaze Launcher Releases

**Canal oficial de distribuição de instaladores e atualizações automáticas do Kaze Launcher para Windows.**  
**Official Windows installer and automatic update distribution channel for Kaze Launcher.**

[![Latest Release](https://img.shields.io/github/v/release/pureza-discord/Kaze-Releases?style=for-the-badge&color=eab308&label=Latest)](https://github.com/pureza-discord/Kaze-Releases/releases/latest)
[![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011%20x64-0ea5e9?style=for-the-badge&logo=windows)](https://github.com/pureza-discord/Kaze-Releases/releases/latest)

[**Português (BR)**](#pt-br) · [**English (US)**](#en-us) · [**Baixar / Download**](https://github.com/pureza-discord/Kaze-Releases/releases/latest)

</div>

---

<a id="pt-br"></a>

## Português (BR)

Este repositório distribui os instaladores oficiais e os manifestos de atualização automática do **Kaze Launcher** para Windows x64.

### Download

**[Baixar a versão mais recente (Windows x64)](https://github.com/pureza-discord/Kaze-Releases/releases/latest)**

Escolha o formato nos **Assets** da última release:

| Arquivo | Formato | Indicação |
| :--- | :--- | :--- |
| `Kaze.Launcher-Setup-0.8.8-x64.exe` | **Instalador (Setup)** | Cria atalhos no Menu Iniciar e na Área de Trabalho e preserva seus dados em cada atualização (recomendado). |
| `Kaze.Launcher-Portable-0.8.8-x64.exe` | **Portátil (Portable)** | Arquivo único para executar direto de qualquer pasta, sem instalação. |

> [!NOTE]
> Como o executável não possui assinatura digital comercial, o Windows SmartScreen pode exibir um alerta na primeira execução. Clique em **Mais informações → Executar assim mesmo**.

### Atualização automática

Você só precisa baixar manualmente uma vez:
- O Kaze Launcher verifica novas versões automaticamente em segundo plano.
- O download é validado via **SHA-512** (`latest.yml`) separando estritamente versões **Setup** e **Portable**.
- Quando uma atualização estiver pronta, basta clicar em **Atualizar · Reiniciar** dentro do launcher — suas contas, sessões e configurações são preservadas.

### O que está incluído no Kaze Launcher

- **Sessões multi-conta isoladas:** grupos e contas ilimitadas com cookies, cache, zoom (`30%–200%`), layouts configuráveis (`Auto`, `3+2`, grade personalizada até `4×4`, abas e foco) e paginação sem recarregar contas.
- **Controle de IP e proxies:** Slot 0 (IP real) + proxies HTTP/HTTPS/SOCKS5 com kill-switch em 2 camadas, proteção WebRTC e contador mensal de banda.
- **Build Planner & Hunt Analyzer (LoL Idle):** 3 motores independentes (**PvE**, **Dungeon** com as 7 Dungeons oficiais e **PvP 1v1**), importação direta do personagem, comparador **Build A vs B** e **Recomendação da Kaze**.
- **Extensões por conta + painel lado a lado:** suporte a `.zip`, `.crx`, pasta *unpacked* e importação de navegadores, já incluindo *Hunt for LoL Idle* (`1zephzrx`) pronta para ativar por conta com atalho lateral **Hunt**.
- **Painel V/L (Votos e Lives):** lives da Twitch via **Chatterino 2** portátil (~20 MB de RAM) e votação em perfil isolado do navegador real (Chrome, Edge, Brave ou Firefox) usando o proxy da conta.
- **Otimização de RAM e desempenho:** perfis de desempenho, hibernação opcional, watchdog e limpeza de RAM manual ou automática a cada **60 minutos** (preservando logins e cookies).
- **Privacidade local:** dados, sessões, backups JSON criptografados e credenciais ficam exclusivamente em `%APPDATA%/Kaze`.

### Créditos

- **Kaze Launcher:** desenvolvido por **taki**.
- **Build Planner & Hunt Analyzer / Hunt for LoL Idle:** créditos a **`1zephzrx`** (Discord: `1zephzrx`).

[↑ Voltar ao topo](#top)

---

<a id="en-us"></a>

## English (US)

This repository distributes official Windows x64 installers and automatic update manifests for **Kaze Launcher**.

### Download

**[Download the latest release (Windows x64)](https://github.com/pureza-discord/Kaze-Releases/releases/latest)**

Choose your preferred format under **Assets** on the latest release page:

| File | Format | Best for |
| :--- | :--- | :--- |
| `Kaze.Launcher-Setup-0.8.8-x64.exe` | **Installer (Setup)** | Creates Start Menu and Desktop shortcuts and preserves your data across updates (recommended). |
| `Kaze.Launcher-Portable-0.8.8-x64.exe` | **Portable** | Single executable that runs from any folder with no installation required. |

> [!NOTE]
> Because this independent build is not signed with a commercial certificate, Windows SmartScreen may show a warning on first launch. Click **More info → Run anyway**.

### Automatic updates

You only need to download manually once:
- Kaze Launcher checks for new releases automatically in the background.
- Downloads are verified via **SHA-512** checksums (`latest.yml`), strictly keeping **Setup** and **Portable** builds separate.
- When an update is ready, click **Update · Restart** inside the app — all accounts, sessions, and settings are kept intact.

### Included features

- **Isolated multi-account sessions:** unlimited groups and accounts with separate cookies, cache, zoom (`30%–200%`), flexible layouts (`Auto`, `3+2`, custom grid up to `4×4`, tabs, and focus), and pagination without reloads.
- **IP control and proxies:** Slot 0 (real IP) + HTTP/HTTPS/SOCKS5 proxies with a 2-layer kill-switch, WebRTC protection, and monthly bandwidth tracking.
- **Build Planner & Hunt Analyzer (LoL Idle):** 3 independent engines (**PvE**, **Dungeon** covering all 7 official Dungeons, and **PvP 1v1**), live character import, **Build A vs B** comparison, and **Kaze Recommendation**.
- **Per-account extensions & docked side panel:** supports `.zip`, `.crx`, unpacked folders, and browser import, bundling *Hunt for LoL Idle* (`1zephzrx`) ready to enable per account with a quick **Hunt** side-by-side toggle.
- **V/L Panel (Votes & Lives):** Twitch chat via portable **Chatterino 2** (~20 MB RAM) and block-free voting in an isolated real browser profile (Chrome, Edge, Brave, or Firefox) using the account's proxy.
- **RAM optimization and performance:** performance profiles, optional hibernation, watchdog, and manual or automatic **60-minute** RAM optimization (preserving logins and cookies).
- **Local privacy:** all sessions, settings, encrypted JSON backups, and credentials stay strictly in `%APPDATA%/Kaze`.

### Credits

- **Kaze Launcher:** created by **taki**.
- **Build Planner & Hunt Analyzer / Hunt for LoL Idle:** credits to **`1zephzrx`** (Discord: `1zephzrx`).

[↑ Back to top](#top)
