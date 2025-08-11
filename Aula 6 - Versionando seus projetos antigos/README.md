# Versionando seus projetos antigos

### Versionando um projeto antigo
1. Localize o projeto em seus arquivos ou backups anteriores
2. Coloque-o dentro do projeto desejado ou crie um novo repositório com esse projeto
3. Realize o commit
4. Publique com o git push

---

### Ignorando arquivos no Git usando GitHub Desktop
1. No __GitHub Desktop__, ao preparar um commit, selecione o arquivo que deseja ignorar
2. Clique com o botão direito sobre o arquivo e escolha a opção __Ignore file (add to .gitignore)__
3. Para ignorar todos os arquivos com a mesma extensão, clique na opção __Ignore all .txt files (add to .gitignore)__ que aparece abaixo
4. O arquivo __.gitignore__ será criado (ou atualizado) na pasta do projeto, contendo o nome ou padrão dos arquivos ignorados
5. Quando o repositório for enviado ao __GitHub (site)__, o arquivo .gitignore será incluído
6. Os arquivos configurados para serem ignorados não serão adicionados ao repositório; eles apenas constam listados dentro do __.gitignore__