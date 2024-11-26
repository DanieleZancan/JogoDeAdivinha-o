# Jogo de Adivinhação de Números

Este é um jogo simples de adivinhação de números implementado em Java. O objetivo do jogo é adivinhar um número escolhido aleatoriamente pelo computador dentro de um intervalo definido pelo jogador. O jogo continua até que o jogador acerte o número ou deseje encerrar o jogo.

## Funcionalidades

- **Escolha do Intervalo**: O jogador pode definir o intervalo dentro do qual o número será adivinhado.
- **Geração de Números Aleatórios**: O computador escolhe aleatoriamente um número dentro do intervalo especificado.
- **Entrada do Jogador**: O jogador insere tentativas para adivinhar o número.
- **Dicas**: O jogo fornece dicas sobre se o número secreto é maior ou menor que a tentativa do jogador.
- **Contagem de Tentativas**: O jogo mantém um contador de tentativas até o acerto.
- **Opção de Sair**: O jogador pode encerrar o jogo a qualquer momento.
- **Mensagem de Encerramento**: Ao finalizar o jogo, o número de tentativas realizadas é exibido.

## Como Jogar

1. O jogo pedirá que você insira o valor mínimo e máximo do intervalo de números.
2. O computador irá gerar um número aleatório dentro deste intervalo.
3. Você terá que adivinhar o número, digitando suas tentativas.
4. O jogo fornecerá dicas sobre se o número adivinhado é maior ou menor que o número secreto.
5. O jogo continuará até que você adivinhe corretamente o número ou decida encerrar digitando `-1`.
6. Quando você acertar, o número de tentativas será mostrado.

## Tecnologias Utilizadas

- **Linguagem**: Java
- **Bibliotecas**: 
  - `java.util.Scanner` para capturar entradas do usuário.
  - `java.util.Random` para gerar números aleatórios.
