# Clonando um Repositório

### O que seria clonar um repositório?
Baixar um repositório público para a máquina local e colocá-lo sob controle de versão no Git localmente

---

### Clonando um repositório
1. Abrir um repositório no GutHub
2. Clique no botão __Code__
3. Selecione a opção __Open with Github Desktop__
4. Confirme a permissão para que o navegador abra o __GitHub Desktop__
5. No pop-up __Clone a repository__ que será exibido:
   1. Em __Repository URL or GitHub username and repository__, verifique o endereço de origem do repositório
   2. Em Local path, escolha a pasta onde o repositório será salvo localmente
6. Clique em __Clone__ para iniciar a cópia para sua máquina
7. Espere terminar o carregamento e o repositório estara clonado

---

### Verificar repositórios existentes
Ao clicar em __Current repository__, será exibida uma lista com todos os repositórios disponíveis, incluindo os seus e aqueles de outras pessoas que você já acessou ou clonou
Por fim, dentro da pasta que definimos, o projeto aparecerá no __Explorador de Arquivos do Windows__, junto com as demais pastas e arquivos já existentes

---
### Deletando um repositório
1. Abra o __GitHub Desktop__ e clique em __Current repository__ (menu de repositórios)
2. Na lista, localize o repositório que deseja remover
3. Clique com o botão direito sobre o repositório desejado
4. Selecione __Remove__ no menu de contexto
5. Será exibida uma tela de confirmação com uma caixa de seleção perguntando se você deseja mover os arquivos para a lixeira
   1. Marque a caixa para mover os arquivos locais para a lixeira (apagar do disco)
   2. Desmarque a caixa para apenas remover o repositório da lista do GitHub Desktop, preservando os arquivos no disco
6. Clique em Remove para confirmar a remoção
7. (Opcional) Se escolheu mover para a lixeira, esvazie a lixeira do sistema para remover os arquivos definitivamente

_Observação: esse procedimento remove o repositório local (ou a entrada no GitHub Desktop). Para excluir um repositório remoto no __github.com__ é necessário entrar nas __Settings__ do repositório no site e usar a opção __Delete this repository__ na seção __Danger Zone__ (o GitHub pede confirmação digitando o nome do repositório)_

---

### Verificando se uma pasta está versionada pelo Git
1. Abra o Explorador de Arquivos no Windows
2. Acesse a pasta que deseja verificar
3. No menu superior, clique em Exibir
4. Ative a opção Mostrar itens ocultos
5. Procure na pasta por um diretório chamado .git
6. Se a pasta .git estiver presente, significa que o diretório está sob controle de versão do Git
7. Se não existir, a pasta não está sendo versionada pelo Git
---
### Alterando projetos de outras pessoas
1. Ao tentar alterar um projeto de outra pessoa e realizar um commit, será exibida uma mensagem 
> __You don't have write access to {nome_do_repositorio}. Want to create a fork?__

> *mensagem mostra que você não pode escrever no repositório {nome_do_repositorio} e oferece criar um fork*

2. É possível __visualizar e analisar__ o código de qualquer repositório público, mas __não é permitido__ enviar alterações diretamente para o repositório original sem autorização
3. Essa restrição evita que qualquer pessoa modifique o projeto, mantendo a organização e a integridade do código
4. Para sugerir mudanças, existem três abordagens comuns:
   1. __Branches__ — criar ramificações no código para desenvolver e propor novas funcionalidades ou correções
   2. __Issues__ — registrar problemas, dúvidas ou sugestões diretamente no repositório
   3. __Forks__ — criar uma cópia do repositório na sua conta, fazer as alterações e, em seguida, abrir um Pull Request para que o dono do projeto avalie e aceite (ou não) as mudanças

Quando clonamos o repositório de outra pessoa, ele é copiado para o nosso repositório local (na nossa máquina). Caso queiramos ter esse projeto também em um repositório remoto vinculado à nossa conta, damos outro nome a ele — nesse caso, não se trata de um clone, mas sim de um fork.