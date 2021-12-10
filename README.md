# kubeDev

## **00 | introdução ao linux**
>### **sistema de arquivos no linux**
>- **/**: é chamado de diretório raiz, comparando com o Windows, é como se fosse o C:
>- **/home:** é onde ficam os diretórios de trabalho dos usuários, individual para cada usuário(semelhante a pasta de usuários no Windows)
>- **/root:** é o diretório home do super usuário do linux
>- **/bin:** é onde ficam os principais comandos do linux(cat, su, rm, pwd)
>- **/lib:** bibliotecas compartilhadas pelos programas e módulos do kernel
>- **/usr:** é onde a maioria dos programas são instalados.  Normalmente é usado com acesso de somente leitura pelos usuários
>- **/boot:** é onde ficam os arquivos estáticos de gerenciamento de inicialização do sistema operacional
>- **/etc:** é onde ficam os arquvivos de configuração do sistema e scripts de inicialiazação
>- **/proc:** diretório virtual de informações do sistema
>- **/sbin:** diretório de programas usados pelo root, para administração e controle do funcionamento do sistema
>- **/tmp:** arquivos temporários
>- **/var:** dados variáveis como log, dados de administração, login e arquivos trasitórios
>- **/opt:** aplicativos adicionais e pacotes de software
>- **/dev:** arquivos de dispositivos (periféricos)
>- **/mnt:** ponto de montagem para montar um sistema de arquivos temporariamente

>### **comandos básicos**
>- **uname:** retorna o nome e o kernel do linux
>- **uname -s:** retorna o kernel do linux
>- **uname -n:** retorna o nome da máquina
>- **uname -r:** retorna o release do kernel
>- **uname -v:** retorna a versão do kernel
>- **uname -m:** retorna o nome do hardware
>- **uname -p:** retorna o tipo do processador
>- **uname -i:** retorna a arquitetura do processador
>- **uname -o:** retorna o sistema operacional
>- **uname -a:** retorna todas as informações dos comandos acima
>- **sudo + comando:** utiliza os "super-poderes" do usuário admin
>- **sudo su:** loga como super usuário
>- **exit:** sai do super usuário e retorna ao usuário padrão que estava logado
>- **who:** informa qual usuário está logado no SO
>- **shutdown:** encerra o SO e desliga a máquina
>- **shutdown -r now:** reinicia a máquina
>- **man + comando:** exibe o manual do comando ou recurso