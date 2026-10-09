# XDK Ouvrir Disque — téléchargements

Logiciel Windows (10 et 11) de **XDK TEAM DEV** pour **voir ce qu'il y a sur un disque sans le formater**, l'ouvrir sans risque, puis le gérer simplement, en français, avec une voix qui guide.

## Télécharger

1. Ouvre la [dernière version](https://github.com/XDTEAMDev/XDK-Ouvrir-Disque-releases/releases/latest).
2. Télécharge **`XDKOuvrirDisque.exe`** (le fichier `.sig` à côté sert seulement à vérifier les mises à jour).
3. Lance-le : Windows demande l'autorisation administrateur, c'est normal (il en a besoin pour lire les disques).

Il faut le **.NET 8 Desktop Runtime** (x64), gratuit chez Microsoft : https://dotnet.microsoft.com/download/dotnet/8.0 (« .NET Desktop Runtime »).

## Ce qu'il fait

- Reconnaît tout seul chaque disque branché et dit ce qu'il contient : vide, Windows, **Xbox 360**, **Linux / NAS**, Xbox One, PS4/PS5, Mac, chiffré, adaptateur USB sans disque…
- Ouvre un disque **en lecture seule**, montre les fichiers des disques Xbox 360 et Linux et les copie sur le PC.
- Formate, crée, supprime, **redimensionne** (barre à faire glisser), **déplace et étend** les partitions, choisit les **lettres**.
- **Clone** un disque vers un autre (même celui de Windows, grâce aux clichés instantanés).
- **Santé et vie du disque** (SMART, vie restante estimée) et **test de surface** en lecture seule.
- Désactive **BitLocker**.
- Ne touche jamais au disque de Windows par erreur : il montre ce qu'il y a dessus et demande de taper « EFFACER » suivi du numéro du disque.

## Mises à jour

Automatiques : à chaque lancement, le logiciel regarde ici s'il existe une nouvelle version, la télécharge, vérifie sa **signature** et redémarre dessus. Un fichier qui n'est pas signé par XDK TEAM DEV est refusé.

## Ce dépôt

Il ne contient que les versions à télécharger de XDK Ouvrir Disque. Les autres logiciels de XDK TEAM DEV ont leurs propres pages.
