Lors de la prémière éxécution , le rapport nous indique des problèmes d'indentation dans tous le fichier qu'il suffit de corriger.


Il y'a eut beaucoup de soucis de dépendances a régler sur le moment , quelque problèmes de git notamment le fait que j'ai push directement sur la branche demander dans le tp donc j'ai du recréer un repo github 

De fait , une fois les problèmes de dépendances contourner les tests fonctionnent relativement bien

 
1. Avantages observés : 
   - Quels sont les avantages de l'automatisation des tests que vous avez constatés ? 

    Je trouve ces tests efficaces de sorte a pouvoir rapidement trouver les erreurs avec des tests unitaires qui lorsqu'ils sont déclenchés permet également de cibler le type d'erreur , en moyen et gros environnement de développement avec pas mal de monde je pense que ca permet grandement de contribuer a un code propre et fonctionnel sans rajouter trop de charge de travail a tous le monde .


   - Comment le CI/CD améliore-t-il la qualité du code ? 

   Comme dis ci-dessus , pouvoir lancer ses tests automatiques branche par branch et séparer les jobs a de nombreux avantage vis a vis du clean code , de l'entretien du code mais également du débug
 
2. Défis rencontrés : 
   - Quelles difficultés avez-vous rencontrées avec Selenium ? 

    Problème de dépendances pour la plupart du temps

   - Comment pourriez-vous améliorer la stabilité des tests ? 

   Rajouter des tests sur des erreurs courrantes pour les spécificités d'un projet particulier
 
3. Métriques : 

   - Quelles métriques sont les plus importantes pour votre projet ? 

   Le taux de réussite du test  est le plus important pour garantir l'abscence de régression . 

   - Comment mesurer l'efficacité de votre pipeline CI/CD ? 

   On la mesure principalement par la durée de cycle(temps entre le commit et le résultat des tests) et la stabilité (fréquence des échecs liés à l'infrastructure plutôt qu'au code).

