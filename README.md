# TP – Relations entre entités, Cascade et orphanRemoval

Projet Maven (JPA / Hibernate + base H2 en mémoire) pour gérer des réservations de salles.

## Description

Le projet contient 4 entités :

- **Utilisateur**, **Salle** et **Reservation** : relations `OneToMany` / `ManyToOne`.
- **Equipement** : relation `ManyToMany` avec `Salle` (table de jointure `salle_equipement`).

Points testés :

- **Cascade** : les réservations sont enregistrées en même temps que l'utilisateur et la salle (`CascadeType.ALL`).
- **orphanRemoval** : une réservation retirée de la liste de l'utilisateur est supprimée de la base.
- **ManyToMany** : ajout / retrait d'équipements d'une salle (l'équipement lui-même n'est pas supprimé).

## Lancer le projet


## Exécution



https://github.com/user-attachments/assets/c6a665ec-db35-4a5d-a2ef-3141a5202034


