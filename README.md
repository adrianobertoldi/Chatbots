
### Trabalho final disciplina Chatbots

Para realização do chatbot, utilizou-se a plataforma Watson da IBM. O bot serve como assistente para uma companhia de seguros fictícia, a Seguradora X.
O fluxo de diálogo do bot é apresentado no arquivo [PDF](/Fluxograma_Chatbot.pdf).

O bot roda localmente em uma página [HTML](/bot.html), que acessa a plataforma online do Watson.

Para integração com webservice, utilizou-se um mock online e gratuito. A ideia é que, caso a aplicação fosse realizada para uma empresa real, esse webservice verificaria os dados do usuário, como número da apólice, nome e até mesmo realizaria agendamento. Contudo, para esse estudo utilizou-se uma abordagem mais simplificada. O webhook pode ser acessado através desse [Link](https://webhook.site/#!/85f0e81c-0aaf-49d3-9798-008572c87063/dc91560b-83ae-4e25-8d54-fa6b0f13b2df/1).

Para a geração das métricas e estatísticas, utilizou-se a ferramenta Analytics do próprio Watson. Como o plano utilizado é o Lite, as conversas são zeradas após 7 dias. Para uma aplicação real, o uso de plataformas pagas são mais indicadas, já que as ferramentas de análise de desempenho são fundamentais para o bom funcionamento e melhorias dos bots.





