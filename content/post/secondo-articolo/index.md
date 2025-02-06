---
title: Installare Manjaro su Termux con proot-distro senza root
description: Guida passo passo per installare Manjaro su Termux utilizzando proot-distro.
date: 2025-02-06
image: 1.png
---



## Introduzione

Manjaro è una distribuzione basata su Arch Linux, in questa guida vedremo come installarlo all'interno di Termux utilizzando `proot-distro`, senza bisogno dei permessi di root.

## Requisiti

- **Termux** installato (meglio dalla versione F-Droid per aggiornamenti regolari)
- **Spazio libero** sufficiente per l'installazione
- **Connessione a Internet** stabile

##  Aggiornare Termux 

Prima di tutto, apri Termux e aggiorna i pacchetti eseguendo:

```bash
pkg update && pkg upgrade
```


## installa proot-distro con pkg

```bash
pkg install proot-distro
```
## oppure con git
 
```bash
pkg install git
git clone https://github.com/termux/proot-distro
cd proot-distro
./install.sh
```
## visualizza elenco distro

```bash
proot-distro list
```

![Image 2](2.jpg)

## installa manjaro

```bash
proot-distro install manjaro
```
![Image 3](3.jpg)

## login
 
```bash
proot-distro login manjaro
```
## oppure
 
```bash
pd login manjaro
```
![Image 4](4.jpg)

## Guarda il video

[Guarda il video su YouTube](https://youtu.be/ONSiOiFmYEc?si=DtZX241fhVq5HX1M)


# Io uso archlinux

![Image 5](5.jpg)

```markdown

```


Grazie per aver letto.
