# Modèles ProVerif pour le pastillage

## Comment lancer les modèles ?

1. Installer [ProVerif](https://bblanche.gitlabpages.inria.fr/proverif/) si nécessaire
2. Se déplacer dans le dossier de la variante souhaitée (`side/`, ...)
3. Puis lancer les modèles :
  - `proverif -lib common.pvl privacy.pv # for privacy`
  - `proverif -lib common.pvl verifiability.pv # for verifiablity`

## Configuration

### Définir les scenarios de corruption

1. `status_server` to `honest` or `corrupt`.
2. `status_reg` to `honest` or `corrupt`.

### Définir la propriété à prouver

Set `property` to `X` or `Xattrs`

## Résultats

TODO
