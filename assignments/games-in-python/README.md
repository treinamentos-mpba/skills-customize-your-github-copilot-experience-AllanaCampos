
# 📘 Assignment: Hangman Game

## 🎯 Objective

Desenvolva uma versão do jogo da Forca em Python para praticar manipulação de strings, listas, seleção aleatória, entrada de dados, loops e condicionais.

## 📝 Tasks

### 🛠️ Prepare the Secret Word and Game State

#### Descrição
Prepare os dados necessários para iniciar uma partida, selecionando uma palavra secreta e inicializando as variáveis que acompanharão os palpites e as tentativas.

#### Requisitos
O programa concluído deve:

- Selecionar aleatoriamente uma palavra de uma lista predefinida.
- Inicializar uma coleção para registrar as letras adivinhadas, um contador de erros e um limite máximo de tentativas incorretas.
- Exibir a palavra oculta usando um espaço reservado, como `_ _ _`, para cada letra ainda não adivinhada.

### 🛠️ Implement Guesses and End the Game

#### Descrição
Implemente o loop principal para receber palpites, atualizar o progresso e encerrar a partida quando o jogador vencer ou esgotar as tentativas.

#### Requisitos
O programa concluído deve:

- Solicitar palpites de letras e revelar no progresso cada ocorrência de uma letra correta.
- Registrar os palpites incorretos e informar quantas tentativas restam.
- Continuar a partida até a palavra ser adivinhada ou as tentativas incorretas se esgotarem.
- Exibir uma mensagem de vitória ou derrota ao final da partida.