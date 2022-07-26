# Moteur de recommandation utilisant un modèle GAN à des fin exploratoire

Dans le cadre de mon mèmoire de fin d'annnée à l'IAE de Lille nous avons décidé, mon tuteur et moi même, de concevoir un système de recommandation permettant plus souvant aux utilisateur d'explorer de nouveaux films sans les frustrer, afin de résoudre le biais des "echo chambers". Pour ce faire nous nous sommes tourné vers les réseaux créatif de type GAN et semi GAN. Nous avons obtenue de bon résultat et les publions ici sous licence.


## Comment l'utiliser

Que ce soit pour une revue par les pairs ou votre propre curiosité, le code ici possède deux principaux modèle. Un plus ancien et plus aléatoire comparant des utilisateurs prit aux hasard entre eux mais tout de même correcte et solvant les effet bulles selon une comparaison à un aléatoire (le code fonctionne principalement sur l'ancien dataset de movie lens dont les deux fichiers son fournies) . et une autre version plus récente et bien plus optimisé utilisant les 25 millions d'utilisateur de movie lens. Ce modèle est plus précis et n'as pas de dépendance externe car les fichiers son téléchargés dans le script. 

Ancien modèle :
  - Gan_recomandation_WithTimestamp
  - Demo_recomandation_system
  - recomandation_system_CalculDiversityOverTime
  
  Dépendance :
   ajouter dans le dossier racine les datasets demandés ancien ou nouveau
   avoir entrainé un modèle au préalable pour les scripts de test

Nouveau Modèle :
  - Training_Optimized_recommandationGAN
  - CalculDiversityOverTime_Optimized_recommandationGAN
  - APP_demo_Optimized_recommandationGAN
  
  Dépendance :
    avoir entrainé un modèle au préalable pour les scripts de test

Si vous souhaitez en savoir plus, le mémoire traitant le sujet est mit dans le GIT, Gare à vous en cas de mauvaise utilisation.
