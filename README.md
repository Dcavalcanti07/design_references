# Design References

Biblioteca de referências de design system extraídas de sites reais. Cada arquivo descreve um sistema visual completo em formato estruturado, pronto para alimentar geradores de UI, prompts de agentes ou auditorias visuais.

## Conteúdo

- ~1.290 arquivos `.md`, um por marca/produto
- Organização alfabética em subdiretórios (`0-9/`, `a/` … `z/`)
- Cada arquivo segue o mesmo schema, facilitando parsing e comparação

## Schema por arquivo

Cada referência contém:

- **Cabeçalho** — nome, tagline curta, tema (light/dark), parágrafo descritivo do tom visual
- **Tokens — Colors** — tabela com nome, hex, token CSS, papel de cada cor
- **Tokens — Typography** — famílias, pesos, tamanhos, line-height, letter-spacing, features OpenType, type scale
- **Tokens — Spacing & Shapes** — unidade base, densidade, escala de spacing, border radius por elemento, layout
- **Components** — descrição de botões, cards, inputs, navegação, toggles, links
- **Do's and Don'ts** — regras práticas de aplicação
- **Imagery** — tratamento de imagens, ícones, ilustrações
- **Layout** — grid, max-width, ritmo vertical, hierarquia
- **Agent Prompt Guide** — referência rápida de cores + 3-5 prompts de exemplo
- **Similar Brands** — referências adjacentes
- **Quick Start** — bloco CSS Custom Properties + bloco Tailwind v4 prontos para colar

## Casos de uso

- Inspiração e benchmark visual
- Treino/few-shot para LLMs que geram UI
- Auditoria de consistência de design system
- Comparação entre estéticas (editorial, brutalist, glass, mono, etc.)
- Base para criar novo design system híbrido

## Estrutura

```
.
├── CLAUDE.md          # instruções do agente + style reference próprio
├── README.md
├── 0-9/
├── a/
├── b/
└── ...
    └── z/
```

## Convenções

- Nomes de arquivo: minúsculas, sem acento, hífen no lugar de espaço
- Hex em lowercase, tokens em kebab-case prefixados com `--`
- Type scale e spacing em pixels absolutos
- Border radius nomeado por elemento (cards, inputs, buttons, hero, etc.)

## Como usar

1. Localize referência pelo diretório alfabético
2. Copie bloco `Quick Start` direto para projeto (CSS vars ou Tailwind v4)
3. Use seção `Agent Prompt Guide` como contexto para LLM gerar componentes
4. Combine múltiplas referências para criar estética híbrida

## Licença

Referências derivadas de sites públicos para fim de estudo e prototipagem. Não redistribuir como produto. Verificar direitos autorais de fontes e marcas antes de uso comercial.

## Contato

Siga no Instagram: [@adaycavalcanti](https://instagram.com/adaycavalcanti)
