# FCSC 2024 Blind Attack

Vous êtes en train de jouer votre premier CTF en mode Attack/Defense, et… c’est LA PANIQUE ! Le jeu a commencé depuis à peine 45 minutes, et votre équipe subit des attaques de tous les côtés, tous les services sont déjà down sauf un : vous ne savez pas si vous devez patcher, si vous devez attaquer, ou si vous devez redevenir un être humain normal et simplement abandonner. Tout s’embrouille dans votre esprit, tous vos repères ont disparu, vous ne savez plus comment vous vous appelez.

Vous reprenez un café (ok, vu le stress, c’était pas la meilleure idée), mais vous décidez de vous diriger vers l’outil mis à disposition de l’équipe pour l’analyse des flots réseaux. Cet outil (Shovel) permet de visualiser tous les flots TCP/UDP qui transitent sur la machine à défendre. Vous êtes en charge du service appelé *blind* sur cet outil, et sans même regarder le code de ce service, vous décidez de simplement reproduire les attaques que les autres équipes utilisent pour voler vos flags.

Votre objectif, voler le flag d’une équipe à ce tick de jeu (dans le scénario Hackropole, le flag sera constant). Le *flag ID* correspondant donné par les admins du CTF est : */fcsc/ddJ565eGcAPFVkHZZFqXtrYe2vmVUQv*.

Shovel : http://localhost:8000/
Service de l’équipe adverse : *nc localhost 4000*
Flag ID : */fcsc/ddJ565eGcAPFVkHZZFqXtrYe2vmVUQv*

![blind-attack.jpg](blind-attack.jpg)

Auteur : Cryptanalyse

Origine : [Blind Attack](https://hackropole.fr/fr/challenges/pwn/fcsc2024-pwn-blind-attack/)


-----------
## Connectez vous
Shovel : http://localhost:8000/

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc blind-attack.cyrhades.fr 4000

-----------

## Ou directement avec netcat
> nc localhost 4000


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-pwn-blind-attack.git

> cd fcsc2024-pwn-blind-attack


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2024-pwn-blind-attack/