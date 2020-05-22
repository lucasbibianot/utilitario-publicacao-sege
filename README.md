# utilitario-publicacao-sege
Utilitário para automatizar a publicação de arquivos do Igest pela SEGE

## Requisitos:
* Windows 
* Google Chrome
* Webdriver Google Chrome

## Instalação do pacote
**Criar a seguinte estrutura de diretórios na raiz c:**
* publicar-portal
  * web-driver
  * arquivos-publicacao
1. Copiar o arquivo [automacao-publicacao](https://github.com/lucasbibianot/utilitario-publicacao-sege/raw/master/automacao-publicacao.exe) para o diretório **publicar-portal**
1. Adicionar o arquivo [.env](https://github.com/lucasbibianot/utilitario-publicacao-sege/blob/master/.env) no diretório **publicar-portal**
1. Realizar o download do [web-driver](https://chromedriver.chromium.org/downloads) de acordo com a sua versão do Google Chrome e descompactar e salvar o arquivo *chromedriver.exe* no diretório **web-driver**
1. Adicionar os arquivos que serão publicados no diretório **arquivos-publicacao**

## Configuração do ambiente
* Abrir o arquivo **.env** com o bloco de notas e preencher as propriedades:
  * **usuario**: Usuário de login no portal TRT3
  * **senha**: Senha do usuário para login no portal TRT3
  * **ind_operacao**: Valor 'A' se for atualizar arquivos, ou valor 'I' para incluir novos arquivos
  * **chrome_exe**: Verificar se o caminho padrão está correto
  * **diretorio_arquivos**: Ajustar se necessário
  * **web_driver**: Ajustar se necessário
  
 ## Execução
 Para a execução, basta um duplo clique no arquivo automacao-publicacao.exe
