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


