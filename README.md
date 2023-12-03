# sae1.3-2.3
Projet : Saé 1.03/2.03 Installation de service réseau
Le rapport à été rédigé avec asciidoctor.

Il faut donc avoir installé asciidoctor, pour vérifier la version et
donc si il est installé, on peut faire : asciidoctor --version Et si il
n'est pas installé : apt install asciidoctor

De la même manière, il faut l'extension pour les pdf, on peut faire :
asciidoctor-pdf --version Et si il n'est pas installé : apt install
asciidoctor-pdf

Une fois certain d'avoit tous les logiciels nécéssaires, on peut
convertir ce rapport en .adoc en .html et en .pdf.

Pour convertir le fichier .adoc en .html la commande est la suivante :
asciidoctor `<cheminDuFichier>`{=html} Donc si vous êtes dans le même
répertoire : asciidoctor RapportFinal.adoc

De la même manière, pour convertir le fichier .adoc en .pdf la commande
est la suivante : asciidoctor-pdf `<cheminDuFichier>`{=html} Donc si
vous êtes dans le même répertoire : asciidoctor-pdf RapportFinal.adoc

Ces rendus (rapport, note, images) ont étés faits par Fourmaintraux
Camille - Groupe E.
