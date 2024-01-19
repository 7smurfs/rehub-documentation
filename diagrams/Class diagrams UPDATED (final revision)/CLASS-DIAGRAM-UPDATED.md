Dijagramom razreda prikazujemo razrede u sustavu, njihove atribute i metode te veze između razreda koji se nasljeđuju ili međusobno komuniciraju. U nastavku slijede dijagrami čiji razredi imaju sličnu funkcionalnost i razinu apstrakcije

EntityClassDiagram - prikazuje razrede koji pripadaju sloju Model. Svaki od razreda se preslikava u odgovarajuću tablicu u bazi

RepositoryClassDiagram – prikazuje razrede koji pripadaju sloju Repository. Ovaj sloj komunicira sa bazom podataka i sa slojem Service.

ServiceClassDiagram – prikazuje razrede koji pripadaju sloju Service. Ovaj sloj komunicira sa slojem Repository i Controller.

ControllerClassDiagram – prikazuje razrede sloja Controller. Ovaj sloj komunicira sa slojem Service i s frontend dijelom aplikacije.

EnumClassDiagram – prikazuje enumeracije koje koristi sloj Model.

ConfigClassDiagram – prikazuje razrede sloja Config. Ovaj sloj služi za sigurnosne potrebe i komuniciranje putem e-maila.

SecurityClassDiagram - prikazuje razrede sloja Security. Ovaj sloj služi za sigurnost i detalje o korisniku.

RequestClassDiagram – prikazuje razrede sloja Request. Ovaj sloj komunicira sa slojem Controller u svrhu validacije Post Request-a.

ResponseClassDiagram – prikazuje razrede sloja Response. Ovaj sloj komunicira sa slojem Controller u svrhu vraćanja Response poruke.