
# 📘 Atividade: Jogo da Forca

## 🎯 Objetivo

Construa o clássico jogo da Forca em Python para praticar manipulação de strings, loops, condicionais e entrada de dados do usuário.

## 📝 Tarefas

### 🛠️ Implementar a mecânica do jogo

#### Descrição
Crie um jogo em que o programa seleciona aleatoriamente uma palavra de uma lista predefinida e o jogador tenta descobri-la, informando uma letra por vez.

#### Requisitos
O programa concluído deve:

- Exibir a palavra oculta com um marcador para cada letra ainda não descoberta, como `_ _ _`.
- Revelar todas as ocorrências de uma letra quando o palpite estiver correto.
- Controlar e exibir o número de tentativas incorretas restantes.
- Encerrar a partida quando o jogador descobrir a palavra ou esgotar as tentativas.
- Exibir uma mensagem indicando vitória ou derrota; em caso de derrota, revelar a palavra.

### 🛠️ Validar os palpites do jogador

#### Descrição
Impeça que palpites repetidos ou entradas que não sejam uma única letra prejudiquem o andamento da partida.

#### Requisitos
O programa concluído deve:

- Aceitar somente um caractere alfabético por palpite.
- Informar quando o jogador digitar uma entrada inválida e solicitar outro palpite.
- Avisar quando uma letra já tiver sido informada, sem descontar uma tentativa.