# Aula 3 | A Evolução do Git e GitHub

### **Quem veio primeiro?**

Para entendermos que veio primeiro (GIT ou GitHub) precisamos falar um pouco sobre a história

---

### **Entendendo a história**

**1985 — CVS (Concurrent Version System (Sistema de Versões Concorrentes))**

*   Centralizado
*   Open Source
*   Mais popular
*   Alguns problemas - (Não permitia renomear arquivos - Não permitia mover arquivos para outras pastas - Em alguns casos demorava de 3 a 4 minutos para fazer um commit)

**2000 — SVN (Subversion (Subversão))**

*   Centralizado
*   Open Source
*   Ativo até hoje
*   CVS-like
*   O SVN era muito parecido com o CVS porém tinha a proposta de resolver problemas do CVS
*   Projeto ainda ativo da fundação Apache
*   SVN tinha um problema que queria ser muito igual ao CVS

# BitKeeper

**2000 — BitKeeper**

*   Distribuído
*   Proprietário
*   Versão comunidade
*   CVS-free - (Bitkeeper era CVS-free ou seja, tentava ser totalmente diferente do CVS)

**2000 — BitKeeper**

> Larry McVoy, antes de fundar a empresa BitMover, participou de um grande projeto: o desenvolvimento do kernel do Linux. Posteriormente, ele criou a BitMover, responsável pela ferramenta BitKeeper, que era uma solução proprietária de controle de versões. Apesar de querer lucrar com o BitKeeper, McVoy também buscava aproximar a comunidade open source, oferecendo uma versão gratuita com algumas limitações, como restrições no acesso a metadados sensíveis

> Na época, o maior "cliente" dessa versão comunitária era justamente o projeto do Linux, que utilizava o BitKeeper para disponibilizar o código-fonte do kernel. O problema começou quando a comunidade se deu conta da contradição ideológica: utilizar uma ferramenta proprietária para distribuir um núcleo totalmente livre. Isso desagradou figuras importantes do movimento software livre, como Richard Stallman, que alertou Linus Torvalds sobre os riscos futuros dessa dependência

> No entanto, Linus Torvalds, conhecido por seu estilo direto e irônico, minimizou a preocupação e respondeu que aquilo não era um problema e que poderiam simplesmente "ir empurrando com a barriga"

> Em 2004, a situação ficou ainda mais tensa. Andrew Tridgell, um desenvolvedor conhecido na comunidade de software livre, criou uma ferramenta chamada **SourcePuller**, que funcionava como um cliente para acessar repositórios do BitKeeper. Para desenvolver essa ferramenta, Andrew utilizou engenharia reversa e acabou descobrindo uma forma de desbloquear recursos que a versão comunitária do BitKeeper não permitia acessar

> Larry McVoy não gostou nada disso e a briga começou. Andrew trabalhava na época na **OSDL (Open Source Development Labs)**, uma organização que apoiava projetos open source, incluindo o próprio Linux. McVoy acusava Andrew de estar roubando seu código, enquanto Andrew defendia que apenas havia criado um cliente para se comunicar com o BitKeeper, sem violar o software em si

> No início de 2005, a BitMover endureceu ainda mais as regras: lançou uma nova licença do BitKeeper que bloqueava ainda mais o acesso a informações, como os metadados e o histórico de alterações (diffs). Esses recursos só estariam disponíveis na versão paga. Na prática, a mensagem para a comunidade era clara: **"Se querem acesso total, terão que pagar."**

> Linus Torvalds, que até então usava o BitKeeper sem grandes preocupações, ficou indignado com a mudança. Richard Stallman já havia alertado sobre os riscos dessa dependência de uma ferramenta proprietária para gerenciar o código-fonte de um projeto livre, e agora essa previsão se concretizava

> Com a situação insustentável, Linus respondeu de forma direta: **"Se você vai bloquear meu acesso, eu mesmo crio uma alternativa."** E foi assim que, ainda em 2005, Linus Torvalds criou o **Git**, um sistema de controle de versões totalmente gratuito e open source, justamente para acabar com essa dependência e evitar que o Linux passasse por esse tipo de problema novamente

**O nascimento do Git se deu a partir da raiva e indignação de Linus Torvalds**

*   Veja como as emoções de um programador insatisfeito com sistemas proprietários foram o ponto de partida para a criação de uma das ferramentas mais revolucionárias no controle de versão

# Git

### **O que significa GIT?**

Quando perguntavam a **Linus Torvalds** o significado do nome **Git**, ele costumava dar respostas diferentes, sempre com seu conhecido tom irônico e bem-humorado

As explicações mais comuns eram as seguintes:

*   **Na forma mais simples e direta**, Linus dizia que **"Git são apenas três letras do alfabeto que, juntas, formam uma palavra curta e fácil de pronunciar."** Ele também brincava que escolheu esse nome justamente por ser um comando pequeno e que não era utilizado por nenhum sistema Unix-Like até então
*   **Em tom irônico**, Linus explicava que **"Git" é uma gíria inglesa para uma pessoa teimosa, cabeça dura — alguém que pode ser irritante, mas que geralmente está certo**
*   **Em um dia bom**, ele dizia que **"Git" poderia significar "Global Information Tracker"** (Rastreador Global de Informações), como se fosse uma sigla importante e imponente
*   **Em um dia ruim**, especialmente quando algo dava errado com o próprio Git, Linus brincava dizendo que Git significava **"Goddamn Idiotic Truckload of Shit"** (algo como "Maldito Monte de Merda Idiota")

### **Figuras**

![Larry McVoy](https://marc.merlins.org/linux/lwce_summer99/Misc/102_misc.jpg)

**Larry McVoy**: Criador do BitKeeper e fundador da BitMover; tentou lucrar com software proprietário usado pelo Linux

![Linus Torvalds](https://antlia.com.br/wp-content/uploads/2023/08/Linus.jpg)

**Linus Torvalds**: Criador do Linux; abandonou o BitKeeper e criou o Git após perder acesso à ferramenta

![Richard Stallman](https://ufpr.br/wp-content/uploads/2017/06/34990611891_1163a9253f_z.jpg)

**Richard Stallman**: Líder do software livre; alertou contra o uso de ferramentas proprietárias no projeto Linux

![Andrew Tridgell](https://i0.wp.com/www.suasnews.com/wp-content/uploads/2015/02/tridge.jpg?resize=490%2C450&ssl=1)

**Andrew Tridgell**: Desenvolvedor do SourcePuller; usou engenharia reversa no BitKeeper, gerando conflito com McVoy

# GitHub

### **Como surgiu o GitHub?**

**2008 – GitHub**

*   Proprietário
*   Hospedagem de código
*   Baseado em **Git**

**2009**: 46k repositórios  
**2010**: 100k users / 1M repositórios  
**2011**: Ultrapassou **SourceForge**  
**2013**: 3M users / 5M repositórios  
**2016**: 14º lugar na lista da **Forbes**  
**2018**: **Sofreu o maior ataque de DDoS da história** – Foi tão resistente que só parou de funcionar quando o tráfego chegou a **1,35 Tbps**, derrubando o **GitHub por cerca de 8 minutos**

*   Adquiridos pela **Microsoft**
*   **US$ 7.5 BILHÕES**
*   Operação independente
*   **2020**: GitHub compra a **npm**

> Muita gente não gostou quando a **Microsoft comprou o GitHub**, alegando que seus códigos estariam nas mãos de uma empresa "mal-intencionada" e que poderia haver riscos de privacidade ou abuso

> No entanto, essa visão não condizia com a realidade. Antes mesmo da compra, a **Microsoft já era uma das maiores contribuidoras de projetos open source** e utilizava ativamente o próprio GitHub para hospedar seus projetos de código aberto. Alguns exemplos incluem:
> 
> *   **PowerShell** (terminal e automação do Windows)
> *   **Visual Studio Code** (editor de código-fonte)
> *   **Windows Terminal** (terminal moderno do Windows)
> *   **Chakra** (motor JavaScript que foi utilizado no Microsoft Edge)

> Após a compra, a Microsoft garantiu que o **GitHub continuaria operando de forma independente**, permitindo que seus desenvolvedores mantivessem o foco na comunidade e na melhoria da plataforma

> Além disso, em **2020, a Microsoft também adquiriu o NPM**, reforçando ainda mais sua presença no ecossistema de desenvolvimento open source

### **Figuras**

**![Chris Wanstrath](https://buildd.co/rails/active_storage/representations/redirect/eyJfcmFpbHMiOnsiZGF0YSI6NTQxMiwicHVyIjoiYmxvYl9pZCJ9fQ==--e520927f2010200136922461f4872eb7384830f4/eyJfcmFpbHMiOnsiZGF0YSI6eyJmb3JtYXQiOiJqcGciLCJyZXNpemVfdG9fbGltaXQiOls0MDAsNDAwXX0sInB1ciI6InZhcmlhdGlvbiJ9fQ==--30fcfcea9988ccdd3e334ecf4c3a03b06f8fbf04/Chris_Wanstrath.jpg)**

**Chris Wanstrath:** Co-fundador e depois CEO do GitHub. Participou da gestão até a aquisição pela Microsoft

**![](https://imageio.forbes.com/specials-images/imageserve/5c74515731358e35dd273053/0x0.jpg?format=jpg&crop=512,512,x0,y0,safe&height=416&width=416&fit=bounds)**

**Tom Preston-Werner:** Criador da ideia original do GitHub. Trabalhou também na criação do Jekyll (gerador de sites estáticos) (criador do Gravatar)

**![](https://sessionize.com/image/288a-400o400o2-9c81MquPv1fmZRqcbLyiTW.jpg)**

**Scott Chacon:** Escreveu a primeira documentação oficial do Git. Teve papel importante na evangelização do GitHub; às vezes citado como co-fundador ou membro-chave inicial

![](https://avatars.githubusercontent.com/u/3?v=4)

**PJ Hyett:** Co-fundador, atuou como desenvolvedor e líder técnico

### **O que é esse mascote do GitHub?**

*   O mascote do GitHub é conhecido como **Octocat** (ou "Octopus Cat"), um polvo com cabeça de gato, com traços antropomorfizados
*   Quem criou o desenho original foi o artista **Simon Oxley**. Curiosamente, a comunidade descobriu que Simon também foi o criador do famoso **Larry the Bird**, o mascote inicial do **Twitter**, que era uma homenagem ao jogador de basquete **Larry Bird**.
*   Simon Oxley costumava vender suas ilustrações em bancos de imagens, como o **iStock**, e foi justamente lá que a equipe do GitHub encontrou e escolheu o **gato-polvo** para ser o mascote da plataforma. O desenho caiu tão bem que acabou se tornando a icônica identidade visual do GitHub

### **Figura**

**![](https://www.uktech.news/wp-content/uploads/2013/10/screen-shot-2013-07-08-at-4-55-16-pm.png)**

**Simon Oxley:** Designer responsável pela criação do icônico logo do GitHub — o “Octocat”