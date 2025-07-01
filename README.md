# 🎓 CV_Template - CV LaTeX sobre et modifiable

Un template de CV en LaTeX pensé pour les étudiants, développeurs ou profils tech qui veulent **postuler à des offres ciblées efficacement**.

✅ Lisible par les ATS  
✅ Sobre, clair et pro  
✅ Facilement modifiable ligne par ligne avec ChatGPT  
✅ Automatisable avec un script Python si besoin

---

## 🧠 Pourquoi ce template ?

J’ai créé ce CV pour pouvoir :
- Adapter rapidement chaque candidature à une offre précise
- Modifier le contenu sans casser la mise en page
- Automatiser ou déléguer certaines parties (à GPT ou un script)
- Avoir un CV stable et cohérent dans le temps

---

## 📁 Contenu du repo

- `CV_Template.tex` : le fichier LaTeX principal
- `avatar.jpg` : image de profil incluse dans le template
- `google.png` : exemple d’icône entreprise ou projet
- `README.md` : ce fichier

---

## 🚀 Comment utiliser ce template

### 💻 Option 1 : en local

1. Installe une distribution LaTeX (TeX Live ou MiKTeX)
2. Compile `CV_Template.tex` avec ton éditeur préféré (Texmaker, Overleaf Desktop, VS Code...)

### ☁️ Option 2 : via [Overleaf](https://www.overleaf.com/)

1. **Télécharge le repo en `.zip`** (`Code > Download ZIP`)
2. Sur Overleaf, clique sur **“New Project” > “Upload Project”**
3. Importez l’archive `.zip` complète

---

## 🧰 Personnalisation

Tu peux modifier :
- Les couleurs, sections et icônes
- Les blocs (expériences, projets, compétences…)
- Les images si tu veux en ajouter (profil ou logos)

---

## 🤖 Utilisation avec GPT

Tu peux :
1. Copier le contenu du `.tex`
2. Ajouter une offre d’emploi
3. Demander à GPT d’adapter le CV (projets, compétences, formulation…)

🧩 Idéal pour générer plusieurs versions ciblées très rapidement.

---

## 🔧 Automatisation (à venir)

Je prévois de publier un script Python permettant :
- D’importer un fichier `.json` ou `.csv` de données (projets, expériences…)
- De générer un CV `.pdf` personnalisé automatiquement

---

## 📌 Pour aller plus loin

Si tu veux une **version modifiée** du template, un **guide rapide**, ou une **démo**, Ouvre une “issue” sur ce repo et on regarde ça ensemble.  
Je peux aussi t’aider à adapter le template à ton profil ou ton secteur.

---

## 📎 Exemple d’ajout d’une expérience

Pour ajouter une expérience, supprime la ligne de remplissage `\vspace{...}` et remplace-la par :
```
\section{EXPÉRIENCES}

\textbf{Développeur Full Stack} \hfill Mars 2023 – Août 2023\
\textcolor{secondary}{\href{https://www.devfusion.io}{www.devfusion.io}} \hfill \textcolor{secondary}{Lyon, France}
\begin{itemize}[leftmargin=*, itemsep=1pt]
\item Conception d’une application de gestion de stock en Node.js et React
\item Déploiement sur AWS avec CI/CD via GitHub Actions
\item Optimisation des performances backend (-30 % sur les temps de réponse)
\end{itemize}
```

## 📄 Licence

Ce template est open source (MIT).  
Utilisation libre à des fins personnelles ou professionnelles, à condition de ne pas le revendre en l’état.

---

**Créé par Rabah**
