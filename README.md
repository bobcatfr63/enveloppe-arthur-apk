# 💶 Enveloppe Arthur

**Une façon simple de savoir où va votre argent, d’anticiper vos dépenses et de maîtriser votre budget.**

Enveloppe Arthur est une application de gestion de budget par **enveloppes virtuelles**, disponible sur **Android** et en **aperçu sur Windows**. Chaque enveloppe représente un poste de dépenses : courses, carburant, vacances, loisirs, imprévus…

**Pas besoin de manipuler de l’argent liquide :** vous répartissez virtuellement votre budget pour visualiser ce qu’il vous reste.

## 📥 Télécharger l’application

| 📱 Android | 🖥️ Windows |
|---|---|
| **[Télécharger l’application Android (APK)](https://github.com/bobcatfr63/enveloppe-arthur-apk/releases/download/v0.5.10-beta.1/Enveloppe-Arthur-v0.5.10-beta.apk)** | **[Télécharger la version Windows (ZIP)](https://github.com/bobcatfr63/enveloppe-arthur-apk/releases/download/windows-preview-v0.3/Enveloppe-Arthur-Windows-v0.3-Setup.exe)** |
| Application mobile avec gestion complète du budget | Version d’aperçu pour PC avec gestion locale et consultation du budget sauvegardé sur le cloud |

➡️ **[Voir tous les téléchargements et les nouvelles versions](https://github.com/bobcatfr63/enveloppe-arthur-apk/releases)**

> Les versions actuellement proposées sont des **bêtas / aperçus** : des améliorations et corrections peuvent encore arriver. La version Windows nécessite **.NET Desktop Runtime 8**.

## 🧩 Comment fonctionne le système d’enveloppes ?

Imaginez que vous ayez **1 800 €** à organiser ce mois-ci. Vous pouvez par exemple prévoir :

| Enveloppe | Montant prévu |
|---|---:|
| 🛒 Courses | 350 € |
| 🚗 Carburant | 150 € |
| 🎉 Loisirs | 100 € |
| 🏖️ Vacances | 100 € |
| 💰 Épargne | 150 € |

Ces montants sont **des exemples à personnaliser** : Enveloppe Arthur ne déplace pas votre argent entre vos comptes bancaires.

Quand vous faites une dépense de **45 €** pour les courses, vous l’enregistrez dans l’enveloppe « Courses ». L’application vous indique alors qu’il reste **305 €** sur cette enveloppe.

Vous visualisez ainsi rapidement vos dépenses, sans devoir refaire vos calculs.

## 📱 Enveloppe Arthur sur Android

La version Android est la plus complète à ce jour.

- **Créer ses enveloppes** : partir de zéro ou choisir parmi **22 modèles courants** (courses, maison, enfants, loisirs, carburant, etc.).
- **Personnaliser ses catégories** : renommer une enveloppe ou la retirer de l’affichage tout en conservant son historique.
- **Ajouter ses revenus et ses dépenses** : enregistrer les mouvements et consulter les opérations du mois.
- **Organiser son salaire** : répartir son budget entre les enveloppes, avec une proposition automatique basée sur ses objectifs.
- **Anticiper les charges fixes** : réserver des montants pour les dépenses récurrentes.
- **Gérer les transferts** : déplacer un montant prévu d’une enveloppe vers une autre.
- **Suivre son budget** : visualiser les soldes, les reports d’un mois à l’autre et des statistiques.
- **Sauvegarder ses données** : exporter une sauvegarde locale ou lancer une sauvegarde cloud depuis un compte Supabase.

### Pour commencer sur Android

1. Téléchargez le fichier **APK** depuis le lien ci-dessus.
2. Ouvrez-le sur votre téléphone et autorisez l’installation depuis cette source si Android le demande.
3. Lancez **Enveloppe Arthur** et créez vos premières enveloppes, ou sélectionnez les modèles prédéfinis.
4. Ajoutez votre revenu, répartissez votre budget et enregistrez vos dépenses au quotidien.

**Astuce :** commencez avec seulement quelques enveloppes (courses, transport, loisirs et imprévus), puis ajoutez-en selon vos besoins.

## 🖥️ Enveloppe Arthur sur Windows

La version PC propose actuellement une **première interface de gestion locale** :

- afficher ses enveloppes sur un écran plus grand ;
- créer des enveloppes et saisir des montants dans la version Windows ;
- importer ou exporter des données locales au format JSON ;
- se connecter à son compte cloud ;
- **consulter en lecture seule** les enveloppes et montants d’une sauvegarde Android présente sur Supabase.

### Pour commencer sur Windows

1. Téléchargez le **ZIP Windows** depuis le lien ci-dessus.
2. Décompressez le fichier dans un dossier de votre choix.
3. Lancez **`EnveloppeArthur.Windows.exe`**.
4. Pour consulter une sauvegarde Android, connectez-vous avec le même compte cloud et cliquez sur **« Voir la sauvegarde Android »**.

> **Important :** les enveloppes créées localement dans la version Windows ne sont pas encore synchronisées automatiquement vers Android.

## ☁️ Utiliser Android et Windows ensemble

Enveloppe Arthur propose un compte cloud pour **conserver une sauvegarde du budget Android** et la **consulter depuis Windows**.

Sur Android : ouvrez **Outils et réglages → Compte et synchronisation**, connectez-vous et choisissez **« Sauvegarder toutes mes données dans le cloud »**.

Sur Windows : connectez-vous avec **le même compte**, puis cliquez sur **« Voir la sauvegarde Android »** pour afficher les enveloppes et les totaux de cette sauvegarde.

**À savoir :** cette sauvegarde et cette consultation sont **manuelles**. La modification simultanée du même budget sur Android et Windows et la synchronisation automatique dans les deux sens **ne sont pas encore disponibles**. Ne supprimez pas vos données originales après une sauvegarde cloud.

## ❓ Questions fréquentes

**Faut-il connecter son compte bancaire ?**  
Non. Vous saisissez les revenus et les dépenses dans l’application. Aucun accès bancaire n’est nécessaire.

**Peut-on modifier les enveloppes proposées ?**  
Oui. Les modèles servent de point de départ. Vous choisissez ceux qui vous intéressent et pouvez ensuite les renommer ou les masquer.

**Faut-il obligatoirement un compte cloud ?**  
Non pour utiliser le budget local sur Android. Le compte cloud est nécessaire pour les fonctions liées à Supabase.

**L’application est-elle gratuite ?**  
Les téléchargements proposés ici sont accessibles gratuitement. Le projet utilise des versions de test et ne promet pas encore une synchronisation complète.

**Comment obtenir les nouveautés ?**  
Consultez la page **[Releases](https://github.com/bobcatfr63/enveloppe-arthur-apk/releases)**. La version Android peut également proposer une mise à jour lorsqu’une version plus récente est détectée.

**Une question ou un bug à signaler ?**  
Vous pouvez ouvrir un **[ticket GitHub](https://github.com/bobcatfr63/enveloppe-arthur-apk/issues)** si cette fonctionnalité est disponible.

---

**Enveloppe Arthur — un budget plus clair, une enveloppe à la fois.** 💙
