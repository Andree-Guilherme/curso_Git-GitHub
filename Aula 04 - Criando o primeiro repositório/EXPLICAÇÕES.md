# **Sempre marcar a criação usando o README — Por quê?**

> O arquivo README é como uma "capa" do projeto. Ele serve para explicar de forma simples o que o projeto faz, como usar e outras informações importantes. Ter um README desde o começo ajuda na organização e já cria o primeiro arquivo do repositório

# **Licenças**

Colocar a licença **MIT** – embora também sejam utilizadas as licenças **Apache** e **GNU GPL v3**

### **O que são?**

São **formas de dizer como outras pessoas podem usar seu código**. Elas são importantes porque:

*   Definem **o que os outros podem ou não fazer** com seu projeto
*   Protegem **você** de problemas legais
*   Ajudam outros desenvolvedores a saber **como colaborar ou reutilizar** seu trabalho

> **📝 MIT License (Muito permissiva)**
> 
> *   **Pode usar, copiar, modificar, vender, distribuir.**
> *   **Não precisa abrir o código** se alguém usar seu projeto
> *   Só exige que mantenha seu nome e a licença no projeto
> 
> **Boa para quem quer liberdade total para os outros usarem seu código**
> 
> **🛡️ GNU GPLv3 (Licença forte, “contagiosa”)**
> 
> *   **Pode usar e modificar**, mas se alguém **modificar e distribuir**, **tem que abrir o código também**
> *   Protege contra empresas que queiram usar seu código sem compartilhar melhorias
> 
> **Boa para quem quer garantir que o código sempre continue livre**
> 
> **🏛️ Apache License 2.0 (Permissiva com proteção de patentes)**
> 
> *   Parecida com a MIT (pode usar, modificar, vender)
> *   **Inclui proteção legal contra patentes**
> 
> **Boa para projetos comerciais, sem exigir que modifiquem o código-fonte**

# **Dicas**

### **Abrir VsCode**

No GitHub Desktop, ao clicarmos em Open in Visual Studio Code, o VS Code será aberto diretamente na pasta exata do repositório, de forma fácil e simples

---

### **Como saber se o arquivo foi incluido?**

Quando é criado um arquivo novo no projeto, ele vai ser marcado em verde, acusando um **U** verde, que significa _Untracked_

Arquivos **untracked** são arquivos que:

*   Estão presentes na pasta do repositório
*   Mas **ainda não foram adicionados ao controle de versão** (ou seja, o Git não os está monitorando)

Tudo é indicado no GitHub Desktop também logo que ele identifica uma inclusão

---

### **Como sabemos se o projeto foi modificado?**

*   Toda alteração feita no repositório é marcada com um **"M" laranja** e também é identificada na aba **Source Control** do VS Code
*   Se abrirmos o GitHub Desktop, ele vai mostrar as alterações feitas
*   No GitHub Desktop no campo _Changes_ vai indicar a quantidade de mudanças, no caso, 1 mudança ou mais
*   Linhas em vermelho representam o que havia anteriormente, e linhas em verde são as que foram adicionadas no GitHub Desktop

# Estados de registro de arquivos

### **Estados**

*   U (Untracked): Arquivo novo, não está sendo rastreado pelo Git ainda
*   A (Added): Arquivo foi adicionado ao stage com git add, mas ainda não foi commitado
*   M (Modified): Arquivo foi modificado em relação ao último commit
*   D (Deleted): Arquivo foi excluído
*   R (Renamed): Arquivo foi renomeado
*   C (Copied): Arquivo foi copiado