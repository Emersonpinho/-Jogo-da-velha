
# 🎮 Jogo da Velha

Este é um jogo da velha simples desenvolvido em Python. O jogo permite que dois jogadores joguem em um tabuleiro 3x3, alternando entre os símbolos "X" ❌ e "O" ⭕. O primeiro jogador a alinhar três de seus símbolos na horizontal, vertical ou diagonal vence o jogo. Se o tabuleiro estiver completo e não houver vencedor, o jogo termina em empate.

## Funcionalidades

- **🕹️ Tabuleiro Interativo**: O tabuleiro é impresso após cada jogada, mostrando a disposição atual.
- **✅ Verificação de Vitória**: O jogo verifica automaticamente se um jogador venceu após cada jogada.
- **🚫 Tratamento de Entradas**: O jogo trata entradas inválidas e solicita que o jogador escolha outra posição.
- **🔄 Alternância de Jogadores**: Os jogadores alternam entre "X" e "O".

## Como Jogar

1. 🚀 Execute o código.
2. 📜 O tabuleiro será exibido, mostrando as posições disponíveis.
3. 🙋‍♂️ O jogador é solicitado a inserir um número de 0 a 8 correspondente à posição desejada no tabuleiro.
4. 🔄 O jogo alternará entre os jogadores até que um deles vença ou ocorra um empate.
5. 🎉 Após o término do jogo, uma mensagem informando o resultado será exibida.

## Estrutura do Código

### Classes e Métodos

- **📦 Classe `JogoDaVelha`**: Esta classe contém toda a lógica do jogo.
  - `__init__(self)`: Inicializa o tabuleiro e define o jogador atual.
  - `imprimir_tabuleiro(self)`: Imprime o tabuleiro atual no console.
  - `fazer_jogada(self, posicao)`: Realiza a jogada do jogador atual na posição escolhida.
  - `verificar_vitoria(self)`: Verifica se o jogador atual venceu o jogo.

### Função Principal

- **🔧 `main()`**: Controla o fluxo do jogo, permitindo que os jogadores façam jogadas até que o jogo termine.

## Requisitos

- 🐍 Python 3.x

## Executando o Jogo

Para executar o jogo, siga os seguintes passos:

1. 🛠️ Certifique-se de ter o Python instalado em seu sistema.
2. 📥 Baixe ou clone este repositório.
3. 📂 Abra um terminal ou prompt de comando.
4. 📍 Navegue até o diretório onde o código está localizado.
5. ▶️ Execute o seguinte comando:

   ```bash
   python nome_do_arquivo.py
   ```

   Substitua `nome_do_arquivo.py` pelo nome do arquivo onde o código está salvo.

## Contribuições

🤝 Contribuições são bem-vindas! Se você deseja melhorar o jogo ou adicionar novas funcionalidades, sinta-se à vontade para abrir um *pull request*.

## Licença

📜 Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

📧 Se você tiver alguma dúvida ou sugestão, entre em contato:

- **Nome**: Emerson de Araujo Pinho
- **Email**: printpinho@gmail.com
