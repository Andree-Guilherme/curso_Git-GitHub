# Merge

### Conflitos de merge no Git
Quando, por exemplo, o responsável pelo __conteúdo__ altera uma linha e, ao mesmo tempo, o responsável pelo __design__ também faz uma alteração __na mesma linha__, ocorre o que chamamos de um __conflito__ na hora de fazer o merge das branches

O Git não consegue decidir sozinho qual das versões manter, então será necessário __resolver o conflito manualmente__, escolhendo qual alteração deve prevalecer (ou combinando as duas)

---

### Como fazer um merge no GitHub Desktop
1. Selecione a branch principal, ou seja, a branch onde as outras serão integradas (geralmente __master__ ou __main__)
2. Vá até o menu __Branch__ no GitHub Desktop
3. Clique na opção __Merge into Current Branch__
4. Escolha a branch que deseja unir à branch atual
5. Será exibida uma tela com as branches disponíveis para merge
6. Selecione a branch desejada para iniciar o merge
7. Se não houver conflitos, o merge será realizado automaticamente
8. Clique na confirmação para concluir o processo de merge

---

### Como resolver conflitos de merge no GitHub Desktop
1. Ao tentar realizar um merge, se houver conflitos, o GitHub Desktop exibirá um alerta informando que os conflitos precisam ser resolvidos manualmente
2.Após clicar para iniciar o merge, aparecerá uma tela destacando os arquivos com conflitos que precisam ser resolvidos
3. Clique no botão para abrir os arquivos com conflito no Visual Studio Code diretamente da tela do GitHub Desktop
4. No VS Code, a interface especial de conflitos mostrará:
   1. A branch atual (marcada como __HEAD__)
   2. A outra branch que está sendo mesclada
5. Edite os trechos conflitados para escolher qual versão manter ou combine as duas, resolvendo o conflito manualmente
6. Na parte superior do trecho conflitado, o VS Code exibirá abas para facilitar a resolução:
* __Accept Current Change__ – Aceita a alteração da branch atual (HEAD)
* __Accept Incoming Change__ – Aceita a alteração da outra branch
* __Accept Both Changes__ – Mantém as duas versões, combinando o conteúdo
* Compare Changes – Permite visualizar e comparar as diferenças entre as versões
7. Clique na opção desejada para aplicar a resolução do conflito
8. Após resolver todos os conflitos, salve os arquivos modificados no VS Code
9. Volte ao GitHub Desktop, onde aparecerá a opção __Mark as resolved__ (Marcar como resolvido). Clique nela
10. Por fim, clique em Commit merge para concluir o processo de merge com sucesso

---

### Como excluir uma branch no GitHub Desktop
1. Clique na aba __Branch__ no menu superior
2. Selecione a opção __Delete__
3. Será exibida uma nova tela com uma caixa de seleção __(Yes, delete this branch on the remote)__
4. Marque a caixa para excluir a branch também no repositório remoto, se desejar
5. Confirme a exclusão para remover a branch