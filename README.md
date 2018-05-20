# OpenAAC
- Para utilização do OpenACC é necessário possuir a versão 7 para cima do gcc.

## Instalação Windows
  
  1) Instalar o GCC pelo executavel [daqui](https://sourceforge.net/projects/mingw-w64/) (Versão 7.3.0)

  2) Caso ocorra algum erro na instalação anterior, baixar [este arquivo](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win32/Personal%20Builds/mingw-builds/7.3.0/threads-posix/dwarf/), e extrair em alguma pasta de seu interesse. 

  3) Após ter feito algum dos dois, entrar na pasta criada e depois na pasta bin
  Ex: C:\mingw32\bin

  4) Apertar Windows + R, e digitar sysdm.cpl

  5) Na tela que abriu, na aba avançado ir em variaveis de ambiente

  6) Na parte de variaveis do sistema, encontrar o 'Path', selecionar e clicar em editar
  - Caso você ja possua alguma versão anterior do GCC, por gentileza remover ela do Path para evitar conflitos.

  7) Adicionar o caminho para a pasta bin do item 3


## Instalação no Linux

não sei ainda


## Execução

gcc -fopeanacc nomedoarquivo.c
