# 🌳 Desafio Divertido: Percursos em Árvores Binárias! 🎮

## Sobre o Projeto

Um simulador gamificado para aprender percursos em árvores binárias (pré-ordem, em-ordem e pós-ordem) de forma interativa. Criado para ajudar na preparação para o concurso da UFMA, focando em conceitos de recursão e estruturas de dados.

## O Que Tem de Legal Aqui? ✨

- **🎯 Modos de Percurso**: Pré-ordem, Em-ordem e Pós-ordem – clique na ordem certa e veja a magia acontecer!
- **📈 Níveis de Dificuldade** (do fácil ao "ufa, que desafio!"):
  - 🟢 **Fácil**: Árvore simples com 3 nós – perfeito para começar
  - 🟡 **Médio**: 6 nós – já começa a ficar interessante
  - 🟠 **Difícil**: 11 nós complexos, com curvas e reviravoltas
  - 🔴 **Super Difícil**: 10 nós profundos e cheios de surpresas
- **🏆 Sistema de Pontuação**: Ganhe pontos por cada desafio (100-500 pts)! Só na primeira vez que completa, hein? 😉
- **📊 Progresso Global**: Acompanhe seus 12 desafios totais – vai virar mestre nisso!
- **🎨 Feedback Visual Incrível**:
  - Nós certos ficam verdes com um badge numerado 🏅
  - Errou? Pisca vermelho e mostra uma dica amigável 💡
  - Vitória? Confetes voando! 🎉
- **🔄 Controles**: Desfazer último clique, limpar tudo ou reiniciar do zero

## O Que Tem de Legal Aqui? ✨

- **🎯 Modos de Percurso**: Pré-ordem, Em-ordem e Pós-ordem – clique na ordem certa e veja a magia acontecer!
- **📈 Níveis de Dificuldade** (do fácil ao "ufa, que desafio!"):
  - 🟢 **Fácil**: Árvore simples com 3 nós – perfeito para começar
  - 🟡 **Médio**: 6 nós – já começa a ficar interessante
  - 🟠 **Difícil**: 11 nós complexos, com curvas e reviravoltas
  - 🔴 **Super Difícil**: 10 nós profundos e cheios de surpresas
- **🏆 Sistema de Pontuação**: Ganhe pontos por cada desafio (100-500 pts)! Só na primeira vez que completa, hein? 😉
- **📊 Progresso Global**: Acompanhe seus 12 desafios totais – vai virar mestre nisso!
- **🎨 Feedback Visual Incrível**:
  - Nós certos ficam verdes com um badge numerado 🏅
  - Errou? Pisca vermelho e mostra uma dica amigável 💡
  - Vitória? Confetes voando! 🎉
- **🔄 Controles**: Desfazer último clique, limpar tudo ou reiniciar do zero

## Tecnologias Que Usei 🛠️

- **HTML5**: A base sólida da página
- **CSS3**: Estilos lindos com Tailwind CSS (via CDN) + toques personalizados
- **JavaScript (ES6+)**: Toda a lógica do jogo, manipulação da tela e renderização
- **SVG**: Para desenhar aquelas árvores bonitas e interativas

## Como Jogar? Vamos Lá! 🚀

1. **📥 Baixe ou clone** o repositório aqui no GitHub
2. **🌐 Abra o `index.html`** no seu navegador favorito
3. **🎚️ Escolha a dificuldade** no seletor lá em cima (comece fácil se for novato!)
4. **📋 Selecione o modo** (Pré-Ordem, Em-Orderm, Pós-Ordem) nas abas estilosas
5. **👆 Clique nos nós da árvore** na ordem correta – use o painel lateral como guia
6. **🔙 Precisa de ajuda?** Use "Desfazer" ou "Limpar" se errar
7. **🎊 Complete todos os 12 desafios** e veja a festa final com confetes!

## Estrutura do Projeto 📁

```
/
├── index.html    # Tudo aqui: HTML, CSS e JS juntos! 🤝
└── README.md     # Este arquivo que você tá lendo 😄
```

## O Que Você Precisa? 💻

- Um navegador moderno (Chrome, Firefox, Edge...) com suporte a ES6 e SVG
- Internet para carregar o Tailwind CSS (mas é rapidinho!)

## Quer Contribuir? 🤝

Sugestões são bem-vindas! Abra uma issue ou mande um PR se tiver ideias para melhorar.

## Prompt de Criação 🤖

Curioso sobre como isso tudo começou? Aqui vai o prompt original que usei para criar o projeto (quem sabe inspire você a fazer algo similar?):

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

## Licença 📜

Projeto de uso educacional – sinta-se à vontade para usar e compartilhar!