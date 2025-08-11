# Hospedagem no GitHub Pages

### Como publicar um site usando GitHub Pages
1. Acesse o repositório remoto no __GitHub__
2. Clique em __Settings__
3. Selecione a aba __Pages__
4. Essa tela permite configurar o __GitHub Pages__, que publica um site diretamente a partir do repositório

### Métodos principais de publicação:
__1. GitHub Actions__
* Método avançado para automatizar a construção e publicação do site
* Indicado para projetos que usam frameworks (React, Angular, Vue) ou que precisam de compilação antes da publicação
* Permite personalizar todo o processo com arquivos de configuração
__2. Deploy from a branch (Publicar a partir de um branch)__
* Método simples e tradicional
* O GitHub publica os arquivos de um branch específico (como `main` ou `gh-pages`)
* Ideal para sites estáticos simples em HTML, CSS e JavaScript, sem necessidade de build

### Ativando o GitHub Pages:
* Se aparecer a mensagem __"GitHub Pages is currently disabled"__, significa que o site ainda não está publicado
* Escolha o branch que será usado para gerar o site (por exemplo, main ou gh-pages)
* Clique em __Save__ para ativar a publicação
* O GitHub começará a publicar o site automaticamente

---

### Configurando a pasta de publicação no GitHub Pages
1. Ao selecionar o branch para publicar no __GitHub Pages__, será habilitado um novo campo para escolher a pasta de origem dos arquivos do site dentro desse branch
2. As opções comuns são:
* / (root) — os arquivos do site estão na raiz (pasta principal) do repositório
* /docs — os arquivos do site estão dentro da pasta chamada docs. Nesse caso, o GitHub Pages publica apenas o conteúdo dessa pasta, ignorando o restante dos arquivos do repositório

### Quando usar a pasta /docs
* Para separar o código do site de outros arquivos no repositório
* Seguindo o padrão do GitHub que recomenda a pasta docs para hospedar páginas
3. Após escolher o branch e a pasta, clique em Save
4. Em alguns instantes, o site será publicado e ficará disponível para acesso ou para remoção da publicação