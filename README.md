Phishing: Captura de Senhas
Ferramentas Utilizadas
Kali Linux
Setoolkit
Windows 7
Configurando o Phishing no Kali Linux
Acesso root:

Copy code
sudo su
Desativando o Apache:

perl
Copy code
sudo lsof -t -i tcp:80 -s tcp:listen | sudo xargs kill
Iniciando o Setoolkit:

Copy code
setoolkit
Tipo de Ataque: Social-Engineering Attacks

Vetor de Ataque: Web Site Attack Vectors

Método de Ataque: Credential Harvester Attack Method

Método de Ataque: Site Cloner

URL para Clone: http://www.facebook.com

Aviso
É importante desativar o Apache para que o projeto funcione corretamente.

Abrindo o Site Clonado pelo Internet Explorer (Windows 7)
Importante
Alguns navegadores, principalmente os mais atuais, podem não rodar o clone corretamente. Uma das melhores opções para realizar o teste é o Internet Explorer do Windows 7. Testar diferentes navegadores é importante para avaliar as possibilidades.
