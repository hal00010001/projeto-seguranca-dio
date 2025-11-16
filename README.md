# projeto-seguranca-dio
<h2>Projeto para o curso de Cyber Segurança da DIO</h2>

<h4>
    Utilizei o software Virtualbox para Linux para desenvolver o projeto.
</h4>

![alt text](<images/Screenshot from 2025-11-13 16-34-05.png>)


<h4>
    Fiz o download das imagens do Kali Linux 2025.3 e Metasploitable 2 para Virtualbox. Funcionaram perfeitamente.
</h4>


<h4>
    Segue as imagens dos dois sistemas funcionando:
</h4>

![alt text](<images/Screenshot from 2025-11-13 01-12-42.png>)
![alt text](<images/Screenshot from 2025-11-13 01-22-58.png>)


<h4>
    Não consegui configurar a rede como host-only como indicado no curso, então configurei como rede interna
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-01-25.png>)


<h4>
    Tive que configurar manualmente as redes com os IPs não-roteáveis e garanti para que os dois sistemas não tenham acesso à Internet
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-01-49.png>)

![alt text](<images/Screenshot from 2025-11-13 02-02-13.png>)

![alt text](<images/Screenshot from 2025-11-13 02-02-43.png>)

![alt text](<images/Screenshot from 2025-11-13 02-03-00.png>)


<h4>
    Aqui mostra os dois sistemas se comunicando
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-03-59.png>)


<h4>
    Fiz um scan com nmap mostrando as vulnerabilidades do sistema-alvo
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-07-11.png>)

<h4>
    Criei os 2 arquivos de usuário e senha para usar com o Medusa
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-37-28.png>)

<h4>
    Mostrando o conteúdo dos arquivos de usuário e senha
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-38-03.png>)

<h4>
    Como o comando Medusa é utilizado
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-39-53.png>)


<h4>
    Aqui mostrando os resultados do Medusa com o sucesso sendo apontado pelo login msfadmin e senha msfadmin
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-41-07.png>)


<h4>
    Conectando via FTP com o login e senha que resultaram em sucesso
</h4>

![alt text](<images/Screenshot from 2025-11-13 02-42-52.png>)


<h4>
    Agora seguindo com o processo com DVWA
</h4>

![alt text](<images/Screenshot from 2025-11-15 01-36-15.png>)


<h4>
    Abrindo o Developer Tools
</h4>

![alt text](<images/Screenshot from 2025-11-15 01-38-07.png>)



<h4>
    Mostrando a falha quando tenta acessar com usuário admin e senha admin
</h4>

![alt text](<images/Screenshot from 2025-11-15 01-39-40.png>)



<h4>
    Mostrando a mensagem "login failed" sendo mostrada logo abaixo do formulário de login
</h4>

![alt text](<images/Screenshot from 2025-11-15 01-40-48.png>)



<h4>
    Utilizando Medusa com os arquivos de login e senha criados para descobrir o login e senha do DVWA
</h4>

![alt text](<images/Screenshot from 2025-11-15 01-55-02.png>)



<h4>
    Resultado do Medusa com as credenciais que irão funcionar
</h4>

![alt text](<images/Screenshot from 2025-11-15 02-03-27.png>)



<h4>
    Colocando login e senha
</h4>

![alt text](<images/Screenshot from 2025-11-15 02-05-06.png>)



<h4>
    Mostrando o acesso bem sucedido
</h4>

![alt text](<images/Screenshot from 2025-11-15 02-07-20.png>)



<h4>
    Utilizando o enum4linux
</h4>

![alt text](<images/Screenshot from 2025-11-15 02-58-59.png>)



<h4>
    Mostrando os usuários descobertos no sistema
</h4>

![alt text](<images/Screenshot from 2025-11-15 03-01-31.png>)



<h4>
    Criando os novos arquivos baseado nos usuários capturados do sistema
</h4>

![alt text](<images/Screenshot from 2025-11-15 03-08-55.png>)



<h4>
    Mostrando o conteúdo dos arquivos
</h4>

![alt text](<images/Screenshot from 2025-11-15 03-09-19.png>)



<h4>
    Utilizando o Medusa com os novos arquivos criados tentando acessar o Samba server
</h4>

![alt text](<images/Screenshot from 2025-11-15 03-21-05.png>)



<h4>
    Mostrando o resultado das tentativas de acesso
</h4>

![alt text](<images/Screenshot from 2025-11-15 03-22-28.png>)



<h4>
    E na última tela mostrando o acesso com o smbclient
</h4>

![alt text](<images/Screenshot from 2025-11-15 03-29-53.png>)