Lab08 – Adicionar a integração ao Processo

1. Clicar no menu hamburguer clique em voltar e depois e ir na opção **Processess:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.001.png)**
1. Em seguida clicar em **Process Application** e vamos clicar no nossa aplicação de processo **Application:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.002.png)**
1. Com a nossa aplicação aberta vamos clicar no menu hamburger e acessar a opção **Integrations**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.003.png)
1. Clique em **Link to an Integration** e em seguida clique em **Browser available integrations**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.004.png)
1. Na barra de busca iremos por **ENVIAR\_ASSINATURA\_DIGITAL**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.005.png)
1. Clique na integração **ENVIAR\_ASSINATURA\_DIGITAL** e depois clicar no botão **Create**, teremos nossa integração listada:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.006.png)
1. Clicar no menu hamburguer e selecionar a opção Processes:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.007.png)
1. Clicar no nosso processo **Aplicação e assinatura de contrato**;
1. Clicar no objeto integration do fluxo de processo; 
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.008.png)
1. Clicar no botão de **menu** e depois clicar em **Open Properties**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.009.png)
1. Clicar na lista **Integration** e selecionar o valor **ENVIARASSINATURADIGITAL**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.010.png)
1. Não esquecer de desmarcar a opção **Is Draft**, teremos o seguinte resultado:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.011.png)
1. Voltar ao processo e clicar no menu do objeto Integration e depois na opção Data Association:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.012.png)
1. Do lado esquerdo clique no instanceId e arraste para o campo New Association:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.013.png)
1. Clicar no ícone **fx**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.014.png)
1. Preencher  a expressão com o valor:

|instanceId.substring(6)|
| :- |
1. Em seguida clique no botão **Validate**, para validar se a expressão é válida, aguarde a confirmação:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.015.png)
1. Vá para a parte inferior da página e clique em **Ok**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.016.png)
1. Do lado direito vamos pegar o process\_id e arrastar para o campo correspondente que ficou livre:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.017.png)
1. Feito isso clicar no botão **Apply**:
1. Clicar no botão **Save**;
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.002.png)
1. Clicar em **Publish**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.018.png)
1. Inserir os comentarios da publica em **Comments** e depois Clicar novamente em Publish;
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.019.png)
1. Agora clicar em Active:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.020.png)
1. Clique em **Active new version**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.021.png)
1. Em **Select a snapshot** deixar como **Last Published Version**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.022.png)
1. Clique no botão **Validate**;
1. Clique no botão **Options**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.023.png)
1. Colocar um número de versão estou utilizando **0.5:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.024.png)**
1. Clicar no botão **Activate:**
1. **Aguardar a mensagem de sucesso:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.025.png)**
1. Clicar no botão **Finish;**
1. Clicar no botão **Close**:
   ![](Aspose.Words.ce5bddea-841a-47c5-879d-280ddf381a5e.026.png)
1. Fim;
