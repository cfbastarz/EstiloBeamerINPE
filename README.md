# EstiloBeamerINPE

Exemplo de template de apresentações do INPE (2021) utilizando o pacote Beamer do LaTeX.

## Uso

Para utilizar, basta abrir o arquivo `estilo_inpe_beamer.tex` e adicionar os frames necessários. Utilize os arquivos `estilo_inpe_beamer_pacotes.tex` e `estilo_inpe_beamer_macros.tex` para adicionar os seus pacotes e macros, respectivamente. O estilo (tema) dos slides, está definido (em boa parte) no arquivo `estilo_inpe_beamer_tema.tex`.

## Exemplos de Uso

* Apresentação ["Matriz de Covariâncias dos Erros de Previsão (Matriz B)"](https://github.com/cfbastarz/WorkshopAD-DIMNT2022/blob/main/matriz_B-cfbastarz/matriz_B-cfbastarz.pdf);
* Apresentação ["Assimilação de dados Híbrida visando a Previsão por Conjunto"](https://github.com/cfbastarz/WorkshopAD-DIMNT2022/blob/main/ensemble-cfbastarz/ensemble-cfbastarz.pdf).

## Compilação

    xelatex estilo_inpe_beamer.tex

Se forem adicionadas referências bibliográficas com `bibtex`, compile o documento da seguinte forma:

    xelatex estilo_inpe_beamer.tex
    bibtex estilo_inpe_beamer
    xelatex estilo_inpe_beamer.tex
    xelatex estilo_inpe_beamer.tex

## Overleaf

Um snapshot deste estilo do Beamer para as apresentações do INPE também pode ser encontrado no overleaf em https://www.overleaf.com/latex/templates/estilobeamerinpe-v1-dot-2/bbjshzqyfbjp

Carlos Frederico Bastarz (carlos.bastarz@inpe.br)
