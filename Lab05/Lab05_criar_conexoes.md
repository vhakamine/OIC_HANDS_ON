Lab – Criar conta no DocuSign e conexões no OIC;

1. Acessar o link: <https://developers.docusign.com/>
1. Clique em **Create Account**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.001.png)
1. Preencher os dados, dar aceite no termos de uso e clicar em Get Started:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.002.png)

![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.003.png)

1. Conta criada:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.004.png)
1. Agora vamos verificar o e-mail que utilizamos no cadastro:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.005.png)
1. Clicar no link de ativação:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.006.png)
1. Clicar em **Activate**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.007.png)
   
1. Caso voce não tenha sido confrontado com a tela abaixo siga para o **passo 11**. Caso contrario siga ao próximo;

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.008.png)
1. Obtenha o valor do código de autorização do seu e-mail:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.009.png)
  
1. Preencha com o código de autorização:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.010.png)
  
1. Já logado na DocuSign, clique em **Developer Account**:

![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.011.png)

1. Ir em **My Apps & Keys**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.012.png)
   
1. Obtenha e guarde o valor do **API Account ID** para usarmos depois:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.013.png)
   
1. Clique em **Add App and Integration Key**;

2. Preencha o nome do App;

![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.014.png)

5. Clique em **Create App**;

7. Anote a **Integration Key**:
   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.015.png)
   
1. Clique em **Add Secret Key**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.016.png)
   
1. Anote a secret key:

3. Configurar o Redirect URL com a URL do OIC que provisionamos anteriormente. O valor deve seguir o seguinte formato: **https://[HOST do OIC]:443/icsapis/agent/oauth/callback**

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.017.png)
   
1. Clicar em **Save**;

3. Acessar a home do OIC:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.018.png)
   
1. Acessar o manu hamburguer em seguida clicar em **Integration**, e depois clicar em **Connections**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.019.png)
   
1. Clique em **Create;**

3. Busque por **docusign:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.020.png)**
   
1. Clique no logo do **DocuSign** e depois clique no botão **Select**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.020.png)
   
1. Agora preencha os dados conforme a imagem abaixo: 

   **![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.021.png)**
   
   Name: [MYNAME]\_DOCUSIGN (MYNAME entre colchetes substituir pelo seu nome);
   
   Identifier: [MYNAME]\_DOCUSIGN (Será preenchido automáticamente de acordo com o Name);
   
   Keywords: Você pode preencher com keywords para que depois você as utilize para relacionar diferentes objetos dentro da ferramenta, recomendo criar uma nova keyword utilizando seu nome sem espaçamento;
   
   Roles: **Invoke** (Já vem preenchido e não permite modificação);
   
   Description: Descrição da finalidade que a conexão será utilizada. Estou utilizando o valor: Conexão com DocuSign utilizando conta pessoal de Vinicius Hakamine.
   
1. Configurar a conexão com os valores que já haviamos coletado quando criamos a conta do DocuSign:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.022.png)
   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.023.png)
   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.024.png)
 
   **Client ID (Integration Key)**: Valor da Integration Key obtido no passo 17
   
   **Client Secret**: Valor da Secret Key obtido no passo 18
   
   **Scope**: signature extended
   
   **Instance Type**: Sandbox
   
   **Account ID**: Valor do **API Account ID** obtido no passo 13.
   
1. Clicar em **Provide Consent**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.025.png)
   
1. Caso voce sejá confrontado com essa tela, prover usuario e senha do OIC e clicar em ok, caso contrário pular para o próximo passo:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.026.png)
   
1. Conceder o acesso ao OIC:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.027.png)
   
1. Clicar em **Accept**;

3. A mensagem indica que o procedimento foi executado com sucesso:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.028.png)
   
1. Volte ao OIC e clique em **Test** para garantir que a conexão está funcionando adequadamente:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.029.png)
   
1. Clique em **Save**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.029.png)
   
1. Clique na seta do lado esquerdo para voltar:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.030.png)
   
1. Agora nossa conexão está pronta para uso:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.031.png)
   
1. Agora vamos clicar no botão **Create**, para criar uma conexão do tipo REST**;**

3. Busque por **REST**, selecione **REST** e depois clique no botão **Select:**

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.032.png)
   
1. Preencher os dados conforme a orientação abaixo:

   Name: [MYNAME]\_REST (MYNAME entre colchetes substituir pelo seu nome);
   
   Identifier: [MYNAME]\_REST (Será preenchido automáticamente de acordo com o Name);
   
   Keywords: Você pode preencher com keywords para que depois você as utilize para relacionar diferentes objetos dentro da ferramenta, recomendo criar uma nova keyword utilizando seu nome sem espaçamento;
   
   Roles: **Trigger**, (Utilizar o valor);
   
   Description: Descrição da finalidade que a conexão será utilizada. Estou utilizando o valor: Conexão REST para exposição de integrações de Vinicius Hakamine.![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.033.png);
   
1. Configure a Security Policy como **OAuth2.0. or Basic Authentication**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.034.png)
   
1. Clique em **Test:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.035.png)**
   
1. Agora clique em **Save:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.036.png)**
   
1. Clique em Voltar:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.037.png)
   
1. Nossa Conexão **REST** está pronta para uso;

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.038.png)
   
1. Agora vamos criar outra conexão do tipo **REST**, para interagir com as APIs de Processos, clique no botão **Create;**

3. Na barra de pesquisa busque por REST:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.039.png)
   
1. Clique no Icone da Nuvem em seguida clique no botão **Select**:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.040.png)
  
1. Vamos preencher o formulario como na imagem abaixo:

   Name: [MYNAME]\_PROCESS (MYNAME entre colchetes substituir pelo seu nome);
   
   Identifier: [MYNAME]\_PROCESS (Será preenchido automáticamente de acordo com o Name);
   
   Keywords: Você pode preencher com keywords para que depois você as utilize para relacionar diferentes objetos dentro da ferramenta, recomendo criar uma nova keyword utilizando seu nome sem espaçamento;
   
   Role: Invoke
   
   Description: Descrição da finalidade que a conexão será utilizada. Estou utilizando o valor: Conexão REST para interagir com as APIs de Processo de Vinicius Hakamine
   
   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.041.png)
   
1. Clicar em **Create**;

3. Configurar a conexão com as seguintes opções:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.042.png)
   
   Connection Type: REST API Base URL
   
   TLS Version: Não preencher
   
1. Em seguida utilizar as seguintes opções:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.043.png)
   
   Connection URL: https://**[OIC-HOST]**/
   
   Enable two way SSL for outboud connections: No
   
   Security: Basic Authentication
   
   Username: credencial de acesso ao OIC (login);
   
   Password: credencial de acesso ao OIC (senha);
   
1. Clicar no botão **Test** e aguardar a mensagem de sucesso:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.044.png)
   
1. Clicar em **Save** e aguardar a mensagem de sucesso:

   ![](Aspose.Words.e20af730-9293-4ad5-8656-a4c1491a56a0.045.png)
   
1. Fim;

[Clique aqui para voltar a lista de labs](https://github.com/vhakamine/OIC_HANDS_ON/blob/main/README.md)
