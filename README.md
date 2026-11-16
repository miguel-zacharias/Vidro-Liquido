# Vidro-Liquido

Experimentos visuais e interativos sobre **Liquid Glass** e **Glassmorphism**. O projeto explora diferentes formas de simular transparência, desfoque, reflexos e refração no navegador, do CSS a shaders WebGL.

## Comece por aqui

Abra [`Testes/Versao-4.html`](./Testes/Versao-4.html) em um navegador moderno. Não é necessário instalar dependências nem executar um processo de build.

A versão 4 usa WebGL para renderizar os efeitos de refração e dispersão. Se WebGL não estiver disponível, a página recorre a um efeito de vidro feito com CSS.

## Experimentos

| Arquivo | O que explorar |
| --- | --- |
| [`Testes/Versao-1.html`](./Testes/Versao-1.html) | Material de vidro em CSS, controles visuais, filtro SVG e lente interativa. |
| [`Testes/Versao-2.html`](./Testes/Versao-2.html) | Mapas de refração e reflexo gerados em canvas, com peças arrastáveis. |
| [`Testes/Versao-3.html`](./Testes/Versao-3.html) | Refinos visuais: aberração RGB, iluminação que acompanha o ponteiro e parallax. |
| [`Testes/Versao-4.html`](./Testes/Versao-4.html) | Renderização WebGL com refração e dispersão em shader, além de fallback em CSS. |

Cada versão é uma página HTML independente. A navegação no próprio experimento permite comparar as diferentes abordagens.

O arquivo [`Testes/Portfolio-Liquid.html`](./Testes/Portfolio-Liquid.html) é um redirecionamento para a versão reorganizada do portfólio. Para abrir os experimentos disponíveis neste repositório, use os arquivos de versão listados acima.

## Estrutura

```text
.
├── README.md
└── Testes/
    ├── Portfolio-Liquid.html
    ├── Versao-1.html
    ├── Versao-2.html
    ├── Versao-3.html
    └── Versao-4.html
```
