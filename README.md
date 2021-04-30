# EstiloBeamerINPE

Exemplo de template de apresentações do INPE (2021) utilizando o pacote Beamer do LaTeX.

## Uso

Para utilizar, basta abrir o arquivo ``estilo_inpe_beamer.tex`` e adicionar os frames necessários. 

## Compilação

    xelatex estilo_inpe_beamer.tex

Se forem adicionadas referências bibliográficas com ``bibtex``, compile o documento da seguinte forma:

    xelatex estilo_inpe_beamer.tex
    bibtex estilo_inpe_beamer
    xelatex estilo_inpe_beamer.tex
    xelatex estilo_inpe_beamer.tex

## Overleaf

Um snapshot deste estilo do Beamer para as apresentações do INPE também pode ser encontrado no overleaf em https://www.overleaf.com/latex/templates/estilobeamerinpe/bbjshzqyfbjp

Carlos Frederico Bastarz (carlos.bastarz@inpe.br)
