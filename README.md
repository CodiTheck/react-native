# React Native

## Quelques commandes utiles
### Changer de nom de projet

```sh
sudo yarn global add react-native-rename

```
Pour changer le nom du projet :
```sh
react-native-rename "New Name" -b com.coditheck.app_name

```
> **NOTE**: ce paquet ne tentera pas de renommer correctement les artefacts de construction tels que ios/build ou les cibles d'installation de Cocoa Pod. Après avoir renommé votre projet, vous devriez probablement nettoyer, puis construire et réinstaller vos dépendances pour qu'il fonctionne correctement avec votre nouveau nom.


