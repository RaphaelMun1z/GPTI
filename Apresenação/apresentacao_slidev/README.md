# Apresentação Slidev — Luisburgo/MG

Projeto editável da apresentação do Trabalho Final de Gerência de Projetos de TI.

## Executar

Requisitos: Node.js 22.12+ (recomendável versão LTS).

```bash
npm install
npm run dev
```

Abrir o endereço informado no terminal (normalmente http://localhost:3030).

## Exportar

```bash
npm run export:pdf
npm run export:pptx
```

O PPTX exportado pelo Slidev padrão geralmente usa imagens por slide. A apresentação permanece editável principalmente no arquivo `slides.md` e no `style.css`.

## Editar

- `slides.md`: conteúdo e estrutura dos 23 slides (separados por `---`).
- `style.css`: identidade visual, fontes e espaçamentos.
- No slide de encerramento, preencher nomes dos integrantes.

## Fontes e ressalvas

Informações oficiais: Edital do Pregão 037/2026, Contrato 172/2026, termos de adjudicação/homologação, prova de conceito.

Planejamento acadêmico: T0 = 03/08/2026 (simulado, pois não foi disponibilizada a Autorização de Fornecimento), divisão semanal do cronograma, EAP/RACI e avaliação qualitativa de riscos. A prova de conceito realizada antes da contratação não equivale a aceite da implantação.

A estrutura não depende de imagens externas. As fontes DM Sans e Manrope são carregadas via Google Fonts, com alternativas locais se indisponíveis.
