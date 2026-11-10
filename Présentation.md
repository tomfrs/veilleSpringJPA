# C'est quoi ?
Spring Data JPA est un module de Spring, facilitant l'accès aux données.

# Comment ça fonctionne ?
On peut créer des requêtes avec :
- L'annotation @Query -> requêtes natives
- Construire la requête à partir du nom de la méthode -> requêtes dérivées
- Spécifications -> requêtes dynamiques

Il faut d'abord importer les dépendances nécessaires dans le pom.xml du projet,
 spring-boot-starter-data-jpa s'en charge
 
 ![alt text](image.png)

 Il s'agit désormais de transformer des classes en entité gérée par JPA afin de pouvoir en générer des tables.
 @Entity transforme la classe, @Id et @GeneratedValue permet d'identifier un attribut id en tant que clé unique

 ![alt text](image-1.png)

 # Où l'utiliser ?
 Sprind Data JPA est la norme pour une application Spring manipulant une base relationnelle