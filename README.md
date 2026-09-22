# Tp: Etude de la diffration

## Objectifs

Etudier expérimentalement les figures de diffraction de différents objets et les comparer à la théorie

## I. Conditions expérimentales: diffraction de Fraunhofer

## II. Vérification expérimentale des lois de diffraction

### a. Diffraction par une fente et deux fentes

On fait passer un laser à travers une fente simple de largeur a puis deux fentes de largeur a distantes de b. On observe les figures de diffraction a l'écran placé à une distance D des fentes. (voir photos)

Les valeurs de a et b sont données par: 
$$
a =\frac{\lambda D}{i_a} 
b = \frac{\lambda D}{i_b}
$$
avec
$$
i_a = \frac{L_a}{N}
i_b = \frac{L_b}{N}
$$

$$L_a$$ et $$L_b$$ sont les longueurs des franges associées respectivement a a et b pour une valeur du nombre N de frange sur la longueur

### b. Comparaison avec les expressions théoriques.

Nous utilisons une barette CCD qui est sensible à la lumière à la place de l'écran et observe les figures d'interférence sur l'ordinateur. 

Nous entrons les valeurs trouvées de a et b dans le logiciel CALIENS pour obtenir la les figures d'interférences théoriques à superposer aux figures expérimentales. 

Nous determinons par la suite les valeurs théoriques (graphiques) et déterminons les erreurs relatives

## III. Diffraction par des réseaux

### a. Diffraction par transmission

Nous faisons traverser un réseau par un laser (d'helium-néon (rouge) comme précédemment) et nous obtenons les figures de diffraction sur l'écran a une distance D. 

Nous nous appuyons sur la relation fondamentale des réseaux: $$ csin \theta = m \lambda $$ avec,

c : le pas du réseau
$$\theta$$ : l'angle de la direction d'observation par rapport a la normale avec $$\theta$$ tres petit
m: un entier relatif représentant l'ordre de diffraction

### b. Diffraction par réflexion

Nous comparons la diffraction par reflexion d'un blu-ray, d'un dvd, et d'un cd ,dans le cadre ou $$\theta$$ n'est plus petit.

## IV. Cohérence spatiale

Nous écliarons des fentes d'Young (distantes de b) par une lampe de sodium (raie verte) devant la quelle nous plaçons une fente reglable d'épaisseur e. La fente reglable est a une distance ds des fentes d'Young. 

Théoriquement le contraste C des franges s'annule lorsque:

$$
e = \frac{\lambda d_s}{b}
$$


Après avoir obtenu la disparition des franges (C = 0) nous déterminous expérimentalement e a l'aide du banc optique comme dans la section II.a.

## Traitement des données

Python

## Fichiers

- 'tp_etude_de_la_diffraction': traitement principal des données expérimentales
- 'functions.py': fonctions utilisées pour l'exploitation des mesures

## Auteur

Nils CAKPO
L3 Physique