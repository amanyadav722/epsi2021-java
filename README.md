# Java - les fondamentaux

Vous trouverez ici au fur et à mesure le code sources des TD réalisés durant le cours

## Insertion de caractères dans une chaine
### Objectifs
- créer une classe principale, point d'entrée du programme
- créer une seconde classe utilitaire
- instancier et appeler cette dernière classe
- récupérer le paramètre passé en ligne de commande

### Les classes concernées
- [fr.epsi.Application](/src/fr/epsi/Application.java)
- [fr.epsi.util.StringUtil](/src/fr/epsi/util/StringUtil.java)

### Procédure de compilation et exécution
depuis le répertoire `src`
```
javac fr/epsi/Application.java
javac fr/epsi/util/StringUtil.java
java fr.epsi.Application MaChaineDeCaractères
```

## Polygones

### Objectifs
- manipuler les apports du **polymorphisme** (utilisation d'un objet en tant que sa classe parente ou les interfaces qu'il implémente)
- saisir le concept de "contrat de service" qu'une interface apporte (une classe qui implémente une interface DOIT implémenter l'ensemble des méthodes définies dans l'interface)

### Les classes concernées
- L'ensemble du package [fr.epsi.poly](/src/fr/epsi/poly)

## Compte Bancaire

### Objectifs
- Appliquer le principe objet de l'**encapsulation** pour verrouiller le fonctionnement interne d'une classe et s'assurer que ses instances seront correctement utilisées, sans possibilité de s'écarter volontairement du fonctionnement désiré

### Les classes concernées
- L'ensemble du package [fr.epsi.bank](/src/fr/epsi/bank)
