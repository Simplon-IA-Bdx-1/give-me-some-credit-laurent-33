# Projet GiveMeCredit (10/2019)

## Objectifs

Générer un programme qui estime la capacité de remboursement d'une personne demandant un nouveau prêt.
<br><br>

## Méthodologie

1. Un historique de cas d'emprunteurs est disponible (plusieurs milliers), et pour chacun d'entre-eux diverses données :
    - si la personne a réussi a rembourser le prêt dans son intégralité
    - les revenus de la personnes
    - le nombre de personnes à charge
    - si elle a déjà eu des défauts de paiement
    - le taux d'endettement
    - ...

2. Un traitement est alors effectué sur ces données brutes afin de compléter les informations disponibles.

3. Un modèle d'apprentissage va alors être créé à partir de toutes ces données afin de déterminer l'importance de chacune 'entre-elles.

4. Lorsque un nouveau candidat emprunteur se présente :
    - l'on retraite ces nouvelles données de la même façon que ce qui avait été fait sur les données d'entraînement du mdèle
    - on présente ces nouvelles données au modèle
    - le résultat est récupéré, à savoir si ce candidat a de bonne chance de rembourser ou non (en se basant sur les cas passés)
<br><br>

## Liens vers les notebooks

- Récupération et Préparation des Données
<center>

[191007 GiveMeCredit - 01data prepare.ipynb](file/191007&#32GiveMeCredit&#32-&#3201data&#32prepare.ipynb)
</center>

- Création du modèle et évaluation sur le set de validation
<center>

[191007 GiveMeCredit - 02bigml evaluation.ipynb](file/191007&#32GiveMeCredit&#32-&#3202bigml&#32evaluation.ipynb)
</center>

- Prédiction sur le set de test et envoi pour évaluation finale
<center>

[191007 GiveMeCredit - 03kaggle format.ipynb](file/191007&#32GiveMeCredit&#32-&#3203kaggle&#32format.ipynbb)
</center>

- Notebook de prédiction sur un seul input
<center>

[191107 GiveMeCredit - 04bigml prediction.ipynb](191107&#32GiveMeCredit&#32-&#3204bigml&#32prediction.ipynb)
</center>
<br>

## Notebooks annexes

- Tracé des courbes d'apprentissage du modèle
<center>

[191103 GiveMeCredit - learning curves.ipynb](191103&#32GiveMeCredit&#32-&#32learning&#32curves.ipynb)
</center>

- Regroupement et moyenne de 4 modèles
<center>

[191104 gmcs group moyenne.ipynb](191104&#32gmcs&#32group&#32moyenne.ipynb)
</center>
