Autor: António Freitas


Objetivos



Parte 2: Controle de Versão e Colaboração (opcional)

2.1 Criando e mesclando um Pull Request
• Criar um Pull Request no GitHub para mesclar nova-feature em main.
• Aceitar e fazer o merge.


1 - Abrir o branch nova-feature
![bfdd4468bcb381b982e7181d0156fbd4](https://github.com/user-attachments/assets/cb88eaf5-1ecc-4d24-94c5-e12b930ed6ad)







2- Depois de realizar alguma alteração no branch (Neste caso adicionei o ficheiro 2_1_PullRequest) e fazer commit desta alteração, selecionar o aviso que indica que o branch está mais avançado que o main branch

![947a4e7e49757385a710d45d26c33e85](https://github.com/user-attachments/assets/313ec108-c861-4ced-8c4d-e746c0600a2b)


3 - Selecionar a opção de “Create Pull Request” 

![e6089940a1e64d068acebaaee659bf29](https://github.com/user-attachments/assets/a98a4b83-303a-4bd8-a981-6024e73ff070)






4- Depois de adicionar um titulo e uma descrição, selecionar “Create Pull Request” 

![31f1b7e04ddc104758fa6e6d1d6722f0](https://github.com/user-attachments/assets/37b8cacc-2d9d-47f0-a6a9-83f9dba2407c)

5 - Neste caso não existem conflitos, logo pode-se selecionar “Merge Pull Request” imediatamente


![7bd8f20ac8139bd8fd6942a842dec25d](https://github.com/user-attachments/assets/06737b75-bdfa-46b5-ad36-ae7b5c07f306)


6- O ficheiro pedirá para adicionar uma descrição e pedirá para confirmar o merge. Selecionar “Confirm Merge” para terminar o processo

![6e7058c1481ffe346534384d74ee051f](https://github.com/user-attachments/assets/0e043cbb-3fbc-4eb4-b8c4-0444a2f6c0a6)


2.2 Resolvendo conflitos de merge
• Criar um novo branch e editar log.txt.
• Fazer o mesmo no main e tentar mesclar.

1 - Seleciono Branches no main branch

![d21c4e856074a6f3a789b6b934cad877](https://github.com/user-attachments/assets/1e01d0fd-c2c8-4b84-a03b-d42ec4295063)








2 - Crio outro branch manualmente

![653fec27f78ad2f004ec36198e11e1c4](https://github.com/user-attachments/assets/b59830e2-9866-48fc-a7c4-943c1e0da43c)



3 - Depois de alterar o log.txt file em ambos o main branch e o novo branch, repete-se o processo de forma a fazer um pull request. Contudo quando se chegar ao ponto de fazer merge, terá ocorrido um conflito. 
Selecionar “Resolve conflicts”

![f3deac0e36e53558611df66e1e5211e0](https://github.com/user-attachments/assets/2a838f67-a87b-4e17-b7f7-4340cbafd4da)


4- A parte a ser alterada no texto estará marcada. Fazer as alterações necessárias e retirar os marcadores <<<<<< ===== e >>>>> de forma a indicar que será esta a versão final.

![580a9e0fed0f8ac5eb8e1e905ed10c77](https://github.com/user-attachments/assets/e85477ee-5097-4a97-998a-e39931715404)



5 - No canto superior direito pressionar “Commit merge”

![46b4c744e40bcff444ef04d8efc9a981](https://github.com/user-attachments/assets/8e83407b-6134-4dfa-a081-2717436b67b7)

6 - Voltando ao Pull Request, a opção de fazer Merge pull request estará agora disponível, podendo-se assim completar a Pull Request


![image](https://github.com/user-attachments/assets/30ccf49f-a424-4dea-8502-5dc685a1eaca)




2.3 Fazendo revisão de código no GitHub
• Criar um Pull Request e solicitar um Code Review.
• Comentar uma linha do código e sugerir mudanças



1 - Depois de realizar um pull request eu posso selecionar um dos ficheiros actualizados

![image](https://github.com/user-attachments/assets/177db68b-d874-45df-b0f8-4973ac18e1c5)


2 - No ficheiro actualizado posso tanto usar o símbolo de comentário como o simbolo de + à frente das linhas no ficheiro de forma a comentar uma linha específica

![image](https://github.com/user-attachments/assets/0b89fc45-26ee-40d6-9234-4d7ceece57f9)





3 - Exemplo de comentário

![image](https://github.com/user-attachments/assets/55591f10-b6a1-402c-8dc1-131c9b0d893f)



4- Para termina a review, no canto superior direito selecionar “Finish your review” e depois selecionar “Submit Review”

![image](https://github.com/user-attachments/assets/118e7562-7f9b-498d-8f76-4da794d4a87a)

5 - Agora na página do pull request, será também apresentado os comentários feitos em review ao ficheiro.

![image](https://github.com/user-attachments/assets/b8297dd4-c1e6-4490-b41a-984fed47dd2a)









