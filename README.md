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

Carlos Frederico Bastarz (carlos.bastarz@inpe.br)
