HTML hypertext markup language -> linguaggio di formattazione per ipertesti
fornire una struttura logica (che abbia senso agli occhi dell'utente) della pagina


Sintassi - un elemento HTML assume la seguente forma:
<tagname attribute1="value1" attribute2="value2" attribute3="value3">content</tagname>

Self closing tags: elementi che non potendo avere contenuto non hanno tag di chiusura

Attributi globali:
- id
- class (insieme di elementi)
- style

Headings tags - per ordine di importanza decrescente
h1
h2
h3
...
h6

Paragraph tag
p

Anchor tag (link)
attributo href cioè hypertext reference



http://127.0.0.1:5500/index.html
https://ricette.giallozafferano.it/Tagliatelle.html


Web Server (il live server simula un web server)
converte un URL in rete -> legge il contenuto di un file sul file system
http://127.0.0.1:5500/index.html -> /Users/kutta/Desktop/HPT68/02_HTML/index.html
http://127.0.0.1:5500/about-us.html -> /Users/kutta/Desktop/HPT68/02_HTML/about-us.html
http://127.0.0.1:5500/friends/ugo.html -> /Users/kutta/Desktop/HPT68/02_HTML/friends/ugo.html



Block level elements:
- occupano tutta la larghezza a loro disposizione (da migliore in CSS)
- impilati in verticale (uno sotto l'altro)
h1, h2, ..., h6
p
div division    il contenitore particolare degli elementi block
ul li oppure ol li

Inline level elements:
- occupano solo la larghezza a loro strettamente necessaria al contenuto
- impilati in orizzontale (uno di fianco all'altro)
a
span    il contenitore particolare degli elementi inline
img
strong


# Regole per elementi HTML innestati
Un elemento block può presentare come contenuto:
- elementi block
- elementi inline
- puro testo

Un elemento inline può presentare come contenuto:
- elementi inline
- puro testo

Eccezione: gli elementi block Headings e Paragraph possono presentare come contenuto:
- elementi inline
- puro testo
