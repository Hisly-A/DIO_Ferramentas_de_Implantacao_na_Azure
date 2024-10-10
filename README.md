# DIO - Ferramentas de Implantação na Azure
Ferramentas de Implantação na Azure


## 🔎 Cloud Shell	

Abra o portal do [`Azure`](https://portal.azure.com), clique no ícone do **Cloud Shell** na barra superior.

![AZ10-01](https://github.com/user-attachments/assets/5098cb80-9568-40ce-9b37-d1b64aea39be)

Esse botão permite executar linhas de código e comandos direto no Azure.

Ao clicar nele é aberta a barra de execução de código:

![AZ10-02](https://github.com/user-attachments/assets/cd37c02c-2c8f-4f85-b975-8440e6ed8d20)

Um detalhe é que para poder executá-lo é necessário ter um Storage account criado, do contrário ele não conseguirá carregar.

Na barra superior note que ele carregou como Power Shell, e que ele possui algumas funções como importar ou exportar arquivos e abrir a tela em uma nova aba:

![AZ10-03](https://github.com/user-attachments/assets/bf157f4c-d032-4a71-9973-869908064671)

![AZ10-10](https://github.com/user-attachments/assets/b8ca4a44-e961-4fbf-8732-8aa607278629)

O Cloud Shell também pode ser aberto como Bash:

![AZ10-04](https://github.com/user-attachments/assets/9b22995e-0316-431d-9cf4-8b22f081c598)

Execute o comando *help* e verifique o resultado:

![AZ10-05](https://github.com/user-attachments/assets/3013e872-5050-424d-b7bf-43628a91441f)

![AZ10-06](https://github.com/user-attachments/assets/c4978c3c-5a36-4510-a637-9f623dbf5a48)

Pressione *h* e veja o retorno:

![AZ10-07](https://github.com/user-attachments/assets/33fe6c57-5bd0-4b74-8208-44aecc897ab9)

![AZ10-08](https://github.com/user-attachments/assets/c187f6e2-e536-4bda-8807-18e613f551a6)

Pressione *q* para sair e voltar à tela inicial.

Digite *az* e veja que é sugerido um comando a ser executado:

![AZ10-09](https://github.com/user-attachments/assets/c1ad045d-b14d-4c75-86b4-be3f3b960f03)


## Azure Command-line interface e Azure Powershell

Aba um grupo de recursos criado e clique em um dos recursos existentes:

![AZ10-11](https://github.com/user-attachments/assets/e5a0569e-137e-4836-85b6-f20a48fcfb59)

Observe as opções diponíveis no grupo **Automation** e clique na opção **CLI/PS**:

![AZ10-12](https://github.com/user-attachments/assets/4b5ab1c8-4143-47ac-81be-3b23b59d2836)

O **Azure CLI** ou **Azure Command-line interface** é um conjunto de comandos usados para criar e gerenciar recursos do Azure.

Na aba **PS** ele traz os comandos que podem ser executados no Azure Powershell:

![AZ10-13](https://github.com/user-attachments/assets/74f4fe9e-58b4-45ba-837a-7cd195f71cd5)

Clique em **Export template**, aguarde ele ser gerado e observe os detalhes desse template para a criação de uma rede virtual:

![AZ10-14](https://github.com/user-attachments/assets/19a26600-d5a2-47b0-a000-6152b86737a6)

Acesse o endereço indicado na imagem abaixo:

![AZ10-15](https://github.com/user-attachments/assets/b08a56bd-49a6-4b6f-849a-2f0d120102a7)

Neste endereço é possível fazer um comparativo entre duas estruturas de código, como no exemplo abaixo onde a linguagem da esquerda é Bicep e da direita é ARM:

![AZ10-16](https://github.com/user-attachments/assets/fb049f63-5b11-4382-8464-6c7b91c75bd0)

Repare na quantidade total de linhas da implementação de uma mesma funcionalidade em cada liguagem.


## Azure Arc

Pesquise por Azure Arc:

![AZ10-17](https://github.com/user-attachments/assets/51619d7a-3611-4ca7-9da8-84ffae69629f)

![AZ10-18](https://github.com/user-attachments/assets/574434a6-4efc-4c0c-8339-d64bf1525ff4)

Essa é uma ferramenta de gerenciamento multi cloud que está presente em todas as assinaturas do Azure, mas precisa ser configurada. Ela permite administrar recursos do Azure não só dentro dele, mas também fora da plataforma.

Observe as funcionalidades disponíveis em cada aba:

![AZ10-19](https://github.com/user-attachments/assets/dfb714d5-50ee-4bcf-a46a-bbe466c23a61)

![AZ10-20](https://github.com/user-attachments/assets/950afa98-0624-437d-951e-4fc5faf35338)

![AZ10-21](https://github.com/user-attachments/assets/0d5433e0-2821-48f2-ac3e-db281437202f)


## Links utilizados

- https://portal.azure.com/

