# Ready Play
 
 Ready Play é um projeto que tenha planos futuros de se tornar uma plataforma para jogos! Enquanto isso, o site é basicamente um CRUD ou um site de Cadastro se preferir.


## Diagrama 📉

Abaixo está um diagrama que resume o projeto atual:

[![](https://mermaid.ink/img/pako:eNp1jzEOwjAMRa8SeWql9gIdkGjLBhMwEQYrSWlE0yAnEaC2h-EsXIyUsuLp237W9x9AWKmggKazd9EieXaoec9irU8VSnSe7Jnl-Wr8dUgjK5Otdh6ZVOzowvtF2rp0uSpnllXJRmqP9GddJ5uH6IKmFDIwigxqGX8YZoaDb5VRHIooJdKVA--nyGHwdv_sBRSegsog3CR6VWu8EBooGuxcnKroa2m3hPpmmz5jQEsu?type=png)](https://mermaid.live/edit#pako:eNp1jzEOwjAMRa8SeWql9gIdkGjLBhMwEQYrSWlE0yAnEaC2h-EsXIyUsuLp237W9x9AWKmggKazd9EieXaoec9irU8VSnSe7Jnl-Wr8dUgjK5Otdh6ZVOzowvtF2rp0uSpnllXJRmqP9GddJ5uH6IKmFDIwigxqGX8YZoaDb5VRHIooJdKVA--nyGHwdv_sBRSegsog3CR6VWu8EBooGuxcnKroa2m3hPpmmz5jQEsu)


## Tecnologias usadas 💻

- HTML : (https://developer.mozilla.org/pt-BR/docs/Web/HTML).
- CSS : (https://developer.mozilla.org/pt-BR/docs/Web/CSS).
- PHP 7.4 : ([https://www.php.net/downloads](https://windows.php.net/downloads/releases/)).
- Banco de Dados SQL : (http://localhost/phpmyadmin/).
- XAMPP 7.4 : (https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/7.4.33/xampp-windows-x64-7.4.33-0-VC15-installer.exe/download).


## Requisitos 🧾


Para rodar o programa, você precisa seguir esses passos:

1. Baixar e instalar o XAMPP 7.4 (o link está acima nas **Tecnologias usadas**. Segue um vídeo ensinando com instalar o xampp (https://www.youtube.com/watch?v=R2HrwSQ6EPM)(Assista a partir do minuto 6:20)).

2. Baixe o projeto e extraia o mesmo dentro da pasta (C:\xampp\htdocs\) para que o xampp consiga reconhecê-lo e o mesmo funcionar.

3. No PHPMyAdmin (localhost/phpmyadmin) importar o arquivo SQL:

   - No PHPMyAdmin (http://localhost/phpmyadmin/), crie um novo banco de dados chamado "readyplay", clicando em "novo" e depois em "criar":
  
     
    ![readyplay_1](https://github.com/Gael1512/readyplay/assets/52392583/cf43d8a8-9d80-48e4-b890-7958b81f24e4)

   - Logo em seguida, clique em "importar" e escolha o arquivo que veio com o programa... o "createdb.sql".
  

    ![readyplay_2](https://github.com/Gael1512/readyplay/assets/52392583/7788edbe-64db-4159-a2d1-4221fd74bf39)

   - E finalize clicando em "importar" no final da rolagem da página. Após isso, seu banco de dados com a tabela correta será criada e você não precisará mais se preocupar com o banco de      dados.
  
      
    ![readyplay_2 1](https://github.com/Gael1512/readyplay/assets/52392583/8a36fba5-6dd6-48f1-a0c7-528a53f1a8c2)
    ![readyplay_2_resultado](https://github.com/Gael1512/readyplay/assets/52392583/52d4cd6e-6435-4cb0-9776-a0df24a82b4c)



## Instalação e Execução do Programa (Como funciona o programa como Cadastro / CRUD) ⬇️✅

   Para executar o programa, você precisa abrir no seu navegador, o endereço "localhost/" e escolher a pasta do projeto, dessa forma irá abrir na página de Cadastro, que por enquanto, é a pagina index do programa (ou pagina inicial se preferir):

  ![readyplay_3](https://github.com/Gael1512/readyplay/assets/52392583/b42c3f4e-d2d9-4327-92e3-91470d4a19bf)
  ![readyplay_3 1](https://github.com/Gael1512/readyplay/assets/52392583/a35bacce-1d2a-46a4-ad03-6b17ac5ffd3f)


  E então, o que se pode fazer no programa atual? (Será seguida as etapas do **CRUD**(**C**reate, **R**ead, **U**pdate, **D**elete) :


  - ***CADASTRO*** (***C***REATE):

       Nossa página principal atualmente é o Cadastro. Nele, é preciso que você preencha todas as informações corretamente, para que não aconteça nenhum infortúnio:
   
       
       ![readyplay_4](https://github.com/Gael1512/readyplay/assets/52392583/68f30c43-9822-4372-8246-7db3b9451fcc)
   
   
       Após tudo preenchido corretamente, basta clicar em "Enviar" para ser cadastrado com sucesso! :
   
   
       
       ![readyplay_4 1](https://github.com/Gael1512/readyplay/assets/52392583/05d0ab02-a471-42d6-970e-79a64a0f48fc)



       Com isso, você será reedirecionado para a próxima página, que nos leva para a nossa próxima etapa.



  - ***LISTAGEM*** (***R***EAD):


       Nesta página, você consegue verificar todos os usuários cadastrados no nosso banco de dados. E, atráves dessa listagem de usuários, você consegue *editar-los* ou *excluir-los*:
   
       
       
       ![readyplay_5](https://github.com/Gael1512/readyplay/assets/52392583/ae0e969c-0875-4f1d-a73b-ad25b42ea9ff)



       Clicando em "editar", a página irá nos reedirecionar para uma página um tanto quanto familiar... mas, que sua intenção é totalmente diferente. Isso nos leva a nossa próxima etapa.


  - ***EDITAR USUÁRIOS*** (***U***pdate):


       Perceba que essa página é bem parecida com a de Cadastro, entretanto, precisamos das informações do cadastro para poder editar-los. Afinal, como posso mudar algo sem lembrar o           que já está cadastrado previamente? Então, após o usuário alterar o que deseja (Vou atribuir ao nome o número "9999"), basta clicar em "enviar" novamente:

       OBS: As partes de "gênero" e a de "senha" precisam **obrigatoriamente** ser preenchidas novamente, pois ainda existe algumas falhas no programa.


       ![readyplay_6](https://github.com/Gael1512/readyplay/assets/52392583/66d877bd-6112-4447-8d2b-58f2178a2326)


    Após clicar em "enviar", perceba que a página apenas atualizou e que qualquer alteração feita, aparentemente, não teve sucesso. Porém, isso é apenas mais uma falha no código.

    Se você clicar em "Lista de Usuários" no canto esquerdo da página, vai ser levado para a página de listagem de usuários... E, então, perceberá que o nome foi alterado sim no banco       de dados.

   
       ![readyplay_7](https://github.com/Gael1512/readyplay/assets/52392583/ab77ffc6-94fb-4442-a66c-e22d7b119444)
       ![readyplay_7 1](https://github.com/Gael1512/readyplay/assets/52392583/10ffc783-1d7b-4e9a-accf-f39590b72724)


    Agora que voltamos à página de listagem, podemos seguir à nossa última etapa. Clique em "Excluir" e veja a mágica!!!!


   
  - ***EXCLUIR USUÁRIOS*** (***D***elete):


     Ué? a página atualizou e não tem mais nada na lista?

     Acontece que o programa simplesmente deletou o usuário do banco de dados. E para excluir, não é preciso uma página, apenas um clique e está feito.


     ![readyplay_8](https://github.com/Gael1512/readyplay/assets/52392583/7157884d-d6df-448d-9844-0ccde62afa77)




## ⚠️ Problemas ⚠️

 1. Como percebido, o programa não tem uma página inicial... Ele abre na página de Cadastro.
 2. No menu esquerdo da tela, as opções a seguir não funcionam: Inicio, Jogos e Contato.
 3. Após Editar o cadastro, a página atualiza com as informações anteriores, o que talvez deixe o usuário confuso, entretanto o cadastro foi atualizado como explicado acima.
 4. A página não têm responsividade para outros aparelhos eletrônicos, Então ela pode se quebrar dependendo de onde for acessada.

    Esses são problemas cientes pelos Devs, que irão ser resolvidos numa futura e possível atualização.

  
  
