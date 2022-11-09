![markdown](https://user-images.githubusercontent.com/104193452/200848514-fdfcea6b-473d-4cc1-b41d-4fdd51f65322.png)
# [Markdown](https://daringfireball.net/projects/markdown/)
Markdown ist eine vereinfachte Auszeichnungssprache. Ein Ziel von Markdown ist eine leicht lesbare Ausgangsform bereits vor der Konvertierung. Als Auszeichnungselemente wurden daher vor allem Auszeichnungsarten verwendet, die in Plain text und E-Mails üblich sind. Auch andere Auszeichnungssprachen mit ähnlichen Zielen zur Lesbarkeit. relevante Features dabei sind:
# Überschriften 
Diese kann man mit einem # kennzeichnen (oder kleinere überschriften mit mehrere # davor) z.B:
# h1 Heading 
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading

## Trennstriche
<hr>
Trennstriche kennzeichnet man mit dem < hr> tag

## hervorgehoben/betonte Wörter
**fett** werden Wörter geschrieben mit 2 * am anfang und ende vom wort
*kursiv* geschrieben wird ein wort mit einem * am anfang und ende vom wort
~~durchgestrichen~~ mit ~ am start und ende vom wort
## Aufzählungen
Man kann diese ungeordnet mit `+`, `-`, oder `*`erstellen z.B:

+ Liste
  - unterliste
    * he
    + ll
    - o
    
geordnet können sie mit nummerierter ordnung erstellt werden:

1. Nr.1
2. Nr.2
3. Nr.3

1. Man kann hintereinanderfolgende Nummern benutzen
1. ...oder man setzt alle als `1.`

## Code

Inline `code`

Indented code

    // Some comments
    
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tabellen

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

######Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


##Blockzitate

> Blockzitate werden mit ">" gekennzeichnet
>> mit mehreren werden diese mehr eingeschoben
> > > man kann auch Platz zwischen diesen haben

## [Fußnote](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].
[^first]: Fußnote
diese können mit einem [^beispiel] nach dem wort gesetzt werden aber sie müssen deklariert werden mit [^bsp]: bsp



#Quellen

[Wikipedia](https://de.wikipedia.org/wiki/Markdown)
[markdown demo](https://markdown-it.github.io/)
[Footnotes](https://github.com/markdown-it/markdown-it-footnote)
