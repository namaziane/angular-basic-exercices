
=== Exercices:

=== Cacher/Afficher le details d'une formation au clique en utilisant la propriéte [Hidden]

**_Instructions_**: Cacher/Afficher les détails d'une formation lorsque le bouton expand/Collapse sont cliqués en liant l'expression training.hidden

[source,js]
----
  trainings = [
    {
      nom: 'Formation Angular Débutant', date: '15/02/2023', heure: '18h', url:
        "https:team.com", format: "enligne", hidden: false
    },
    {
      nom: 'Formation Angular Avancé', date: '15/06/2023', heure: '18h', lieu: {
        adresse:
          'adresse-1', ville: 'ville-1', pays: 'pays-1'
      }, format: "sursite", hidden: false
    },
    {nom: 'AWS', date: '15/04/2023', heure: '18h', hidden: false}
  ];
----


=== Cacher/Afficher le details d'une formation au clique en utilisant l'event binding

**_Instructions_**: Cacher/Afficher les détails de toutes les formation en cliquant sur le bouton expandAll/CollapseAll


=== Filtrer les elements de la liste en utilisant le binding bidirectionnel

**_Instructions_**: Filrer la liste des formations en saisissant une partie de nom de formation dans un input
en utilisant ngModel
