# Simulador de Fluxo — wrapper (GitHub Pages)

Página que embute o Web App do **Simulador de Fluxo** (Alicerce) num
`<iframe credentialless>`, para abrir em qualquer navegador mesmo com 2+ contas
Google logadas (contorna o roteador `/u/N/` do Google). Mesmo padrão do
Gerenciador de Escrituras.

**Link da equipe:** a URL desta página (GitHub Pages) — **nunca** a `/exec` direta.

- **App embutido (`/exec`):** `https://script.google.com/macros/s/AKfycbyAE30P0nfW1tryx1II_jerZbRF96HkireRxaqCQAQRfC_xMMvimcMn_55I4Zg0Ho3PhA/exec`
- `allow="clipboard-write"` no iframe é necessário para o botão **Copiar** funcionar.
- Pré-requisitos no app: deploy anônimo + `doGet` com `XFrameOptionsMode.ALLOWALL`.

Republicar = `git push` nesta pasta (Pages rebuilda sozinho). `credentialless` é
Chromium-only (Chrome/Edge); Firefox/Safari caem no link direto de fallback.
