# mini test
Une application Java utilisant Jakarta Persistence API (JPA) avec PostgreSQL pour gérer les relations entre différentes entités comme Student, Address et Cours.

# ⚙️ Relations entre les entités

**@Entity** : Définit une classe comme une entité JPA.

**@OneToOne** : Relation entre Student et Address (un étudiant a une seule adresse).

**@ManyToOne** : Relation entre Employe et son chef (un employé a un chef).

**@OneToMany** : Relation entre Employe et ses subordonnés (un chef a plusieurs employés sous ses ordres).

**@ManyToMany** : Relation entre Student et Cours (un étudiant peut suivre plusieurs cours, et un cours peut être suivi par plusieurs étudiants).