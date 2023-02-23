<h1> DESAFIO DE PHISHING - DIO --> CAPTURANDO SENHAS DO FACEBOOK 🕵🏻💻</h1>


O desafio é conseguir rodar o o setoolkit e criar um clone do facebook, usando a propria maquina como servidor e assim fazer a captura do possivel login e senha da vítima.

-----

<h2>FERRAMENTAS 🛠️</h2>

- ***Setoolkit***
- ***Kali Linux***
- ***Windows***
- ***Navegador***

-----

<h2>RESULTADO ESPERADO ✅💻</h2>

![RESULTADO](https://user-images.githubusercontent.com/78884474/220962280-dd126704-1e05-40ac-aa78-d694d3c71529.png)

-----

<h2>AGORA, VAMOS PARA A AÇÃO! 🕵🏻</h2>

### 1º - PASSO
Antes de tudo, vamos acessar o ***KALI LINUX***, e entrar no terminal, logo a pós para ultilizar a ferramenta ***setoolkit*** precisamos ter acesso root.
No terminal é so digitar : ***sudo su*** e dar enter, vai pedir para colocar sua senha root  então vc estará com "permissão especial" para poder acesaar a ferramenta.

Como nosso foco inicial é fazer um phishing, que é um ataque de engenharia social, vamos rodar o ***setoolkit***:

no terminal com o acesso especial, digite ***setoolkit***
 <div align="center">
      <img src="https://user-images.githubusercontent.com/78884474/220964828-0f4b3390-65d3-4127-aeb7-6544e1e64316.png" width="700px"  />
   </div>


-----

### 2º - PASSO
Após acessar a ferramenta vamos digitar ***1 - Social-Engineering Attacks*** para definir o tipo do ataque.

 <div align="center">
     <img src="https://user-images.githubusercontent.com/78884474/220965857-6ede08a2-23b9-4045-b11d-5544ad20c9c0.png" width="700px"  />
  </div>

-----

### 3º - PASSO
Após definido o tipo de ataque vamos digitar ***2 - Web Site Attack Vectors*** para definir o vetor do ataque. Como mostra a imagem a abaixo:

<div align="center">
   <img src="https://user-images.githubusercontent.com/78884474/220967740-9ff29d80-0425-44c2-b742-77cc69aca456.png" width="700px"  />
</div>

-----

### 4º - PASSO
Assim que definirmos o vetor de ataque vamos digitar ***3 - Credential Harvester Attack Method***, este método ele é responsavel por pegar, coletar as informações de email e senha digitada pela vitima. so selecionar como na imagem abaixo:

<div align="center">
   <img src="https://user-images.githubusercontent.com/78884474/220969220-e3fe3b6a-7288-4999-877a-afd415e66524.png" width="700px"  />
</div>

-----

### 5º - PASSO
Agora vamos digitar ***2 - site cloner*** que serve para clonar o site. caso já tenha um template pronto, pode usar ele também ultilizando as outras opções.

<div align="center">
   <img src="https://user-images.githubusercontent.com/78884474/220970051-b99aeb4e-8b09-4cce-9550-c5571811d275.png" width="700px"  />
</div>

-----

### 6º - PASSO
Neste passo o setoolkit pede para que digitemos o IP da nossa maquina, que ele irá usá-la como servidor, o setoolkit já da a sugestão de ip, caso não queira trocar é só dar um enter e prosseguir para o próximo passo.

<div align="center">
   <img src="https://user-images.githubusercontent.com/78884474/220970985-e10cfac6-a27b-4e74-b193-3ff4683046e3.png" width="700px"  />
</div>

-----

### 6º - PASSO
Aqui definimos o site a ser clonado, no nosso caso o ***facebook***, vamos digitar a URL : http://www.facebook.com

<div align="center">
   <img src="https://user-images.githubusercontent.com/78884474/220972414-9540ee9b-0fc6-4e6f-a41a-f899cd7b15db.png" width="700px"  />
</div>

-----

### 7º - PASSO
Após colcoar a URL e dar um enter, só aguardar um pouco e ela irá carregar, se aprecer como esta a imagem a baixo é porque o clone deu certo. ✅👍🏻

<div align="center">
   <img src="https://user-images.githubusercontent.com/78884474/220972799-4a39bb03-1dc6-45d7-b47f-32ee596b2137.png" width="700px"  />
</div>

<h2>REALIZANDO O ATAQUE 💻🛠️🕵🏻</h2>


Após tudo feito e ok, vamos simular um atque desse phishing e ver se está funcionando tudo certo. 

Você pode pegar o IP definido comos ervidor e digitar no seu navegador e da um enter, e irá abrir a pagina fake do facebook, como mostra a imagem abaixo:

<div align="center">
   <img src="https://user-images.githubusercontent.com/78884474/220974064-38627f9a-e0b0-4359-b291-b15e27e02b88.png" width="700px"  />
</div>

-----
Depois que a vitima colocar todas as credenciais e clicar em entrar, a pagina ira carregar e dar um glitch, o link será redirecionado para a pagina real do facebook enquanto o setoolkit irá coletar as credenciais colocada.

<div align="center">
   <video src="https://user-images.githubusercontent.com/78884474/220981914-b2875290-7425-4523-a12e-fb9b303c35e2.mp4" width="700px"  />
</div>

<h2>OBSERVAÇÕES FINAIS</h2>

- Para deixar o link mais "bonito" você pode abrir um encurtador de link e coloca-lo lá, assim fica mais atrativo a vitima.
- Use o conhecimento com prudência !!!!


- ***Este treinamento tem todo um intuinto educativo, afim de propagar conhecimento e apredizado para que, aqueles como eu, entendam os processos ultilizados por pessoas maliciosas, e asim possa se proteger desses ataques.***

-----

 <div align="center">
      <img src="https://user-images.githubusercontent.com/78884474/211343329-a8718daf-0953-4563-83f5-20901019202f.png" width="100px"  />
   </div>

</br>
</br>
</br>

<div align="center"> 
 	<a href="https://instagram.com/creative.agenciaofl" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
 <a href="https://discord.gg/pDbY76q8Qf" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a> 
  <a href = "mailto:igo.dev2023@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/igomarcos/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
 </div>




