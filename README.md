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

>### **Comandos para arquivos e diretórios**
>- **pwd**: informa o caminho do diretório que você está no momento
>- **cd + pasta**: (change directory) entra na pasta que chamou
>- **cd ..**: volta um nível de pasta
>- **ls**: lista todos os diretórios e os arquivos
>- **ls -a**: lista todos os diretórios e os arquivos, incluindo os diretórios ocultos
>- **ls -l**: igual ao ls, porém, exibe informações detalhadas de cada arquivo
>- **ls -la**: inclui o retorno do -l e do -a
>- **mkdir + nome**: cria um diretório com o nome informado
>- **mkdir -p + nome**: cria um diretório com subdiretórios dentro (se não usar o -p, não funciona)
>- **rm + nome**: remove o diretório(não remove se houver arquivos ou pastas dentro)
>- **rm -rf + nome**: remove o diretório e todo o seu conteúdo
>- **cp + nome-arquivo.extensão pasta+nome-arquivo.extensão**: faz a cópia do arquivo
>- **mv + nome-arquivo.extensão pasta+nome-arquivo.extensão**: move o arquivo para a pasta indicada**:
>- **mv + nome-arquivo.extensão novo-nome-arquivo.extensão**: renomeia o arquivo
>- **touch + nome.extensão**: cria ou modifica um arquivo
>- **cat + arquivo.extensão**: mostra todo o conteúdo do arquivo
>- **head + arquivo.extensão**: mostra o início do conteúdo do arquivo
>- **head -n 2 + arquivo.extensão**: limita ainda mais a exibição do conteúdo do arquivo
>- **tail + arquivo.extensão**: exibe o final do conteúdo do arquivo
>- **tail -n 2 + arquivo.extensão**: limita ainda mais a exibição do conteúdo do arquivo
>- **more + arquivo.extensão**: exibe o conteúdo do arquivo e sua porcentagem de exibição
>- **less + arquivo.extensão**: exibe o conteúdo do arquivo e pgup e pgdown para rolar o arquvivo, 'q' para sair
>- **grep + termo pesquisa + arquivo.extensão**: pesquisa dentro do arquivo com base no termo(case sensitive)
>- **grep -n + termo pesquisa + arquivo.extensão**: pesquisa dentro do arquivo com base no termo(case sensitive) e informa o número da linha
>- **grep -n -i + termo pesquisa + arquivo.extensão**: pesquisa dentro do arquivo com base no termo(ignore case sensitive) e informa o número da linha