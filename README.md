# Script-de-Criacao-de-Estrutura-de-Usuarios-Diretorios-e-Permissoes
Script de Criação de Estrutura de Usuários, Diretórios e Permissões - LINUX UBUNTU


Neste projeto iremos criar um script onde toda a infraestrutura de usuários, grupos de usuários, diretórios e permissões serão criadas automaticamente. Será realizado o upload do arquivo de script no GitHub para futuras reutilizações do script. Sendo assim, toda nova máquina virtual que for iniciada já estará pronta para uso quando o script for executado.

##
<div align="center">
  <h1>
   ✨ ARTIGO - na plataforma DIO ✨
  </h1>
 <h5> https://web.dio.me/articles/script-da-vm-ubuntu-para-o-github?back=%2Farticles&page=1&order=oldest </h5>
</div>

Depois de realizar o primeiro desafio do Bootcamp Linux do Zero, compreendi que os comandos de envio dos comandos podem ser úteis para possíveis futuras consultas ou para medir o nível de aprendizado e conhecimento sobre o assunto, por isso, aqui está disponível os seguintes passos para cumprir essa tarefa:

Para enviar um script do Ubuntu VM para um repositório do GitHub, é necessário seguir os seguintes passos:

1. Certifique-se de ter uma conta do GitHub e de ter criado um repositório para o qual deseja enviar o script.
2. Instale o Git no seu Ubuntu VM, caso ainda não o tenha feito, utilizando o seguinte comando:

🔸sudo apt-get update sudo apt-get install git 

3. Crie um novo diretório para o seu projeto, caso ainda não o tenha feito, utilizando o seguinte comando:

🔸mkdir meu-projeto cd meu-projeto 

4. Crie um novo repositório Git para o seu projeto utilizando o seguinte comando:

🔸git init 

5. Copie o seu script para o diretório do projeto.

6. Adicione o script ao controle de versão Git, utilizando o seguinte comando:

🔸git add meu-script.sh 

7. Realize o commit do seu script utilizando o seguinte comando:

🔸git commit -m "Adicionando meu script ao repositório" 

8. Adicione o repositório remoto do GitHub como destino para o seu repositório local, utilizando o seguinte comando:

🔸git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git 

Note que você deve substituir seu-usuario pelo seu nome de usuário no GitHub e nome-do-repositorio pelo nome do repositório que você criou.
9. Envie o seu script para o repositório remoto do GitHub utilizando o seguinte comando:

🔸git push -u origin master 

Esse comando irá enviar o conteúdo do seu repositório local para o repositório remoto do GitHub. Certifique-se de substituir master pelo nome do seu branch principal, caso você tenha optado por utilizar outro nome.

##
<strong>
Alguns links úteis:
  </strong>

Para a execução dos comandos é necessário possuir um software de virtualização e o SO de sua preferência virtualizado (ISO).

🤍https://ubuntu.com/#download

🤍https://www.virtualbox.org/

##



<strong>👽 Espero ter ajudado!</strong>
