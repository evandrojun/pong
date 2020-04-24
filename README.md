# Jogo Pong!

Jogo desevolvido para a matéria de Computação Orientada a Objetos (COO)na USP (Universidade de São Paulo) com o intuito de desolver as habilidades de programação neste paradigma.

#### Descrição do Exércicio de Programação

Você foi recentemente contratado pela ​ EACH Game Dev. Co. ​ para atuar no desenvolvimento de ​ Pong! seu mais novo e aguardado lançamento. Entretanto, poucos dias antes do início do seu trabalho, o único desenvolvedor da equipe deixou o emprego para trabalhar na maior concorrente da empresa. Cabe a você agora a tarefa de finalizar o desenvolvimento do projeto ​Pong. O projeto ​ Pong!​ é escrito Java, e é composto pelas seguintes classes:

- **`Pong`**: classe principal do jogo (contém o método ​ main que gerencia o todo andamento da partida e a  nteração entre os demais elementos).
- **`GameLib/MyFrame/MyKeyAdapter`**: três classes que implementam funcionalidades gráficas (criação de janela em modo gráfico, métodos para desenhos de formas geométricas) e para processar entrada via teclado.
- **`Wall`** : implementa as paredes do jogo.
- **`Ball`** : implementa a bola do jogo.
- **`Player​`**: implementa os jogadores (controláveis) pelo usuários.
- **`Score​`**: implementa o placar do jogo.

Felizmente, algumas destas classes já estavam 100% prontas quando o antigo desenvolvedor deixou a empresa: ​ Pong​ , ​ GameLib, MyFrame, MyKeyAdapter e ​ Wall​. Entretanto, o antigo desenvolvedor apagou, por acidente, os códigos fontes destas classes, e só restaram os arquivos ​ .class​ . Desta forma, não há a possibilidade modificar o comportamento destas classes, de modo que as classes restantes, que deverão ser
implementadas por você, precisam obrigatoriamente “conversar em sintonia” com as classes que já estão prontas.
Para ajudar, um esqueleto de cada uma das classes que precisam ser implementadas (***Ball​***, ***Player*** e ***Score​***) já foi disponibilizado para você. Desta forma, sua tarefa consiste em completar cada um dos arquivos fontes de modo que cada classe implemente o comportamento esperado delas, fazendo com que o jogo passe a funcionar de forma plena.
É extremamente importante que os construtores e as declarações de métodos fornecidos nos esqueletos das classes não sejam alterados, tanto em relação ao nome, quanto em relação aos parâmetros recebidos. Juntamente com os esqueletos das classes, também foi disponibilizado para você a documentação das mesmas em formato ​ javadoc explicando o papel de cada método e parâmetro.

---

## Instruções para jogar

O jogo foi desenvolvido em Java, portanto certifique-se de ter a JDK instalada. Para o desenvolvimento foi utilizada a versão:
> ***java 14.0.1***

---

#### Para rodar o jogo:

- Clone o repositório:

> ``git clone https://github.com/evandrojun/pong.git``

- Navegue ao repositório **``src``** do projeto e garanta que os arquivos **Ball.java**, **Player.java** e **Score.java** estejam compilados rodando:

> ``javac Ball.java Player.java Score.java``

- Em seguida jogue com o comando e siga a instruções do jogo na tela:

> ***java Pong***
