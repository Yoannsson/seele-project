# seele-project
Système d'agents cognitifs auto-adaptatifs basé sur les LFM (Liquid Flow Models). Projet exploratoire pour la recherche, la R&amp;D et la construction d'une IA distribuée modulaire.
# ARES — Agent Réplicateur Évolutif Sémantique

## 🌐 Présentation

ARES est un agent IA semi-autonome structuré pour fonctionner au cœur du projet S.E.E.L.E.  
Il a pour but de générer, tester, réviser et apprendre du code Python, en s’appuyant sur un modèle de type LFM (Liquid Flow Model) et une architecture multi-agents.

## 🔍 Objectifs

- Créer un agent IA de génération de code capable de s'auto-améliorer.
- Utiliser des sous-agents spécialisés pour modulariser les tâches (MoE, Buffer, Communication, Récompense...).
- Préparer ARES à générer et superviser d'autres agents.
- Maintenir une structure adaptative et évolutive.

## 🧠 Architecture

ARES est composé des modules suivants :

- `ares.py` : cœur du système, coordonne les sous-agents.
- `lfm_agent.py` : intègre un modèle LFM pour la génération de texte/code.
- `moe_expert.py` : gère la sélection d'experts via un Mixture of Experts.
- `communication_manager.py` : gère les échanges inter-agents.
- `buffer_manager.py` : stocke les données d’apprentissage temporairement.
- `reward_manager.py` : évalue la qualité des réponses avec des scores.
- `test_ares.py` : tests unitaires du système.
- `requirements.txt` : dépendances Python.
- `README.md` : ce fichier.

## ▶️ Lancement

```bash
python ares.py
