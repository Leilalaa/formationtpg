# TP2git : Memo git

Memo sur les commandes utiles à utiliser dans **git**

- initialiliser un repository **git** :
```git
git init
```
- ajouter les nouveaux fichiers ou les fichiers modifiés au **commit** :
```git
git add . //tout ajouter
git add <File> // ajouter un fichier spécifique
```
- commiter un commit avec un message:
```git
git commit -m "message"
```
- afficher le statut (nouveaux fichiers, fichiers modifiés..) du repository:
```git
git statut
```
- afficher les modifications depuis le dernier commit:
```git
git diff
```
- afficher le log du repository:
```git
git log
git log --decorate --graph //meilleure présentation
```
- créer une branche :
```git
git branch <branche>
```
- changer de branche :
```git
git checkout <branche>
```
- merge une branche :
```git
git merge <branche>
```
