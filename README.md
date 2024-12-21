# Phishing para captura de senhas do Facebook

### Ferramentas utilizadas para o desafio

- Kali Linux no Virtual Box
- Ferramenta The Social-Engenieer Tolkit, executando no terminal: setoolkit

### Configurando o Phishing no Kali Linux

- Alterar permissão para root, executando no terminal: sudo su.
- Executar a ferramente setoolkit, executando no terminal: setoolkit.
- Abre um menu com as opções da ferramenta. Iremos utilizar a primeira opção.
- Digitar 1 e <ENTER> para escolher a ferramenta: Social-Engineering Attacks.
- Selecionamos agora o vetor do ataque. Digitando 2 <ENTER>: Web Site Attack Vectors.
- Selecionar o método de ataque. Digitar 3 <ENTER> para escolher: Credential Harvester Attack Method.
- Selecionar a opção que clona um website. Digitar 2 <ENTER>: Site Cloner.
- A ferramenta precisa do IP do servidor que fará a coleta das credenciais, em nosso caso será a própria
  máquina onde está o Kali Linux.
- A ferramenta já nos informa o IP local.
- Caso você precise, para obter o IP, basta usar o comando ifconfig no terminal.
- Digitar então o IP da máquina e <ENTER>.
- Agora iremos clonar o website "isca", digitando a URL do Facebook: http://www.facebook.com.
- Abre seu navegador e acesso o IP do seu servidor.
- No console do Kali verá que está havendo acessos.
- Poderá verificar que foi capturado o login e senha, conforme imagem em anexo.

### Resutados
![teste1](https://github.com/user-attachments/assets/d5ebebeb-efc7-485d-8616-a44deff7cd3b)

![teste2](https://github.com/user-attachments/assets/f60d6ff9-76df-4f2f-be2f-234c082f18ed)


