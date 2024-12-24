# Void Docs

Welcome to the Void documentation. This repository contains the source data
behind <https://docs.voidlinux.org/>. Contributing to this repository follows
the same protocol as the packages tree. For details, please read
[CONTRIBUTING](./CONTRIBUTING.md).

## Building

The [res/build.sh](./res/build.sh) script builds HTML, roff and PDF versions of
the Void documentation and the `void-docs.1` man page. It requires the following
Void packages:

- `mdBook`
- `findutils`
- `pandoc`
- `texlive`
- `perl`
- `perl-JSON`
- `librsvg-utils`

In order to build and install these files, set the `PREFIX` and `DESTDIR`
environment variables to appropriate values and run `res/build.sh` followed by
`res/install.sh`.

=======================================================================================

# Documentação do Void

Bem-vindo à documentação do Void. Este repositório contém os dados de origem
por trás de <https://docs.voidlinux.org/>. Contribuir para este repositório segue
o mesmo protocolo da árvore de pacotes. Para detalhes, leia
[CONTRIBUTING](./CONTRIBUTING.md).

## Construindo

O script [res/build.sh](./res/build.sh) constrói versões HTML, roff e PDF
da documentação do Void e da página de manual `void-docs.1`. Ele requer os seguintes
pacotes Void:

- `mdBook`
- `findutils`
- `pandoc`
- `texlive`
- `perl`
- `perl-JSON`
- `librsvg-utils`

Para compilar e instalar esses arquivos, defina as variáveis ​​de ambiente `PREFIX` e `DESTDIR`
para valores apropriados e execute `res/build.sh` seguido por
`res/install.sh`.
