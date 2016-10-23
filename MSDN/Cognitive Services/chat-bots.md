# Construindo Chat Bots com a plataforma Microsoft Bot Framework

Olá pessoal, meu nome é Fernando de Oliveira e neste artigo irei abordar o conceito de chat bots e mostrar como podemos desenvolver aplicações inteligentes para interagir com usuários de forma mais natural e humana. 

# O que é um chat bot?

Um chat bot é um programa que interage com usuários, simulando o comportamento humano em uma conversação (reagindo à comandos, perguntas e respostas). 

Um dos grandes desafios de um chat bot é ser um assistente para o usuário com conversações de forma mais natural possível, resolvendo tarefas de forma simples e eficiente.

![](./img/pic-001.png)

Figura 1 – Chat bot no Skype

# O impacto nas redes sociais

O número de usuários ativos em aplicativos de mensagens (como Skype, Slack, WhatsApp e Facebook Messenger) tem ultrapassado o número de usuários de redes sociais.

![](./img/pic-002.png) 

Figura 2 – Aplicativos de mensagem tem ultrapassado redes sociais

Um estudo feito para o Facebook mostrou que a demanda de mensagens privadas tem sido muito superior em relação à demanda de posts. Ou seja, usuários estão usando interagindo mais através do aplicativo de mensagens do que dentro da própria rede social.

![](./img/pic-003.png) 

Figura 3 – Demanda de posts e mensagens privadas

Alta demanda por aplicativos de mensagens e volume de usuários crescendo cada vez mais. Ótimo momento para pensarmos em chat bots focados em negócios, não é mesmo? :)

# Apresentando o LUIS

Luis é um colega meu que está aprendendo inglês. Ele tem aprendido algumas palavras, frases e contextos, além de estar entendendo algumas perguntas e sabendo respondê-las. Quanto mais ele estuda, mais eu percebo sua evolução em uma conversação.

O LUIS que estarei apresentando agora não é o meu colega, mas o que ele faz é muito semelhante. LUIS - [Language Understanding Intelligent Service](https://www.microsoft.com/cognitive-services/en-us/language-understanding-intelligent-service-luis) - é uma API de Machine Learning que permite adicionar processamento de linguagem natural em aplicações, entendendo e interpretando linguagens contextualmente. É uma das APIs presentes no [Microsoft Cognitive Services](https://www.microsoft.com/cognitive-services).

Na página inicial do LUIS, é possível testar o funcionamento do serviço e visualizar a forma com que o resultado é gerado (em formato JSON). 

![](./img/pic-004.png) 

Figura 4 – Demonstração de alguns cenários utilizando o LUIS