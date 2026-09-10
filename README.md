<p align="center">
  <img src="docs/banner.svg" alt="Markdown Templates banner" width="100%" />
</p>

<h1 align="center">markdown-templates</h1>

<p align="center">
  <strong>EN</strong> Markdown templates: ADR, RFC, meeting notes<br/>
  <strong>PT</strong> Templates Markdown: ADR, RFC, notas de reunião
</p>

<p align="center">
  <a href="https://github.com/manansbdb/markdown-templates/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/Markdown-083fa1?style=for-the-badge" alt="Markdown" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Reusable **Markdown templates** for ADRs, RFCs, and meeting notes. | **Templates Markdown** reutilizáveis para ADRs, RFCs e notas de reunião. |
| Copy into `docs/` and fill the sections. | Copia para `docs/` e preenche as secções. |

```mermaid
flowchart LR
  A["📝 Need doc"] --> B["templates/ADR|RFC|MEETING"]
  B --> C["✍️ Fill sections"]
  C --> D["📚 Team docs"]
  style A fill:#14b8a6,stroke:#0f766e,color:#fff
  style B fill:#083fa1,stroke:#1e3a8a,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#6366f1,stroke:#4338ca,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/markdown-templates.git
cd markdown-templates
```

### 2) Copy templates / Copia templates

```bash
mkdir -p /path/to/your-project/docs/templates
cp templates/ADR.md /path/to/your-project/docs/templates/
cp templates/RFC.md /path/to/your-project/docs/templates/
cp templates/MEETING_NOTES.md /path/to/your-project/docs/templates/
```

### Requirements / Requisitos

- `git`
- No runtime dependencies

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/markdown-templates.git
cp markdown-templates/templates/ADR.md ./docs/ADR-0001.md
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `templates/ADR.md` | Architecture Decision Record |
| `templates/RFC.md` | RFC / design proposal |
| `templates/MEETING_NOTES.md` | Meeting notes |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
markdown-templates/
├── docs/banner.svg
├── templates/ADR.md
├── templates/RFC.md
├── templates/MEETING_NOTES.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
