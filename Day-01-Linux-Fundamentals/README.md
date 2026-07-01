# Day 01 – Linux Fundamentals

## Objectif

Découvrir Linux et installer Ubuntu Server.

## Environnement

- VirtualBox 7.x
- Ubuntu Server 24.04 LTS
- RAM : 4 Go
- CPU : 2
- Disque : 30 Go

## Ce que j'ai appris

- Le rôle d'un système d'exploitation
- Le Kernel Linux
- Les distributions Linux
- Les commandes de base
- La structure du système de fichiers

## Commandes utilisées

```bash
pwd
ls
cd
mkdir
touch
cp
mv
rm
history
whoami
hostname
uname -a
```

## Exercices réalisés

### Création de l'arborescence

```bash
mkdir -p DevOps/{Linux,Docker,AWS,Terraform,Kubernetes}
```

Résultat :

```text
DevOps/
├── Linux
├── Docker
├── AWS
├── Terraform
└── Kubernetes
```

## Captures d'écran

### Installation

![Installation](screenshots/01-installation.png)

### Premier démarrage

![Ubuntu](screenshots/02-terminal.png)

### Exercices

![Exercices](screenshots/03-exercices.png)

## Difficultés rencontrées

J'ai eu des difficultés à distinguer les chemins absolus et les chemins relatifs.

Après plusieurs exercices, cette notion est devenue plus claire.

## Conclusion

Cette première journée m'a permis de comprendre pourquoi Linux est la base des infrastructures modernes et de prendre en main le terminal Linux.
