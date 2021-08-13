Lab 04 – Criar e associar atividades no processo;

1. Em Processes, acesse a funcionalidade **Process Applications**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.001.png)
1. Abrir **Application**, a aplicação que estamos trabalhando;
1. Vamos abrir o processo **Aprovação e assinatura de contrato**;
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.002.png)
1. Vamos criar uma nova **Lane** (Raia), para que o processo roteie a atividade para o jurídico aprovar o contrato, clique no Ícone **+** para criar a nova raia:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.003.png)
1. O nome da Lane ficou como **Proccess Owner:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.004.png)**
1. Vamos modificá-la para **Juridico**. Clicar em cima da **Lane** para que fique azul e clicar no ícone do **Lápis**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.005.png)
1. Agora vamos clicar no ícone **+** para criar uma nova Role na ferramenta que irá representar o departamento **Jurídico:**
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.006.png)
1. Preencher com **Juridico** e clicar em **Ok**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.007.png)
1. Agora vamos clicar no botão com a seta para baixo acima do ícone com **?** ao lado direito:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.008.png)
1. Vamos arrastar um objeto **Approve** do tipo **Human**. Isso vai fazer com que nosso processo seja aprovado pelo departamento Juridico da nossa companhia:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.009.png)
1. O objeto deve ficar posicionado entre os objetos de **Start** e **End** do projeto, conforme a imagem abaixo:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.010.png)
1. Em seguida arraste o objeto **User task**, para a **Lane (Juridico)**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.011.png)
1. Clicar no objeto **User task**, depois clicar no ícone de **menu** abaixo do ícone de **seta,** clicar em **Open Properties:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.012.png)**
1. Vamos clicar no Ícone **Lupa** para selecionar o formulário que já haviamos criado anteriormente para esse processo. Selecionar e clicar em **Ok**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.013.png)
1. Em **Action,** vamos renomear as ações de **APPROVE,REJECT** para **Aprovar,Rejeitar**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.014.png)
1. Agora vamos customizar o Title, Task Summary, Due Date, Priority, Skip Approval On:

   **Title**: Titulo da Atividade de aprovação, estou utilizando: **"Validar contrato com o Forcenedor: " + ContratoFormulario.fornecedor + " no valor de " + ContratoFormulario.valor** , no qual o **nome do fornecedor** e **valor** estamos pegando o valor dinamicamente do formulário

   **Task Summary**: Resumo da atividade, normalmente é descrito o que deve ser executado nessa atividade, estou usando o valor: Verificar clausulas e legalidade do contrato;
   
   **Due Date**: Tempo de SLA para conclusão da aprovação, estou usando o valor de 7 dias corridos: 0M7d0h0m;
   
   **Priority**: Prioridade da atividade, neste caso estou utilizando Normal;
   
   **Skip Approval On**: Utilizado quando temos diversos aprovadores para a mesma atividade modelo serial ou paralelo, por exemplo se é negado por um aprovador os outros não precisam avaliar por já está reprovado! Estou utilizando como desmarcado
   
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.015.png)
1. Usar o ícone de seta para baixo para ocutar as **Properties** do **User Task,** clicar duas vezes no User Task para renomear a atividade para **Aprovação Departamento Juridico**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.016.png)
1. Clicar em **Save** e testar o processo clicando em **Test** e depois no ícone **Play**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.017.png)
1. Clique no ícone Play no **Start** para testarmos nosso processo:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.018.png)
1. Selecionar o usuário e clicar em **Play**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.019.png)
1. Preencher o Formúlario e clicar em **Submit**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.020.png)
1. Após preencher o formúlario e anexar o contrato, o processo fez o roteamento para o time Juridico fazer a aprovação desse contrato, como podemos ver na imagem abaixo:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.021.png)
1. Clicar no ícone de **Play** na Aprovação do Departamento Juridico, verificar se todos os dados da Atividade estão respondendo conforme o esperado, por exemplos os valores dinamicos do Titulo da Atividade, selecionar o usuário e clicar no botão **Play**:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.022.png)
1. Escolher a opção **Launch Form** para verificar todas as informações:
   ![](Aspose.Words.2b69f4e8-d131-4524-b9f4-e07d5f2f1f9d.023.png)
1. Aprovar ou Rejeitar;
1. Verificar a execução do fluxo até o final e clicar em **Close**;
1. Fazer um novo teste desde o inicio voltar ao passo 18 executar o teste com a opção não utilizada ainda caso você escolheu **Aprovar** no passo 25 utilizar **Rejeitar**;
1. Clique em **Save** para salvar nosso progresso;
1. Fim;


[Clique aqui para voltar a lista de labs](https://github.com/vhakamine/OIC_HANDS_ON/blob/main/README.md)
