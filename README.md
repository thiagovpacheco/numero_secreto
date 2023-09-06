# Site "Número Secreto"
Bem-vindo ao "Número Secreto", um jogo divertido onde você tenta adivinhar um número secreto entre um intervalo definido. Neste README, explicaremos como o site funciona sem se aprofundar em linguagens de programação ou pseudocódigos.

## Visão Geral:
O site "Número Secreto" é um jogo interativo baseado na web que desafia você a adivinhar o número secreto escolhido aleatoriamente pelo computador. O jogo segue estas etapas básicas:

### Página Inicial: 
Ao acessar o site, você verá uma página de boas-vindas com um título "Acerte o número secreto" e uma faixa de cores agradável.

### Intervalo de Números: 
Abaixo do título, você encontrará uma mensagem que informa que o número secreto está entre dois valores, representados por "menor-valor" e "maior-valor". Nesse caso, o intervalo é de 1 a 100.

### Faça seu Chute: 
Você é convidado a fazer um chute sobre qual número você acha que é o número secreto.

### Reconhecimento de Voz (Opcional): 
Uma característica única deste jogo é a capacidade de fazer um chute por reconhecimento de voz. Você pode ativar o reconhecimento de voz clicando no botão de microfone. Em seguida, diga em voz alta o número que você deseja chutar.

### Feedback e Validação: 
Após fazer o chute (seja digitando ou usando a voz), você verá uma mensagem indicando o número que você escolheu.

### Verificação de Chute: 
O site verifica se seu chute é válido, ou seja, se é um número entre o intervalo permitido (1 a 100) e se é um número válido (não é um texto ou palavra).

### Feedback do Jogo: 
Com base no seu chute, o site fornecerá feedback. Se você acertar o número secreto, receberá uma mensagem de vitória. Caso contrário, receberá uma dica se o número é maior ou menor do que o número secreto.

### Jogar Novamente: 
Após acertar o número secreto ou receber a mensagem "GAME OVER," você pode reiniciar o jogo clicando no botão "Jogar novamente."

### Componentes Importantes
* HTML: O código HTML define a estrutura da página, incluindo o título, a mensagem de intervalo de números e a área onde o feedback do jogo é exibido.
* CSS: A folha de estilo CSS é responsável pelo layout e aparência visual do site. Define as cores, fontes, tamanhos de texto e formatação geral.
* JavaScript (main.js): Este arquivo JavaScript lida com a geração do número secreto, exibe os valores de intervalo na página e verifica se o chute do jogador está correto ou não.
* JavaScript (reconhecimentoDeVoz.js): Este arquivo JavaScript implementa o reconhecimento de voz para permitir que você faça chutes usando sua voz.
* JavaScript (validacao.js): Este arquivo JavaScript contém as funções que validam se o chute do jogador é válido e fornece feedback com base no chute.

### Como Jogar
1) Visite o site "Número Secreto."
2) Leia a mensagem de intervalo de números para saber entre quais valores o número secreto está.
3) Escolha um número dentro do intervalo permitido.
4) Digite o número no campo de chute ou ative o reconhecimento de voz para fazer o chute.
5) Aguarde o feedback do jogo para saber se você acertou ou não.
6) Tente novamente ou clique em "Jogar novamente" se desejar reiniciar o jogo.
7) Divirta-se jogando o "Número Secreto" e veja quantas tentativas você precisa para acertar o número secreto!
