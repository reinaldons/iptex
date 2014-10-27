# IPTeX

Template de formatação LaTeX para dissertações do Instituto de Pesquisas Tecnológicas do Estado de São Paulo (IPT). Esse template deve ser usado em conjunto com o abnTeX2.

## Como usar

Para usá-lo basta incluir no preâmbulo de seu documento .tex:

    \usepackage{iptex}
    
## Arquivo exemplo

O arquivo-exemplo.tex localizado no diretório raiz, é um arquivo auto explicativo e deve ser utilizado em sua dissertação, pois nele está contido configurações necessárias não inseridas no template de formatação.

### Instalando as fontes Arial

    $ wget -q http://tug.org/fonts/getnonfreefonts/install-getnonfreefonts
    $ sudo texlua ./install-getnonfreefonts
    $ getnonfreefonts arial-urw

### Instalando o LaTeX e abnTeX2

#### Debian, Ubuntu e derivados

Para uma instalação completa:

    sudo apt-get install texlive-full

Para uma instalação apenas dos pacotes necessários pelo abnTeX2:

    apt-get install texlive-publishers texlive-lang-portuguese texlive-latex-extra texlive-fonts-recommended

#### Arch Linux

Para uma instalação apenas dos pacotes necessários pelo abnTeX2:

    $ yaourt -S texlive-core texlive-latexextra
    $ yaourt -S abntex2

Para um texto com mais detalhes sobre a instalação do LaTeX: [Orientações de instalação do LaTeX e do abnTeX2](https://code.google.com/p/abntex2/wiki/Instalacao)
