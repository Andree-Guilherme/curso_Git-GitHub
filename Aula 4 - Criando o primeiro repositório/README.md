# Aula 5 | Criando o primeiro repositório

### **Criando o repositório local e remoto**

1.  Para criar um repositório local, abrimos o GitHub Desktop e selecionamos a opção 'repositório local no disco'
2.  Em seguida, será exibida uma tela para preencher os dados de criação do repositório:

*   **Campos:**
    *   **Name** — Nome do repositório
    *   **Description** — Descrição do repositório (opcional)
    *   **Local path** — Caminho local onde o repositório será criado
    *   **Initialize this repository with a README** — Opção para iniciar o repositório com um arquivo README
    *   **Git ignore** — Seleção do arquivo `.gitignore` para o projeto (lista suspensa)
    *   **License** — Escolha da licença do projeto (lista suspensa)
*   **Botões:**
    *   **Create repository** — Criar o repositório
    *   **Cancel** — Cancelar a criação

1.  A tela inicial será aberta novamente
2.  Para publicarmos no servidor (GitHub), devemos clicar no botão Publish repository
3.  Ao clicar nesse botão será abeto uma tela com os seguintes campos

*   **Campos**
    *   **Name:** Nome do repositório que será publicado no GitHub
    *   **Description:** Texto opcional que descreve o propósito ou conteúdo do repositório
    *   **Keep this code private:** Define se o repositório será privado (acesso restrito) ou público (acesso aberto)
    *   **Organization:** Permite escolher uma organização do GitHub vinculada à sua conta, se houver
*   **Botões:**
    *   **Publish repository:** Botão para iniciar a publicação do repositório no GitHub
    *   **Cancel:** Cancela a operação e fecha a janela

1.  Posteriormente, ao acessarmos a página do GitHub, o repositório **irá aparecer lá**

Este processo criará uma pasta no caminho indicado, que servirá de repositório local, e ao clicar em "Publish", esse repositório local será enviado para o repositório remoto — GitHub.

---

### **Versionando localmente e enviando inserções ou alterações para o GitHub**

1.  Com o VsCode aberto quando fazemos alguma inserção ou alteração o GitHub Desktop encontrara automaticamente a atualização
2.  Para versioná-las, precisamos ir à área de commit
3.  Temos que adicionar um título para esse commit e uma descrição. Por fim, clicar em **commit**
4.  Ao clicar em **commit**, estamos enviando as alterações para o Git (criando um versionamento dentro do Git) — ou seja, registramos a alteração localmente, dentro da própria máquina
5.  A ação de enviar o código para o GitHub é chamada de **push.** Para fazer isso, basta clicar no botão **Push**, que será habilitado logo após o commit

---

*   Toda vez que houver uma alteração feita pelo site, por outra máquina ou por qualquer outro meio que não esteja atualizada na máquina que você está usando, clicamos em **Fetch Origin** para que ele busque se houve alguma alteração
*   Caso o GitHub Desktop encontre alguma alteração feita em outra máquina ou no site, ele vai avisar e recomendar um **pull** para baixar e incorporar essas mudanças. Assim, seu repositório local fica atualizado e sincronizado com o remoto