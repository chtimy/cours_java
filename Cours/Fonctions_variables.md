Une méthode est un petit morceau de code que l'on peut réutiliser plusieurs fois. Ca permet d'éviter entre autre la duplication d'un même code. Voici par exemple la fonction *pow* qui va calculer la puissance d'un nombre:

```java
float pow(float number, float power) {
   result = number;
   for(int i = 1; i < power; i++) {
       number = number * number;
   }
   return number;
}
```

