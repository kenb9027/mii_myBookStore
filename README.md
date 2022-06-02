Nouveau Projet Symfony 5.4

- MyBookStore
Dependances Front
- Bootstrap

Entité
- book 
    - id 
    - title 
    - description 
    - price 
    - cover 
    - createdAt (valeur par defaut = date de l'insertion) 
    - publishedAt 
    - isActive (defaut = false)

- author 
    - id 
    - firstname 
    - lastname 
    - fullname (genaré automatiquement = firstname + lastname) 
    - gender (M, F, N)

- category 
    - id 
    - name 
    - description 
    - color (7 caractères) 
    - illustration

Formulaire
- BookType
- AuthorType
- CategoryType

Routes
- accueil /
- Liste des livres /books
- Details d'un livre /book/{id}
- Ajouter un livre /book
- Editer un livre /book/{id}/edit
- Supprimer un livre /book/{id}/delete
- Liste des auteurs /authors
- Details d'un auteur /author/{id}
- Ajouter un auteur /author
- Editer un auteur /author/{id}/edit
- Supprimer un auteur /author/{id}/delete
- Liste des catégories /categories
- Details d'une catégorie /category/{id}
- Ajouter une catégorie /category
- Editer une catégorie /category/{id}/edit
- Supprimer une catégorie /category/{id}/delete

////////////////////////////////////////////////
- Relations entre les entités
- EntityType et CollectionType dans les formulaires
- Sécurité (restriction d'accès)
