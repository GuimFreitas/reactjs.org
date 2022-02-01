

Em GitHub, acesse o repositório do seu site.

Decide which publishing source you want to use. For more information, see "About GitHub Pages."

Se a fonte de publicação que você escolheu já existe, navegue até ela. Caso contrário, crie a fonte de publicação.

Na raiz da fonte de publicação, crie um novo arquivo chamado index.md com o conteúdo que você deseja exibir na página principal do seu site.

Dica: se index.html estiver presente, ele será usado ao invés de index.md. Se nem index.html nem index.md estiverem presentes, será usado README.md.

Configure a sua fonte de publicação. Para obter mais informações, consulte "Configurar uma fonte de publicação para seu site do GitHub Pages".

No nome do seu repositório, clique em

Configurações. Botão de configurações do repositório

In the "Code & operations" section of the sidebar, click

    Pages.

    Opcionalmente, se você estiver publicando um site de projeto de um repositório privado ou interno pertencente a uma organização que usa GitHub Enterprise Cloud, escolha a visibilidade do seu site. Em "GitHub Pages", selecione o visibilidade de GitHub Pages no menu suspenso e, em seguida, clique em uma visibilidade. Para obter mais informações, consulte "Alterar a visibilidade do seu site de GitHub Pages". Menu suspenso para selecionar visibilidade para o seu site

    Para ver seu site publicado, em "GitHub Pages", clique na URL do seu site. URL do seu site publicado

    Observação: podem ser necessários até 10 minutos para que as alterações no site sejam publicadas após o push delas no GitHub. If you don't see your GitHub Pages site changes reflected in your browser after an hour, see "About Jekyll build errors for GitHub Pages sites."

    If your GitHub Pages site is built from a public repository, it is built and deployed with a GitHub Actions workflow run unless you've configured your GitHub Pages site to use a different CI tool. For more information about how to view the workflow status, see "Viewing workflow run history."

Note: GitHub Actions workflow runs for your GitHub Pages sites are in public beta for public repositories and subject to change. GitHub Actions workflow runs are free for public repositories.

Note: If your site has not published automatically, make sure someone with admin permissions and a verified email address has pushed to the publishing source.
Próximas etapas

Você pode adicionar mais páginas ao seu site criando novos arquivos. Cada arquivo ficará disponível no site na mesma estrutura de diretórios que a fonte de publicação. Por exemplo, se a fonte de publicação do site de projeto for o branch gh-pages e você criar um arquivo chamado /about/contact-us.md no branch gh-pages, o arquivo novo ficará disponível em https://<user>.github.io/<repository>/about/contact-us.html.

Também é possível adicionar um tema para personalizar a aparência do site. Para obter mais informações, consulte "Adicionar um tema ao site do GitHub Pages com o seletor de temas".

Para personalizar seu site ainda mais, você pode usar o Jekyll, um gerador de site estático com suporte integrado para o GitHub Pages. Para obter mais informações, consulte "Sobre o GitHub Pages e o JJekyll".
