**`Projecte Fase1: Definició i validació del catàleg XML`**

**`Contextualització`**

`Aquest enunciat correspon al primer bloc del projecte del mòdul 0373: al llarg de tot el curs es treballa un únic catàleg —el d'una botiga fictícia que cada persona tria i personalitza—, que va evolucionant RA a RA fins a cobrir set perspectives diferents (XML, validació, web, interactivitat, transformació, emmagatzematge i gestió comercial). En aquest primer bloc es defineix el catàleg com a document XML (RA1) i se'n valida l'estructura amb un DTD (RA4).`

`Les dues parts comparteixen el mateix catàleg però s'avaluen per separat, amb rúbrica pròpia per a cada RA.` 

**`RA1 - Reconeix les característiques de llenguatges de marques analitzant i interpretant fragments de codi`**

**`Objectiu`**  
`Crear el fitxer cataleg.xml que reculli el catàleg d'una botiga fictícia de temàtica a escollir com a document XML ben format, aplicant les característiques i regles sintàctiques dels llenguatges de marques treballades a classe. Aquest catàleg és el document base sobre el qual també treballarà la part de RA4.`

**`Enunciat`**  
`Es treballa individualment. Cada persona tria el nom i la temàtica de la seva botiga (llibreria, música, roba, electrònica, esports, jocs de taula, alimentació, videojocs, etc...); aquesta tria és lliure i no altera cap dels requisits següents.`

`Dades de la botiga (element arrel). El catàleg no pot començar directament amb la llista de jocs: l'element arrel ha d'incloure també les dades pròpies de la botiga: el seu nom, la moneda en què es mostren els preus (per defecte EUR) i la data de l'última actualització del catàleg.`

`Mínim de productes. El catàleg ha de contenir com a mínim 10 productes diferents, cadascun amb els camps següents:`

* `Codi: identificador propi del producte dins del catàleg (per exemple PROD-001), únic per a cada producte.`

* `Nom / Títol.`

* `Categoria / Sector: una o més categories per producte (per exemple, ficció, assaig, roba d'home, calçat, accessoris, terror, acústic, etc.).`

* `Etiquetes / Característiques: un o més valors o especificacions segons la temàtica triada (per exemple, talles, formats, marques, plàstics/materials, opcions d'ús, etc.).`

* `Preu: número, en la moneda indicada a les dades de la botiga.`

* `Valoració: número (per exemple, d'1 a 10, o d'1 a 5 estrelles — a definir pel grup i indicar-ho a la justificació).`

* `Estoc: nombre d'unitats disponibles (enter, ≥ 0).`

* `Data d'incorporació / Data de llançament (format DD/MM/AAAA).`

* `Descripció: una o dues frases.`

`Camps amb més d'un valor. Com que un mateix producte pot tenir més d'una categoria i més d'una etiqueta o característica, aquests dos camps s'han de poder repetir per a un mateix producte: caldrà decidir com representar-ho amb XML (aquesta decisió és, precisament, un dels punts que avalua la rúbrica de RA1, i determinarà la cardinalitat que haureu de definir més endavant al DTD de RA4).`

**`Què heu de fer?`** 

* `Dibuixeu, a mà o amb una eina, un esquema de l'arbre d'estructura del document: element arrel, elements i els seus fills, i quins camps seran elements i quins atributs. Aquest esquema forma part del lliurable final.`

* `Declaració XML completa, amb la codificació (encoding) indicada explícitament, i un únic element arrel (per exemple <botiga> o <cataleg>) amb les dades de la botiga descrites més amunt.`

* `El document ha d'estar ben format: etiquetes obertes i tancades correctament, aniuament correcte, noms d'elements vàlids i valors d'atribut entre cometes.`

* `Com a mínim un comentari XML (<!-- ... -->) que expliqui una part del document (per exemple, el significat del camp "codi" o de l'estructura general).`

* `Com a mínim un cas en què calgui utilitzar una referència d'entitat predefinida (&amp;, &lt;, &gt;...) — per exemple, perquè el títol o la descripció d'algun producte conté el caràcter "&" ("Rock & Roll") o algun altre símbol reservat.`

* `Cal decidir raonadament què es representa com a element i què com a atribut, i organitzar la informació en una jerarquia clara (per exemple, agrupar dades relacionades en subelements en lloc d'aplanar-ho tot en atributs solts).`

* `Comprovar amb una eina (navegador, editor de codi, validador en línia...) que el document és ben format, i adjuntar una captura de pantalla que ho mostri.`

**`Què heu d’entregar?`** 

* `RA1_Projecte_Fase_1_cataleg_nom_cognom.xml`   
* `L'esquema de l'arbre + una justificació escrita (una pàgina aproximadament) que expliqui les decisions d'estructura preses, per què s'ha triat cada element o atribut en els casos més dubtosos, i quins avantatges aporta representar aquesta informació en XML en un document anomenat RA1_Projecte_Fase1_cognom_nom.pdf`

