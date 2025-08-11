# Git Branches

### Branch (Ramo)
"Branch" significa __ramo__, e quando pensamos em ramos, logo lembramos de árvores — é exatamente essa a ideia que devemos ter ao ouvir falar de __branches no Git__

>Por exemplo:
>    "Vai lá no seu Git, cria uma branch e faz uma feature nessa branch."

No Git, a estrutura funciona como uma árvore. Temos o __tronco principal__, que chamamos de __branch master__ (ou main, dependendo da configuração). Essa branch representa o __ramo de produção__, ou seja, o __produto final__ ou a __versão estável__ do software

>Exemplo 1

> Se temos um software na versão 4.0 (estável), mas há pessoas trabalhando em melhorias ou novas funcionalidades para a versão 4.5 ou 5.0, essas alterações devem ser feitas em branches separadas. Depois de testadas e aprovadas, essas branches podem ser unidas à principal por meio de um merge

>Exemplo 2

>Se alguém encontra um erro ou abre uma Issue relatando um problema, podemos criar uma branch específica para corrigir esse defeito. Após corrigido, fazemos o commit e um merge dessa branch de correção para a branch principal (master), garantindo que o produto final seja atualizado com a solução

---

* Sempre que criamos um repositório, é obrigatório ter um ramo principal, chamado __master__ (ou __main__ em repositórios mais recentes). Esse é o __ramo padrão__ onde as alterações principais são registradas

* Sempre que fazemos uma modificação nesse ramo, realizamos um __commit__ — ou seja, salvamos essa alteração com um rótulo (mensagem). Cada __commit__ representa uma __nova subversão__, ou seja, um __novo ponto no versionamento do projeto__

A qualquer momento, podemos __enviar esse conteúdo da branch master para a origin__
Quando usamos o comando git push, __estamos enviando (ou "empurrando") uma cópia do repositório local para o repositório remoto__

__Tecnicamente falando, isso é chamado de:__
> __"fazer um push para a origin"__

* A origin é o repositório remoto, geralmente no GitHub
* É como se fosse um backup do seu projeto hospedado na nuvem
* Já o repositório local é o que está na sua máquina

Resumindo:

• Cada __novo commit__ gera uma nova versão

• No final do dia (ou quando decidirmos), usamos o comando __push para enviar todos os commits para a origin__, garantindo que o projeto remoto esteja atualizado

---

Devemos __evitar fazer commits diretamente na branch principal (master ou main)__. Para isso, o ideal é criar novas branches sempre que formos desenvolver algo novo

> Por exemplo:
> Se formos desenvolver o __design de uma página__, criamos uma __nova branch específica para essa feature__. O mesmo vale para qualquer outra funcionalidade

As alterações feitas nessa branch acontecem __paralelamente à branch master__. À medida que vamos realizando os __commits__ na branch paralela, chega um momento em que queremos __unir essa branch com a principal__. Isso é feito usando o comando git merge — que significa junção. O Git então __integra o conteúdo da branch paralela à master__

Se, em outro momento, precisarmos desenvolver outra feature (por exemplo, do __backend__), também podemos criar uma nova branch sem problema algum. E caso os testes ou o planejamento __não deem certo__, podemos simplesmente __apagar essa branch__, sem afetar a master

---

### Como criar uma nova branch no GitHub Desktop
1. Abra o __GitHub Desktop__
2. Clique em __Branches__ no menu superior
3. Selecione __New Branch__
4. Insira o nome desejado para a nova branch
5. Confirme a criação da branch
6. O GitHub Desktop irá sugerir que você publique a branch, enviando-a do repositório local para o repositório remoto no GitHub

* Caso criemos outra branch, o processo será o mesmo, porém o GitHub Desktop solicitará em qual branch existente a nova será baseada — ou seja, de qual ponto do projeto a nova branch irá partir

---

### Confirmando a branch antes do commit
Ao fazer alterações no código, devemos __nos certificar de que estamos na branch desejada__ no GitHub Desktop. Assim que o GitHub Desktop detectar as alterações, elas __aparecerão automaticamente__, permitindo que a gente __faça o commit diretamente na branch selecionada__

---

### Atualização instantânea no editor ao mudar de branch
Quando mudamos a __branch no GitHub Desktop__, o conteúdo do projeto é __automaticamente atualizado no Visual Studio Code__ (ou no editor que estiver sendo usado), refletindo os arquivos e versões correspondentes à branch selecionada

