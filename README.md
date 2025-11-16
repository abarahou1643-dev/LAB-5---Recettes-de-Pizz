

#  PizzaRecipes

Application Android développée en Java permettant de consulter une liste de recettes de pizzas avec leurs détails complets (ingrédients, étapes de préparation, durée, prix).

---

## Démarrage Rapide

### Installation

- Ouvrir avec **Android Studio**
- Synchroniser Gradle
- Exécuter sur émulateur/device API 24+

### Fonctionnalités
-  Splash Screen animé
-  Liste des pizzas avec images
-  Détails complets des recettes
-  Navigation fluide

---

##  Structure

```
app/src/main/java/com/example/pizzarecipes/
├── classes/Produit.java          # Modèle données
├── dao/IDao.java                 # Interface DAO  
├── service/ProduitService.java   # Gestion données
├── adapter/PizzaAdapter.java     # Adapteur liste
└── ui/                           # Activités
    ├── SplashActivity.java
    ├── ListPizzaActivity.java
    └── PizzaDetailActivity.java
```

---

##  Tech Stack

- **Langage** : Java
- **SDK Min** : Android 7.0 (API 24)
- **Architecture** : MVC
- **Patterns** : Singleton, DAO, Adapter

---

##  Données

10 pizzas incluses avec :
- Nom, prix, durée
- Ingrédients complets
- Étapes de préparation
- Images haute qualité

---



https://github.com/user-attachments/assets/f593f74f-d358-4e02-9a79-cbb03c17f01b










