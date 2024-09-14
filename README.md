# Jogo-da-Velha
Jogo da Velha - bem comentado
O código fornecido é para um jogo da velha (ou tic-tac-toe) implementado em HTML, CSS e JavaScript. Aqui está um resumo em português do funcionamento do código:

### Estrutura HTML:
- Define o layout do jogo com botões para escolher entre dois jogadores ou jogar contra a IA.
- Inclui um grid de 9 caixas para o tabuleiro do jogo.
- Exibe um placar para os jogadores e uma área para mensagens de vitória ou empate.

### CSS:
- Estiliza o layout do jogo, incluindo o grid do tabuleiro e os botões.
- Define o estilo dos símbolos `x` e `o`, bem como a aparência do placar e das mensagens.

### JavaScript:
1. **Inicialização e Eventos**:
   - Define as variáveis para os elementos do jogo e adiciona eventos de clique nas caixas do tabuleiro e nos botões para selecionar o modo de jogo.
   
2. **Lógica do Jogo**:
   - Ao clicar em uma caixa, o símbolo (`x` ou `o`) é adicionado.
   - Alterna entre os jogadores ou executa uma jogada automática se a IA estiver ativada.
   - Verifica se há um vencedor ou se o jogo terminou em empate, e atualiza o placar e exibe a mensagem correspondente.

3. **Funções**:
   - `checkEl()`: Determina qual símbolo (`x` ou `o`) deve ser colocado com base no turno do jogador.
   - `checkWinCondition()`: Verifica todas as condições de vitória ou empate.
   - `declareWinner()`: Atualiza o placar e exibe a mensagem de vitória ou empate.
   - `computerPlay()`: Executa a jogada da IA com uma escolha aleatória de caixa vazia.

### Funcionalidade Principal:
- Permite que dois jogadores humanos joguem um contra o outro ou que um jogador jogue contra a IA.
- Verifica constantemente as condições de vitória ou empate e atualiza o estado do jogo de acordo.
- Limpa o tabuleiro e reinicia os contadores após cada jogo.

Este código cria uma experiência interativa para o jogo da velha, com a opção de competir contra outro jogador ou contra uma IA simples.
