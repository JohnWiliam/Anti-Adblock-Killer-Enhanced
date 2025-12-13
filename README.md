# Anti-Adblock Killer Enhanced - Elite Edition 🛡️

[![Install Script](https://img.shields.io/badge/INSTALL_SCRIPT-333333?style=for-the-badge&logo=tampermonkey&logoColor=white&labelColor=2cbe4e)](https://github.com/JohnWiliam/Anti-Adblock-Killer-Enhanced/raw/master/Anti-Adblock.user.js)
[![License](https://img.shields.io/badge/LICENSE-MIT-blue?style=for-the-badge)](LICENSE)
[![Version](https://img.shields.io/badge/VERSION-1.0.1-orange?style=for-the-badge)](https://github.com/JohnWiliam/Anti-Adblock-Killer-Enhanced/raw/master/Anti-Adblock.user.js)

---

## 🇺🇸 English

### Definitive Anti-Adblock Bypass
**Anti-Adblock Killer Enhanced** is a cutting-edge UserScript designed to bypass complex anti-adblock detection systems. Powered by AI heuristics and adaptive stealth technology, it neutralizes detection scripts and removes annoying overlays while keeping your browsing experience smooth.

### 🚀 Key Features
*   **🤖 AI-Powered Detection:** Uses heuristic analysis to identify and remove adblock overlays even if they use randomized class names.
*   **🛡️ Stealth Mode:** Neutralizes known detection APIs (like `BlockAdBlock`, `adsbygoogle`) by mocking their behavior.
*   **🔧 Auto-Healing:** Monitors your browsing session and automatically restores scrolling if a site tries to lock it.
*   **⚡ Performance Optimized:** Dynamically adjusts its scanning rate to minimize CPU usage.
*   **🔄 Auto-Update:** Fetches the latest blocking rules directly from the repository.

### 📦 Installation
1.  Install a UserScript manager extension:
    *   **Tampermonkey** (Recommended)
    *   **Violentmonkey**
2.  **[Click Here to Install](https://github.com/JohnWiliam/Anti-Adblock-Killer-Enhanced/raw/master/Anti-Adblock.user.js)** or click the big green button above.
3.  Confirm the installation in the tab that opens.

### ⌨️ Hotkeys
| Key Combo | Action |
| :--- | :--- |
| `Ctrl + F9` | **Toggle Protection** (Enable/Disable) |
| `Ctrl + F10` | **Force Cleanup** (Manually remove overlays) |
| `Ctrl + F11` | **Emergency Disable** (Reload page without script) |

### 🛠️ How it Works
This script works in layers:
1.  **Pre-Interception:** Before the page loads, it injects fake "ad" variables (like `adsbygoogle`) to trick detectors into thinking ads are loading fine.
2.  **DOM Monitoring:** It watches for changes in the page structure. If an element looks like an overlay (based on keywords or behavior), it gets zapped ⚡.
3.  **Self-Defense:** If a site tries to detect the script itself by checking modified functions, the script hides its tracks using `toString()` overrides.

---

## 🇧🇷 Português

### Bypass Definitivo de Anti-Adblock
**Anti-Adblock Killer Enhanced** é um UserScript de última geração projetado para burlar sistemas complexos de detecção de adblock. Impulsionado por heurísticas de IA e tecnologia furtiva adaptativa, ele neutraliza scripts de detecção e remove overlays irritantes, mantendo sua navegação fluida.

### 🚀 Funcionalidades Principais
*   **🤖 Detecção por IA:** Usa análise heurística para identificar e remover overlays de adblock mesmo que usem nomes de classes aleatórios.
*   **🛡️ Modo Furtivo:** Neutraliza APIs de detecção conhecidas (como `BlockAdBlock`, `adsbygoogle`) simulando seu comportamento.
*   **🔧 Auto-Cura:** Monitora sua sessão de navegação e restaura automaticamente a rolagem se um site tentar bloqueá-la.
*   **⚡ Otimização de Performance:** Ajusta dinamicamente sua taxa de verificação para minimizar o uso da CPU.
*   **🔄 Auto-Atualização:** Busca as regras de bloqueio mais recentes diretamente do repositório.

### 📦 Instalação
1.  Instale uma extensão gerenciadora de UserScripts:
    *   **Tampermonkey** (Recomendado)
    *   **Violentmonkey**
2.  **[Clique Aqui para Instalar](https://github.com/JohnWiliam/Anti-Adblock-Killer-Enhanced/raw/master/Anti-Adblock.user.js)** ou clique no botão verde no topo da página.
3.  Confirme a instalação na aba que abrir.

### ⌨️ Teclas de Atalho
| Combinação | Ação |
| :--- | :--- |
| `Ctrl + F9` | **Alternar Proteção** (Ativar/Desativar) |
| `Ctrl + F10` | **Limpeza Forçada** (Remover overlays manualmente) |
| `Ctrl + F11` | **Desativação de Emergência** (Recarregar sem o script) |

### 🛠️ Como Funciona
Este script atua em camadas:
1.  **Pré-Interceptação:** Antes da página carregar, ele injeta variáveis de "anúncio" falsas (como `adsbygoogle`) para enganar os detectores, fazendo-os pensar que os anúncios estão carregando normalmente.
2.  **Monitoramento do DOM:** Ele observa mudanças na estrutura da página. Se um elemento parecer um overlay (baseado em palavras-chave ou comportamento), ele é eliminado ⚡.
3.  **Auto-Defesa:** Se um site tentar detectar o próprio script verificando funções modificadas, o script esconde seus rastros usando sobrescritas de `toString()`.

---

<div align="center">
  <i>Open Source Project • Free for Reuse • Powered by Community & AI</i>
</div>
