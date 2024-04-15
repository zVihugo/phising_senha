Phishing: Captura de Senhas
===========================

Ferramentas Utilizadas
----------------------

*   **Kali Linux**
*   **Setoolkit**
*   **Windows 7**

Configurando o Phishing no Kali Linux
-------------------------------------

1.  Acesso root:
    
    Copy code
    
    `sudo su`
    
2.  Desativando o Apache:
    
    perlCopy code
    
    `sudo lsof -t -i tcp:80 -s tcp:listen | sudo xargs kill`
    
3.  Iniciando o Setoolkit:
    
    Copy code
    
    `setoolkit`
    
4.  Tipo de Ataque: **Social-Engineering Attacks**
    
5.  Vetor de Ataque: **Web Site Attack Vectors**
    
6.  Método de Ataque: **Credential Harvester Attack Method**
    
7.  Método de Ataque: **Site Cloner**
    
8.  URL para Clone: [http://www.facebook.com](http://www.facebook.com)
    

### Aviso

É importante desativar o Apache para que o projeto funcione corretamente.

Abrindo o Site Clonado pelo Internet Explorer (Windows 7)
---------------------------------------------------------

### Importante

Alguns navegadores, principalmente os mais atuais, podem não rodar o clone corretamente. Uma das melhores opções para realizar o teste é o Internet Explorer do Windows 7. Testar diferentes navegadores é importante para avaliar as possibilidades.
