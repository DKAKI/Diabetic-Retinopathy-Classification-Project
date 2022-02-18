# Diabetic-Retinopathy
Travail réalisé par /DKAKI_ABDERRAHIM

La rétinopathie diabétique (Diabetic retinopathy (DR)) est considérée comme l'une des maladies mondiales de la cécité, en particulier chez les personnes âgées. La principale raison de cette maladie est la complication du diabète dans les vaisseaux sanguins rétiniens. Habituellement, les signes avant-coureurs ne sont pas observés. Le dépistage est une clé importante pour le diagnostic des stades précoces de la rétinopathie diabétique. Dans ce travail, notre tâche est de créer un système d'analyse automatisé capable d'attribuer un score basé sur l’échelle suivante : 0 – pas de DR   /1 – léger   / 2 - Modéré   /3 - Sévère /4 - DR proliférative ce qui peut aider les médecins à prendre une décision préliminaire.
![myimage-alt-tag](https://ocutech.com//wp-content/uploads/2017/12/Diabetic-Retina.jpg)

Le diabète, une maladie chronique affecte divers organes du corps humain, y compris la rétine. La rétinopathie diabétique (RD) résulte du diabète sucré (Diabetes Mellitus) (DM). La DM est la principale cause de cécité entre un groupe d'âge significatif dans les pays occidentaux. Il augmente dans les pays sous-développés aussi. Les patients atteints de DM sont beaucoup plus susceptibles à la cécité que sans DM. La rétinopathie diabétique progressive et l'œdème maculaire (cliniquement significatif) peuvent entraîner une perte de vision sévère. La RD affecte une large population diabétique dans les pays développés.
DR, une maladie silencieuse qui n'apparaît qu'à ses derniers stades où le traitement est très difficile et dans certains cas impossibles. Dans la DR les vaisseaux sanguins qui aide à nourrir le la rétine commence à fuir du liquide et du sang sur la rétine, ce qui entraîne des caractéristiques visuelles appelées lésions telles que les microanévrysmes, hémorragies, exsudats durs, taches de coton, région des vaisseaux sanguins. Il ne peut être traité efficacement qu'à ses débuts et donc sa détection précoce est très importante grâce à un dépistage régulier. Le dépistage automatique est hautement nécessaire afin que l'effort manuel soit réduit vu que le cout de cette procédure est assez élevé.


# Dataset:


Les images rétiniennes ont été fournies par EyePACS, une plateforme gratuite de dépistage de la rétinopathie. On dispose d'un grand ensemble d'images rétiniennes haute résolution prises dans diverses conditions d'imagerie. Un champ gauche et droit est fourni pour chaque sujet. Les images sont étiquetées avec un identifiant de sujet ainsi que soit à gauche ou à droite (par exemple, 1_left.jpeg est l'œil gauche du patient id 1). L'ensemble de données comprend 88 696 images de 44 348 sujets, une image pour chaque œil.
 Un clinicien a évalué la présence de rétinopathie diabétique dans chaque image sur une échelle de 0 à 4, selon l'échelle mentionné précédemment.
Les images de cet ensemble de données provenaient de différents modèles et types de caméras et présentaient une qualité très mitigée. Il y avait du bruit dans les images et les étiquettes. Certaines images contenaient des artefacts - étaient floues, sous-exposées ou surexposées. Un objectif majeur de ce projet était de développer un algorithme pouvant fonctionner en présence de bruit et de variations.
échelle:
>
>0 - No DR
>
>1 - Mild
>
>2 - Moderate
>
>3 - Severe
>
>4 - Proliferative DR

