PHISHING: CAPTURA DE SENHAS 
Ferramentas utilizadas
Kali Linux;
Setoolkit;
Windows 7.
Configurando o Phishing no Kali Linux
Acesso root: sudo su

Desativando o Apache: sudo lsof -t -i tcp:80 -s tcp:listen | sudo xargs kill

Iniciando o setoolkit: setoolkit

Tipo de ataque: Social-Engineering Attacks

Vetor de ataque: Web Site Attack Vectors

Método de ataque: Credential Harvester Attack Method

Método de ataque: Site Cloner

URL para clone: http://www.facebook.com

Warning

É importante que o apache seja desativado para que o projeto funcione corretamente.

Abrindo o site clonado pelo Internet Explorer (Windows 7)


Important

Alguns navegadores, principalmente aqueles mais atuais, não rodarão o clone. Uma das melhores opções para realizar o teste é o Internet explorer do Windows 7. É importante testar as possibilidades!
