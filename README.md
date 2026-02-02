Repositório oficial do Editor de Texto NotepadNext no GitHub:

https://github.com/dail8859/NotepadNext


Tradução revisada por marcelocripe:

https://github.com/marcelocripe/NotepadNext_pt_BR/


Para utilizar o arquivo "NotepadNext.desktop" ou "notepadnext_deb_package.desktop", inicie o Emulador de Terminal na pasta onde está o arquivo que foi baixado.

Digite o comando abaixo no Emulador de Terminal e pressione a tecla "Enter", digite a sua senha se for solicitada e pressione a tecla "Enter" para copiar o arquivo com a extensão ".desktop" para a pasta "/usr/share/applications".

$ sudo cp NotepadNext.desktop /usr/share/applications

ou

$ sudo cp notepadnext_deb_package.desktop /usr/share/applications


Digite o comando abaixo no Emulador de Terminal e pressione a tecla "Enter" para escrever globalmente todas as entradas dos menus do antiX:

$ sudo desktop-menu --write-out-global
