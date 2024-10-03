# Duelo da Forca

Este é um jogo multiplayer simples de adivinhação de palavras, no estilo "Forca", onde dois jogadores competem entre si. O objetivo é adivinhar a palavra proposta pelo oponente, e quem acertar mais palavras ganha pontos.

## Tecnologias Utilizadas

- **HTML5**: Para a estruturação das páginas.
- **CSS3**: Para o design e estilo personalizado.
- **JavaScript**: Para a lógica do jogo e interação entre os jogadores.
- **Bootstrap 3.4.0**: Para o layout responsivo e design padrão.
- **jQuery 3.4.1**: Para facilitar a manipulação do DOM e a execução de requisições.

## Funcionalidades

1. **Login de Jogadores**:
   - Dois jogadores podem entrar com seus nomes para iniciar o jogo.
   
2. **Rodadas de Jogo**:
   - O jogador 1 propõe uma palavra e o jogador 2 tenta adivinhar.
   - O jogo troca de turno automaticamente, com pontuação sendo atualizada em tempo real.

3. **Lógica de Substituição de Letras**:
   - Durante o turno de perguntas, algumas letras da palavra são substituídas por "_", tornando o desafio mais interessante.

4. **Pontuação**:
   - Pontuação é acumulada a cada palavra corretamente adivinhada.

## Como Jogar

1. Clone este repositório.
    ```bash
    git clone https://github.com/usuario/duelo-da-forca.git
    ```
2. Abra o arquivo `index.html` em seu navegador.
3. Insira os nomes dos dois jogadores e clique no botão "Entrar".
4. O jogador 1 insere uma palavra, que será parcialmente ocultada para o jogador 2 adivinhar.
5. O jogo alterna entre os jogadores a cada rodada.

## Estrutura do Projeto

- `index.html`: Página de login inicial onde os jogadores inserem seus nomes.
- `game_page.html`: Página principal do jogo onde a lógica de adivinhação acontece.
- `game.css`: Arquivo de estilo para personalizar o visual do jogo.
- `game_login.js`: Script responsável por gerenciar o login dos jogadores e armazenamento de nomes.
- `game_page.js`: Script com a lógica do jogo, manipulação da pontuação e alternância de turnos.

## Requisitos do Sistema

- Navegador atualizado com suporte a HTML5, CSS3 e JavaScript.
- Conexão com a internet para carregar as dependências externas do Bootstrap e jQuery.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues para sugestões de melhorias.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

