Lab06 - Criar Integração

1. Logar no OIC acessar o menu hamburger e clicar na opção **Integration**:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.001.png)
   
1. Clicar no menu hamburger em seguida clicar em **Integrations**:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.002.png)
   
1. Clicar no botão **Create**;
1. Clicar em **App Drive Orchestration** e no botão **Select**:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.003.png)
   
1. Preencher conforme a orientação abaixo em seguida clicar no botão **Create**:

   Name: [MYNAME]\_ASSINATURA\_DIGITAL (MYNAME entre colchetes substituir pelo seu nome);
   
   Identifier: [MYNAME] \_ASSINATURA\_DIGITAL (Será preenchido automáticamente de acordo com o Name);
   
   Version: 01.00.0000 (Preenchido automáticamente);
   
   Documentation URL: Não preencher. É possível apontar uma documentação existente;
   
   Keywords: Você pode preencher com keywords para que depois você as utilize para relacionar, estou utilizando o valor com o meu nome;
   
   Package: Não preencher, é possível montar pacotes para cada uma de suas sprints;
   
   Description: Descrição do desenvolvimento, estou usando o valor: Enviar contrato para assinatura digital.
   
   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.004.png)
   
1. Clicar no botão **+** conforme a imagem abaixo:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.005.png)
   
1. Buscar e clicar na conexão **[MYNAME]\_REST** que criamos nos laboratórios anteriores;
1. Preencher as informações conforme a imagem abaixo e clique em **Next**:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.006.png)
   
1. Preencher como na imagem abaixo e clicar em **Next**:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.006.png)
   
1. Agora vamos configurar nossa entrada de dados marcando as opções **Select the request payload format** e **What is the media-type or request body? (Content-Type Header)** com o valor **JSON Sample e JSON** respectivamente:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.007.png)
   
1. Clicar no **<<<< inline >>>>** para colocar um exemplo de entrada:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.008.png)
   
   Utilizar o valor no quadro abaixo e clicar em **Ok:**

|<p>{</p><p>"process\_id":"19191919"</p><p>}</p>|
| :- |
1. Clicar em **Next**;

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.009.png)
   
1. Agora vamos configurar a modelo de resposta que nossa API irá retornar;
1. Assim como fizemos no anterior iremos preencher como JSON Sample e JSON os campos **Select the request payload format** e **What is the media-type or request body? (Content-Type Header)**:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.006.png)
   
1. Clicar no **<<<< inline >>>>** para colcoar um exemplo de entrada;
1. Utilizar o valor no quadro abaixo e clicar em **Ok:**

|<p>{</p><p>"process\_id":"19191919"</p><p>}</p>|
| :- |

1. Clicar em **Next**;
1. Clicar em Done para concluir:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.010.png)
   
1. Neste ponto definimos as assinatura da nossa API e retorno da nossa API:

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.011.png)
   
1. Clicar no ícone **menu** na extremidade direita;

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.012.png)
   
1. Clicar em Tracking;
1. Agora selecione **process\_id** e clique no icone seta, para inserirmos o process\_id como um tracking field:![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.013.png)
1. Clicar em **Save**;

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.014.png)
   
1. Feito isso a notificação em vermelho que aparecia como um erro em nossa integração irá sumir (caso não tenha visto o screenshot do passo 20 mostra isso):

   ![](Aspose.Words.a8a95ad0-07a9-4484-8e59-dd73e4632464.015.png)
   
1. Fim


[Clique aqui para voltar a lista de labs](https://github.com/vhakamine/OIC_HANDS_ON/blob/main/README.md)
