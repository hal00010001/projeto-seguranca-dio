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





