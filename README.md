# XDK Gestionnaire Disque — téléchargements

*(ex « XDK Ouvrir Disque » : même logiciel, nouveau nom.)*

Logiciel Windows (10 et 11) de **XDK TEAM DEV** pour **voir ce qu'il y a sur un disque sans le formater**, l'ouvrir sans risque, puis le gérer simplement, en français, avec une voix qui guide.

## Télécharger

1. Ouvre la [dernière version](https://github.com/XDTEAMDev/XDK-Gestionnaire-Disque-releases/releases/latest).
2. Télécharge **`XDKGestionnaireDisque.exe`** (le fichier `.sig` à côté sert seulement à vérifier les mises à jour).
3. Lance-le : Windows demande l'autorisation administrateur, c'est normal (il en a besoin pour lire les disques).

Il faut le **.NET 8 Desktop Runtime** (x64), gratuit chez Microsoft : https://dotnet.microsoft.com/download/dotnet/8.0 (« .NET Desktop Runtime »).

## Clé (gratuite)

Depuis la 1.7.0, il faut une **clé** pour utiliser le logiciel (1 mois ou à vie) :

1. Ouvre le logiciel : il affiche le **code de ton PC** (par exemple `ABCD-EFGH-JKLM`). Copie-le.
2. Rejoins le **Discord XDK TEAM DEV** : https://discord.gg/zEC35KSuxt, choisis ta langue, puis va dans la catégorie 💽 XDK GESTIONNAIRE DISQUE, salon 🔑・demande-de-clé.
3. Clique sur « Demander une clé » et colle ton code PC. L'équipe valide ta demande et t'envoie ta clé en **message privé**.
4. Colle la clé dans le logiciel et clique sur « Activer ».

Une clé ne marche que sur le PC de son code. Les mises à jour arrivent toujours toutes seules, même sans clé.

## Ce qu'il fait

- Reconnaît tout seul chaque disque branché et dit ce qu'il contient : vide, Windows, **Xbox 360**, **Linux / NAS**, Xbox One, PS4/PS5, Mac, chiffré, adaptateur USB sans disque…
- Ouvre un disque **en lecture seule**, montre les fichiers des disques Xbox 360 et Linux et les copie sur le PC.
- Formate, crée, supprime, **redimensionne** (barre à faire glisser), **déplace et étend** les partitions, choisit les **lettres**.
- **Clone** un disque vers un autre (même celui de Windows, grâce aux clichés instantanés).
- **Santé et vie du disque** (SMART, vie restante estimée) et **test de surface** en lecture seule.
- Désactive **BitLocker**.
- Sa propre **Gestion des disques** : tout ce que fait celle de Windows (en ligne / hors ligne, initialiser, convertir GPT ↔ MBR, partition active, renommer, lettres, **disques virtuels** .vhdx), sans quitter le logiciel.
- Ne touche jamais au disque de Windows par erreur : il montre ce qu'il y a dessus et demande de taper « EFFACER » suivi du numéro du disque.

## Mises à jour

Automatiques : à chaque lancement, le logiciel regarde ici s'il existe une nouvelle version, la télécharge, vérifie sa **signature** et redémarre dessus. Un fichier qui n'est pas signé par XDK TEAM DEV est refusé.

## Ce dépôt

Il ne contient que les versions à télécharger de XDK Gestionnaire Disque. Les autres logiciels de XDK TEAM DEV ont leurs propres pages.
