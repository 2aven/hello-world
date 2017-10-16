# hello-world
## Tasca LMSGI 01 - Introducció als Llenguatges de Marques

### A) Creació de documents
S'han creat documents inicialment desde l'editor de text plà Gedit, per introduir diferents exemples de llenguatges de marca i s'han guardat posteriorment en els formats corresponents: .rtf .html i .xml que vé acompanyat amb un arxiu de format .xsl

1. El document de tipus RTF es pot obrir amb processadors de text com OpenOffice, en aquest cas es mostra un text d'exemple simple amb énfasis (conté *cursiva*) modificant la font **Marlett**.
`{\rtf1\ansi\ansicpg1252\uc1\deff0\deflang1034\deflangfe1034{\fonttbl{\f0\fcharset0 Marlett;}}\f0{\colortbl;}\pard\sl-240\slmult1\li0\fi0\ri0\sa200\sb0\s-1\cfpat0\cbpat0{\fs22\ulnone text en }{\i\fs22\ulnone cursiva}}`
![Captura document RTF][Screen_RTF]
2. L'exemple de document HTML s'obre desde un explorador web, en aquest cas Firefox, i conté un títol en format de capçalera i un paràgraf simple.
![Captura document HTML][Screen_HTML]
3. El document XML conté una tabla d'un hipotètic catàleg de música, defineix l'element <cd> amb diferents propietats (títol, artista, país, discogràfica, preu, any). El document XML per sí sol no defineix més que els elements, per això s'inclou la segona línea '<?xml-stylesheet href="Tabla.xsl" type="text/xsl"?>' que fà referència a un arxiu .xsl que li dona l'estil de presentació; en aquest cas, mostrant una taula que fà llistat amb només el títol i l'artista de cada element definit al .xml.
![Captura document XML][Screen_XML]

En aquest arxiu hi ha una petita mostra de com usar **Markdown**, que permet marcar de manera fàcil certes opcións de format:

* Énfasis: **negreta** i *cursiva*.
* [links](https://rawgit.com/) ...
* Llistes
  - [x] amb subllistes
  - [x] o checkbox
  - [ ] també poden ser enumerades
* Imatges
* Tamanys de papçalera o textos citats
> Perfavor, m'acostes la sal?
>
> -Albert Eintein, dinant en família.
* Format per mostrar còdi
  - que pot mostrar colors per resaltar la sintàxis:
```javascript
if (isAwesome){
  return true
}
```
* I altres...

[Screen_RTF]: https://github.com/2aven/hello-world/blob/master/Captura%20de%20pantalla%20de%202017-10-16%2010-43-40.png
[Screen_HTML]: https://github.com/2aven/hello-world/blob/master/Captura%20de%20pantalla%20de%202017-10-16%2012-29-04.png
[Screen_XML]: https://github.com/2aven/hello-world/blob/master/Captura%20de%20pantalla%20de%202017-10-16%2012-41-20.png
[Screen_RawGit]: https://github.com/2aven/hello-world/blob/master/Captura%20de%20pantalla%20de%202017-10-16%2014-34-40.png
