# 4625-extractor
Analitza els registres de seguretat de Windows amb ID 4625


Descripció del codi

* Aquest script en Python s'encarrega d'analitzar els registres de seguretat de Windows per cercar esdeveniments específics.

* Connexió al registre d'esdeveniments: S'obre la font de registres de seguretat del sistema local.

* Cerca d'esdeveniments: Filtra esdeveniments amb el codi d'error 4625, que indica errors d'inici de sessió.

* Extracció de dades: Obté les adreces IP d'origen i els noms d'usuari dels esdeveniments trobats.

* Generació de fitxers: Escriu les adreces IP i els noms d'usuari en dos fitxers separats en format Markdown.

* Gestió d'errors: Inclou maneig d'excepcions per assegurar una execució estable.

* Aquest script és útil per a auditories de seguretat i anàlisi de problemes d'inici de sessió.
