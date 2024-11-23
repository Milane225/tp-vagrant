# Création de notre première machine virttuelle

## Pré-requis
==> Installation de VirtualBox
==> Installation de Vagrant

## Etape 1
Ouvrir la console dans l'emplacement du dossier Vagrant

## Initialiser Vagrant avec une image système
````
vagrant init ubuntu/bionic64
````

## Créer le Vagrantfile (Création de la VM)
````
vagrant up
````

## Vérification des machines déployées
````
vagrant global-status
````

## statut des déploiements par rapport au dossier ou on se trouve, ou il y a le fichier vagrantfile
````
status
````

## Connexion à la VM
````
vagrant ssh
````

## Arrêter la VM
````
vagrant halt
````

## Supprimer la VM
````
vagrant destroy
````
