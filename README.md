# 🔐 LAB 4 — Analyse Statique APK (OWASP MSTG)


## 🎯 Objectif
Ce laboratoire vise à analyser statiquement une application Android (APK) afin d’identifier les vulnérabilités de sécurité, en se basant sur le standard OWASP Mobile Security Testing Guide (MSTG).

## 🛠️ Outils utilisés
- JADX v1.5.0
- dex2jar v2.4
- JD-GUI v1.6.6
- Ubuntu Server minimal

## 🔍 Résumé des vulnérabilités
- 🔴 Secret stocké en clair dans le code
- 🔴 Vérification du secret côté client
- 🟠 Protection root contournable
- 🟠 Détection du mode debug exploitable
- 🟡 allowBackup activé
- 🔵 minSdkVersion trop bas



## ⚠️ Disclaimer
Ce projet est réalisé dans un cadre strictement académique.  
L’APK analysé provient d’un challenge OWASP et ne contient aucune donnée sensible réelle.
