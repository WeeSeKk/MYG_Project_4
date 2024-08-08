---
title: Specifications document MYG Project 4
---
# I. Summary

# 

&nbsp;

&nbsp;

&nbsp;

# II. Project description

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

# III. **Architecture** 

## Use Case :

```mermaid
graph LR
    A((User)) --> B(Create account)
    B --> D(Login)
    A --> E(Add product to 
cart/wishlist)
    E --> F(Add product to cart
via wishlist)
    E --> G(Buy product 
from cart)
    A --> H(Write comments
on products)

    C((Admin)) --> I(Add products)
    I --> J(Modify products)
    C --> K(View accounts)
    K --> L(Delete accounts)
    C --> M(Delete comments)
    C --> N(Modify front page)
    C --> O(Modify/Add products category)
```

## Buying Workflow :

```mermaid
graph TD
    A[Add product to cart] --> B(Go to cart)
    B --> C{Cart}
    C -->|Remove product from cart| D[Empty cart]
    C -->|confirm buying/shipping| E[Add product         to order list]
    E --> F{Oder list}
    F --> |Cancel order via orders list|G[Empty order list]
    F --> |Follow order via orders list|H[Continue updating the order 
list until shipping is complete]
    H --> |Once shipping is done|I[Order in order list is complete]
```

## AR Workflow :

```mermaid
graph TD
    A[Add Product 
to app] --> C
    C{3D model}
    C -->|Add 3D model| D[AR button appear on 
product page]
    C -->|Don't add 3D model| E[AR button don't show
on product page]
    D --> |AR button clicked| F[Open AR view on app]
    F --> G[View product on AR]
```

&nbsp;

# IV. **Planning & budget**

&nbsp;

&nbsp;

&nbsp;

# V. **Annexes**

## Wireframe(User) :

&nbsp;

<p align="center"><img src="/.swm/images/Group%201%20(1)-2024-7-8-7-49-53-592.jpg"></p>

## Wireframe(Admin) :

<p align="center"><img src="/.swm/images/Group%202-2024-7-8-7-49-3-573.png"></p>

&nbsp;

&nbsp;

&nbsp;

#### **I. Résumé**

- **Nom de l'application**

- **Date de création**

- **Version**

- **Auteur**

- **Objectifs de l'application**

- **Public cible**

- **Plateformes cibles** (iOS, Android, web)

- **Budget**

- **Délai de réalisation**

#### **II. Description du projet**

- **Besoin métier** : Détaillez le problème que l'application vise à résoudre et les besoins des utilisateurs.

- **Fonctionnalités** : Décrivez les fonctionnalités principales et secondaires de l'application, en précisant leur importance et leur fonctionnement.

- **Ergonomie et design** : Définissez l'interface utilisateur (UI) et l'expérience utilisateur (UX) recherchées, en précisant les couleurs, les typographies, les styles graphiques, etc.

- **Contenus** : Décrivez les types de contenus qui seront présents dans l'application (textes, images, vidéos, etc.).

- **Spécifications techniques** : Détaillez les technologies et les frameworks qui seront utilisés pour le développement de l'application.                              (database)

#### **III. Architecture UML** 

- Diagramme de cas d'utilisation (USE CASE)

- Diagramme de d'activité

- Diagramme de classe&nbsp;

#### **IV. Planning et budget**

- **Détaillez les différentes étapes du projet** (conception, développement, tests, etc.) et le planning associé.

- **Prévoyez un budget** pour chaque étape du projet, en tenant compte des ressources humaines et matérielles nécessaires.

#### **IV. Annexes** 

- **Wireframes** (représentations schématiques de l'interface utilisateur)

- **Charte graphique**

<SwmMeta version="3.0.0" repo-id="Z2l0aHViJTNBJTNBTVlHX1Byb2plY3RfNCUzQSUzQVdlZVNlS2s=" repo-name="MYG_Project_4"><sup>Powered by [Swimm](https://app.swimm.io/)</sup></SwmMeta>
