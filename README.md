# Project-Model
### Instruções
1. Faça um **Fork** deste repositório;
2. Clone localmente: `git clone https://github.com/SEU_USERNAME/projeto-modelo`;
3. Adicione o remote upstream para manter seu repositório local atualizado: `git remote add upstream https://github.com/kartulle/projeto-modelo`;
    > Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch `main` deste repositório original de onde você fez o fork, ou `git fetch upstream main` para baixar sem mesclar. Veja mais em: [Primeiros Passos com Git e GitHub](https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/03-primeiros-passos-com-git-e-github.md).
4. Crie uma nova **branch** e nomeie como `feat/collaborators/SEU_USERNAME`:
    > Exemplo: `git checkout -b feat/collaborators/kartulle`
5. Dentro da pasta [`collaborators`](https://github.com/kartulle/projeto-modelo/tree/main/collaborators), crie um arquivo em Markdown (extensão `.md`) e nomeie com o mesmo nome do seu usuário no GitHub;
    > Exemplo: `collaborators/kartulle.md` <br>
6. Adicione suas alterações à "staging area" com o comando `git add collaborators/SEU_USERNAME.md`;
    > **Observação:** Você pode utilizar o comando `git add .` para adicionar todas as alterações de uma vez só.
7. Crie um commit e adicione a mensagem indicando a adição do seu perfil `git commit -m"feat: add SEU_USERNAME profile"`;
    > **Observação:** Verificar a [`Convenção de Commits`](https://github.com/kkademorais/projeto-modelo/blob/main/CONTRIBUTING.md#conven%C3%A7%C3%A3o-de-commits) para escrever a mensagem do seu commit de forma clara e padronizada.
8. Envie as alterações para o seu repositório remoto `git push origin feat/collaborators/SEU_USERNAME`;
    > **Observação:** Você pode utilizar o comando `git push origin` para mandar as alterações sem precisar especificar a URL, desde que você tenha feito o passo **3**. 
9. Crie um **Pull Request**.
    > **Observação**: No geral, quando você der um push para o seu repositório do Github, ele perguntará para você se deseja fazer um Pull Request. Caso não apareça, é só você ir para o repositório principal, clicar em Pull Request e Create, e por último indicar o seu repositório e a branch em específico.
    > Se tudo estiver certo, irá aparecer um template, que contém botões de múltipla escolha referente ao seu tipo de alteração, checklist e também comentários adicionais se você achar que seja bom acrescentar. Assim, quando você concluir, é somente você apertar o "Create Pull Request" que fica abaixo dessa caixa de texto e esperar a resposta do bot do Github Actions dizendo se seu PR (Pull Request) foi aceito ou não.
    > Em caso de aprovação o bot irá liberar e o projeto estará pronto para codar.
    
## <img src="https://user-images.githubusercontent.com/74038190/206662607-d9e7591e-bbf9-42f9-9386-29efc927bc16.gif" width="30px" height="30px"> Convenção de Commits 

| Tipo de Commit | Descrição                                                            | Exemplo
| ---------------|----------------------------------------------------------------------|-----------
| `feat`         | Adiciona uma nova funcionalidade ao projeto.                         | `feat: add USENAME.md profile`
| `fix`          | Corrige um bug ou problema no projeto.                               | `fix: fixed issue fix#IssueNumber`
| `docs`         | Altera a documentação do projeto. Ex.: README, comentários no código.| `doc: altered section SECTIONNAME`
| `style`        | Realiza mudanças na aparência, sem alterar a funcionalidade.         | `style: add EFFECTNAME to COMPONENT`
| `refactor`     | Realiza mudanças no código que não alteram a funcionalidade.         | `refactor: refactor at CLASSNAME`
| `test`         | Adiciona ou modifica testes no projeto.                              | `test: testing FUNCIONALITYNAME`
