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

## Prompt de Criação

Para reproduzir ou entender a origem deste projeto, aqui está o prompt original usado para sua criação:

```
Atue como um Engenheiro de Software Sênior especializado em Front-end e Educação Interativa. 
Preciso que você crie um "Simulador Gamificado de Percursos em Árvores Binárias" (Pre-order, In-order, Post-order) para me ajudar a estudar para concursos de TI.

A aplicação deve ser construída em um ÚNICO arquivo HTML, contendo CSS (via Tailwind CSS CDN) e JavaScript puro (Vanilla JS).

Aqui estão os requisitos detalhados da aplicação:

1. ESTÉTICA E LAYOUT (Clean UI)
- Tema escuro sofisticado (fundo slate-950, painéis slate-900, bordas slate-800). Textos em tons de slate-200 a slate-400.
- Topbar bem fina no topo da tela com: "TREINO UFMA 2026" à esquerda, e à direita "Desafios Concluídos: 0 / 12" e "Pontuação Total: 0 pts".
- Header principal com o título "Percursos em Árvore", um `<select>` para Dificuldade (Fácil, Médio, Difícil, Super Difícil) e botões estilo "abas" para os modos (Pré-Ordem, Em-Ordem, Pós-Ordem).
- O corpo principal deve ser dividido em dois: 
  - Esquerda/Centro (70% do espaço): Um canvas usando `<svg>` para desenhar a árvore.
  - Direita (30% do espaço): Um painel lateral ("aside") mostrando a sequência de nós clicados pelo usuário, botão de "Desfazer" e "Recomeçar".

2. DADOS E NÍVEIS DE DIFICULDADE
- Crie 4 objetos JavaScript representando árvores binárias fixas:
  - Fácil: 3 nós (raiz e dois filhos).
  - Médio: 6 nós.
  - Difícil: ~12 nós, assimétrica, com zig-zags (nós que só têm o filho da direita ou só da esquerda).
  - Super Difícil: ~16 nós, profunda e complexa.
- Cada nível tem um viewBox e um espaçamento vertical/horizontal ajustado no SVG para não sobrepor os nós e ficar centralizado.

3. LÓGICA DO JOGO (Feedback Imediato)
- Quando o usuário altera a dificuldade ou o modo, o sistema calcula internamente o array com a resposta correta usando algoritmos de recursão reais (Pre, In, Post).
- O SVG desenha a árvore com linhas (arestas) e círculos (nós). O `<text>` com o valor do nó fica dentro do círculo.
- O clique no nó deve ter uma hitbox transparente e maior que o círculo visual para facilitar o toque no celular/mouse.
- Validação imediata:
  - Se o usuário clicar no nó correto (o próximo da sequência): o nó fica verde, ganha um pequeno "badge" numerado indicando sua posição na ordem, e entra na lista do painel lateral.
  - Se clicar no nó errado: exibe um alerta vermelho temporário flutuante no topo do SVG ("Ops! Era esperado o nó X") e o nó clicado pisca em vermelho. A jogada errada não é registrada.

4. SISTEMA DE PROGRESSÃO E PONTUAÇÃO
- Há 12 desafios únicos no total (4 árvores x 3 modos).
- O usuário ganha pontos apenas na PRIMEIRA vez que conclui um desafio específico.
- Pontuação por dificuldade: Fácil=100, Médio=200, Difícil=300, Super=500.
- Ao concluir a sequência de um desafio: Mostra um modal (overlay sobre a árvore) de "Vitória", informando "+ X pontos" e um botão para continuar.
- GRAND FINALE: Quando o usuário atingir 12/12 desafios, bloqueie a tela com um modal épico (com animação de confetti usando CSS keyframes no fundo), parabenize-o ("Treinamento Concluído") e exiba a pontuação final (máximo 3300). Deve haver um botão para "Reiniciar Tudo" que zera os pontos e limpa o progresso.

O código deve ser responsivo, limpo, bem indentado e funcionar perfeitamente apenas salvando em um arquivo `index.html` e abrindo no navegador.
```

## Licença

Este projeto é de uso educacional e não possui licença específica definida.