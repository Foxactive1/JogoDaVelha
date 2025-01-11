# Jogo da Velha com Inteligência Artificial

Este é um projeto de Jogo da Velha (Tic-Tac-Toe) desenvolvido em Python, utilizando a biblioteca Tkinter para a interface gráfica. O jogo oferece dois níveis de dificuldade para a IA: fácil e difícil.

## Funcionalidades

- **Interface gráfica** intuitiva e responsiva.
- **Dois níveis de dificuldade**:
  - **Fácil**: movimentos aleatórios.
  - **Difícil**: usa o algoritmo **Minimax** para jogadas estratégicas.
- Mensagens de fim de jogo indicando vitória, derrota ou empate.
- Possibilidade de jogar como "X" contra a IA ("O").

## Estrutura do Código

- **check_winner**: verifica se há um vencedor.
- **is_full**: verifica se o tabuleiro está cheio.
- **make_move**: realiza um movimento no tabuleiro.
- **ai_move_easy**: gera movimentos aleatórios.
- **ai_move_hard**: usa o algoritmo Minimax para encontrar o melhor movimento.
- **minimax**: avalia todas as possíveis jogadas para determinar a melhor.
- **Game**: gerencia a lógica principal e interface do jogo.

## Como Executar

1. Certifique-se de ter o Python instalado (versão 3.6 ou superior).
2. Instale a biblioteca Tkinter se ainda não estiver disponível.
3. Salve o código em um arquivo `jogo_da_velha.py`.
4. Execute o arquivo com o comando:
   ```bash
   python jogo_da_velha.py
