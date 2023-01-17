# Links e Ancoras

## Links

* Ligar um conteúdo a outro, quando clicado ele faz comunicação para o link e direciona para a página.

* Usar os links sempre que quisermos fazer uma referência a um outro conteúdo, apontando para outro arquivo ou seção do texto.

* Podemos criar arquivos como index.html, home.html, projetos.html e contato.html, entre outros

* Com esses arquivos prontos, podemos criar âncoras, que serão exibidos pelo navegador assim que o usuário clicar no link referente

* Para isso passamos o nome do arquivo no atributo "href".

        <a href = "home.html">Home</a>
        <a href = "projetos.html">Projetos</a>

* Por padrão links sempre serão abertos na mesma guia

* Para abrit em uma nova aba/janela, passamos o atributo target com o valor "_blank"

        <a href = "projetos.html" target = "blank">Projetos</a>

## Âncoras

* A criação de âncoras na página ajuda o usuário quando o estver em uma página muito grande, e ao clicar em um link a página irá rolar até o conteúdo marcado com a âncora.

* Para que isso aconteça, é necessário passar um atributo "id" com um nome para o elemento que se quer localizar, e passar esse nome no href com "#".

