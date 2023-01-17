# Listas

## Ordenadas
* Indica uma lista ordenada por números ou letras.
* Para isso utilizamos a tag "ol" para criar a lista, e cada item da lista é indicado pela tag "li"

        <ol>
            <li>HTML</li>
            <li>CSS</li>
            <li>JS</li>
        </ol>

* Podemos passar um atributo "type" para a tag <ol> para indicar o tipo de ordenação que queremos.

1. type = "1" - lista por números
2. type = "A" - lista por letras maiúsculas
3. type = "a" - lista por letras maiúsculas
4. type = "I" - lista por letras maiúsculas
5. type = "i" - lista por letras maiúsculas

        <ol type = "A">
            <li>HTML</li>
            <li>CSS</li>
            <li>JS</li>
        </ol>

## Não Ordenadas

* Parecida com a lista anterior, mas sem identificadores.

        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JS</li>
        </ul>

* Utilizada para criar Menus

## Listas de Descrição

* Essas listas são formadas pela tag "dl", e nelas a gente indica o nome de um termo("dt") e depois listamos descrições sobre esse termo("dd");

        <dl>
            <dt>HTML</dt>
            <dd>- HyperText Markup Language</dd>
        </dl>

## Progress e Meter

* Podemos representar o progresso de algum processo com a tag de progresso. Passamos o vaor total do progresso no atributo "max", e l valor do progresso em "value".

        <progress value = "30" max = "100"></progress>

* Podemos ter algo parecido com a tag "meter". Tambppem podemos indicar quais valores são considerados altos e baixos com os atributos high e low.

        <meter value = "30" max = "100" min = "0"></meter>


