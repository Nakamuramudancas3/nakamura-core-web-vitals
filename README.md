# 📊 Lighthouse & Core Web Vitals – Nakamura Mudanças

Documentação técnica oficial de auditoria **Google Lighthouse / PageSpeed Insights**, focada em **Core Web Vitals**, aplicada ao site **[https://nakamuramudancas.com.br](https://nakamuramudancas.com.br)**.

Esta documentação foi criada para fins de **SEO técnico, performance web, compliance com Google**, transparência técnica e histórico de otimizações.

---

## 🎯 Objetivos

* Garantir conformidade com **Core Web Vitals**
* Documentar auditorias Lighthouse (Mobile e Desktop)
* Registrar melhorias de performance
* Criar histórico técnico auditável
* Servir como material profissional (clientes, SEO, DevOps)

---

## 🧩 Estrutura do Repositório

```
lighthouse-core-web-vitals
│
├── README.md
│
├── reports/
│   ├── mobile.html
│   ├── desktop.html
│   ├── mobile.json
│   └── desktop.json
│
├── docs/
│   ├── core-web-vitals.md
│   ├── lighthouse-metrics.md
│   └── metodologia.md
│
├── before-after/
│   ├── before.md
│   └── after.md
│
└── checklist/
    └── performance-checklist.md
```

---

## 🌐 Site Avaliado

* **URL:** [https://nakamuramudancas.com.br](https://nakamuramudancas.com.br)
* **Servidor:** LiteSpeed
* **CMS:** WordPress
* **Construtor:** Elementor

---

## 📈 Métricas Monitoradas

* **LCP** – Largest Contentful Paint
* **CLS** – Cumulative Layout Shift
* **INP** – Interaction to Next Paint
* **FCP** – First Contentful Paint
* **TTFB** – Time to First Byte

---

## 📄 docs/core-web-vitals.md

### Largest Contentful Paint (LCP)

Tempo de carregamento do maior elemento visível da página.

* ✅ Bom: até 2.5s
* ⚠️ Médio: até 4.0s
* ❌ Ruim: acima de 4.0s

Principais otimizações:

* Preload de imagens críticas
* CSS crítico
* Otimização de servidor (TTFB)

---

### Cumulative Layout Shift (CLS)

Mede a estabilidade visual da página.

* ✅ Bom: ≤ 0.1
* ❌ Ruim: > 0.25

Principais otimizações:

* Definição de width/height em imagens
* Evitar inserções dinâmicas sem espaço reservado

---

### Interaction to Next Paint (INP)

Tempo de resposta às interações do usuário.

* ✅ Bom: ≤ 200ms
* ⚠️ Médio: ≤ 500ms
* ❌ Ruim: > 500ms

Otimizações:

* Redução de JavaScript
* Defer / Async
* Remoção de scripts desnecessários

---

## 📄 docs/lighthouse-metrics.md

### Métricas Lighthouse

* Performance
* SEO
* Best Practices
* Accessibility

Ferramenta utilizada:

* Google Chrome DevTools
* Lighthouse CLI

---

## 📄 docs/metodologia.md

### Metodologia de Auditoria

1. Execução Lighthouse em modo anônimo
2. Cache limpo
3. Análise Mobile e Desktop
4. Coleta de HTML e JSON
5. Comparação antes/depois
6. Registro de melhorias

---

## 📄 before-after/before.md

### Situação Inicial

* CSS não crítico bloqueando renderização
* Fontes sem preload
* CLS elevado
* JavaScript excessivo

---

## 📄 before-after/after.md

### Após Otimizações

* CSS crítico inline
* Fetchpriority configurado
* Font-display: swap
* Imagens WebP + Lazy Load
* CLS controlado

---

## 📄 checklist/performance-checklist.md

### Checklist Técnico

* [x] CSS crítico
* [x] JS com defer
* [x] Font-display: swap
* [x] Preload de fontes
* [x] Lazy loading
* [x] WebP
* [x] Cache LiteSpeed
* [x] Fetchpriority configurado

---

## 🚀 Publicação (GitHub Pages)

1. Settings → Pages
2. Branch: main
3. Pasta: /docs

---

## 🧠 Observação Final

Esta documentação segue as **diretrizes oficiais do Google** para Core Web Vitals e PageSpeed Insights, sendo adequada para auditorias técnicas, SEO avançado e comprovação profissional.

---

📌 **Responsável Técnico:** Nakamura Mudanças
