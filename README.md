<h1 align="center"># MUTHO</h1>
<h4 align="center">Reasoner da utilizzare: HermiT 1.4.3.456</h4>


Italiano | [English](README_EN.md)

Benvenuto nell'implementazione ufficiale dell'ontologia mutho (music and theater ontology) sviluppata da Promemoria Group.
Questa ontologia serve a raccogliere informazioni riguardanti le opere teatrali.
Le informazioni raccolte spaziano dal compositore dell'opera, ai ballerini partecipanti, alla locazione geografica in cui si è tenuta l'opera fino ai costumisti e molto altro.

# Index
- [Tratti Distintivi](#tratti-distintivi)
- [Ambiente di Sviluppo Utilizzato][#ambiente-di-sviluppo-utilizzato]
- [Download Ontology](#download-ontology)
- [Download Release](#download-release)
- [Build from Source Code](#build-from-source-code)
- [Run Ontology](#run-ontology)

## Tratti Distintivi

L'ontologia è stata sviluppata mediante riferimenti ad ontologie esterne.

Occorre far presente che l'ontologia da cui abbiamo preso spunto per lo sviluppo è Doremus Ontology  (DOing REusable MUSical data).
Questa ontologia serve per catalogare e registrare informazioni riguardanti la musica (autore,genere,durata ecc..).
Basata su ontologie già esistenti come FRBR (Functional Requirements for Bibliographic Records) e CIDOC, un'ontologia che descrive il dominio dei beni culturali, nella prospettiva dei musei.
Come nel caso di Doremus Ontology sono state utilizzati riferimenti ad ontologie esterne come FRBR, schema.org, FOAF, lukeBlaney.

FRBR è un'ontologia utile a dare una rappresentazione semi-formale delle informazioni bibliografiche.
Da questa ontologia sono state importate alcune classi e relazioni come ad esempio la classe Endeavour (che rappresenta un qualsiasi prodotto di impresa artistica o creativa).

L'ontologia esterna FOAF (acronimo di friend of a friend) viene utilizzata principalmente per descrivere persone, con le loro attività e le relazioni con altre persone e oggetti.
Da questa ontologia sono state importate alcune classi e relazioni come ad esempio la classe Organization.

L'ontologia esterna schema.org è uno schema di markup di dati strutturati supportato dai motori di ricerca, nato da Google, Yahoo! e Microsoft. Grazie a questo schema, i motori di ricerca avranno modo di capire meglio le informazioni presenti nelle pagine web.
Schema.org è stata dunque utilizzata per facilitare la reperibilità dei dati riguardanti l'ontologia dai principali motori di ricerca.
Da questa ontologia sono state importate alcune classi e relazioni come ad esempio la classe Organization (impostata poi come equivalente alla classe Organization della ontologia esterna FOAF).

Abbiamo importato anche alcune classi e relazioni dall'ontologia esterna fornita dall'autore Luke Blaney usata per descrivere ed organizzare dati riguardanti le opere teatrali.
Da questa ontologia sono state importate alcune classi e relazioni come ad esempio la classe Season (descrive il concetto di stagione nelle produzioni delle opere teatrali).

## Ambiente di Sviluppo Utilizzato
