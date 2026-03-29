# Desafio de Percursos - Árvores Binárias

## Descrição

Este é um projeto educacional interativo desenvolvido em HTML, CSS e JavaScript para ajudar estudantes a aprender e praticar os percursos em árvores binárias. O jogo simula desafios de percursos em pré-ordem, em-ordem e pós-ordem, com diferentes níveis de dificuldade, sistema de pontuação e feedback visual em tempo real.

O projeto foi criado como uma ferramenta de treinamento para o vestibular UFMA 2026, focando em conceitos de recursão e estruturas de dados.

## Funcionalidades

- **Modos de Percurso**: Pré-ordem, Em-ordem e Pós-ordem
- **Níveis de Dificuldade**:
  - Fácil: Árvore simples com 3 nós
  - Médio: Árvore com 6 nós
  - Difícil: Árvore complexa com 11 nós
  - Super Difícil: Árvore muito complexa com 10 nós
- **Sistema de Pontuação**: Pontos por desafio concluído (100-500 pts dependendo da dificuldade)
- **Progresso Global**: Acompanhamento de 12 desafios totais
- **Feedback Visual**: 
  - Nós corretos ficam verdes com badge de ordem
  - Nós incorretos piscam em vermelho com mensagem de erro
  - Tela de vitória com confetes no final
- **Controles**: Desfazer último movimento, limpar exercício, reiniciar tudo

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página
- **CSS3**: Estilos com Tailwind CSS (via CDN) e customizações
- **JavaScript (ES6+)**: Lógica do jogo, manipulação DOM e renderização SVG
- **SVG**: Renderização visual das árvores binárias

## Como Usar

1. **Clone ou baixe** o repositório
2. **Abra o arquivo `index.html`** em qualquer navegador moderno
3. **Selecione o nível de dificuldade** no seletor superior
4. **Escolha o modo de percurso** (Pré-Ordem, Em-Ordem, Pós-Ordem)
5. **Clique nos nós da árvore** na ordem correta do percurso selecionado
6. **Use os botões laterais** para desfazer ou limpar se necessário
7. **Complete todos os 12 desafios** para ver a tela final de conclusão

## Estrutura do Projeto

```
/
├── index.html          # Arquivo principal com todo o código
└── README.md           # Este arquivo
```

## Requisitos

- Navegador web moderno com suporte a ES6+ e SVG
- Conexão à internet (para carregar Tailwind CSS via CDN)

## Contribuição

Este projeto foi desenvolvido como uma ferramenta educacional específica. Sugestões de melhorias são bem-vindas através de issues ou pull requests.

## Licença

Este projeto é de uso educacional e não possui licença específica definida.