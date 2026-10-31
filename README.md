# SEED Labs — XSS Attack Lab

Relatório e documentação do laboratório de **Cross-Site Scripting (XSS)** do [SEED Labs](https://seedsecuritylabs.org), desenvolvido no curso de **Cibersegurança** da Universidade Federal de Uberlândia (UFU).

## Sobre o laboratório

O laboratório utiliza o **Elgg For SEED Labs v3.3.3**, uma rede social open-source com as proteções contra XSS intencionalmente desativadas, provisionada via Docker Compose.

## Tasks executadas

| Task | Descrição | Resultado |
|------|-----------|-----------|
| Task 1 | XSS Armazenado Básico | ✅ Payload executado no perfil |
| Task 2 | Leitura de Cookie via XSS | ✅ Cookie de sessão lido via `document.cookie` |
| Task 3 | Exfiltração de Cookie (Session Hijacking) | ✅ Cookie exfiltrado via netcat |
| Task 4 | Ação automática via XSS (Add Friend) | ✅ Ação forçada contornando tokens CSRF |
| Task 5 | Worm auto-propagável | ✅ Perfil da vítima infectado automaticamente |
| Task 6 | Análise de contramedidas | ✅ HTMLawed ausente, sem HttpOnly, sem CSP |

## Ambiente

- Ubuntu 24
- Docker Compose v5.5.1
- Navegador Brave

## Arquivo

- `relatorio_xss_2026.pdf` — Relatório completo em normas ABNT com evidências (capturas de tela)

## Aviso

Este laboratório foi executado em ambiente isolado (containers Docker locais), sem acesso a sistemas reais ou de terceiros. O conteúdo é exclusivamente para fins educacionais.
