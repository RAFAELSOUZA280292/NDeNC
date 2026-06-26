# Pricetax Fiscal Guardian — ND & NC

Guia técnico interativo sobre Notas de Débito (ND) e Notas de Crédito (NC) na
Reforma Tributária do Consumo (IVA Dual — IBS/CBS). Página única, autossuficiente.

**PRICETAX Consultoria Tributária** · www.pricetax.com.br · (41) 99892-4080

## Conteúdo
- `index.html` — site completo (logo, PDF de apoio e tudo embutido; basta este arquivo)
- `PRICETAX-Guia-de-Apoio-ND-NC.pdf` — material de apoio (também já embutido no HTML)

## Deploy (Vercel)
Projeto estático, sem build. Framework Preset: **Other**. Output: raiz do repositório.
O `index.html` é servido automaticamente na raiz.

## Domínio
Subdomínio sugerido: `ndnc.pricetax.com.br` → CNAME `cname.vercel-dns.com` no Hostinger.

## Atualizações
Editar `index.html`, commitar e dar `git push` — a Vercel publica sozinha.
