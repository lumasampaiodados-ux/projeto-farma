# 📁 Estrutura do Projeto — Portfólio Luma Sampaio

## 🗂️ Arquivos e suas funções

| Arquivo | Função |
|---|---|
| `index.html` | Página inicial — o usuário escolhe Desktop ou Mobile |
| `portfolio_desktop.html` | Portfólio completo para telas grandes |
| `portfolio_mobile.html` | Portfólio otimizado para smartphones |
| `dashboard-lumafarma.html` | Dashboard farmácia (dados fictícios) |
| `dashboard-financeiro.html` | Dashboard financeiro / meios de pagamento (dados fictícios) |
| `dashboard-seguranca.html` | Dashboard segurança da informação (dados fictícios) |
| `Curriculo_Luma_Sampaio.pdf` | ⚠️ Coloque o PDF do currículo aqui nesta pasta |

## ⚠️ Importante: Botão de Download do Currículo

O botão de download do currículo em PDF **só funciona se o arquivo PDF
estiver na mesma pasta** que os HTMLs, com o nome:

```
Curriculo_Luma_Sampaio.pdf
```

Se o nome do seu arquivo for diferente, edite a linha abaixo
em cada arquivo HTML (index, desktop e mobile):

```html
<a href="Curriculo_Luma_Sampaio.pdf" download="Curriculo_Luma_Sampaio.pdf" ...>
```

## 🔗 Fluxo de Navegação

```
index.html
├── portfolio_desktop.html  ──► dashboard-lumafarma.html
│                           ──► dashboard-financeiro.html
│                           ──► dashboard-seguranca.html
└── portfolio_mobile.html   ──► dashboard-lumafarma.html
                            ──► dashboard-financeiro.html
                            ──► dashboard-seguranca.html
```

Todos os dashboards têm um botão "← Portfólio" que volta para
`portfolio_desktop.html`.

## 🔤 Tipografia

Toda a tipografia usa a fonte **Inter** (Google Fonts),
padronizada em todos os arquivos.

## 📝 Notas

- Não há mais redirecionamento automático no `index.html`
- O usuário escolhe manualmente a versão
- Todos os dashboards exibem aviso de dados fictícios
