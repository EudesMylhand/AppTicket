Voici ton texte **converti proprement en Markdown**, prêt à être utilisé dans un fichier `README.md` ou autre documentation :

```markdown
# 📄 Documentation de l'Application de Visualisation CSV pour Impression

## Table des Matières
1. [Introduction](#introduction)
2. [Fonctionnalités](#fonctionnalités)
3. [Guide d'Utilisation](#guide-dutilisation)
4. [Format des Fichiers](#format-des-fichiers)
5. [Paramètres Personnalisables](#paramètres-personnalisables)
6. [Options d'Impression](#options-dimpression)
7. [Limitations](#limitations)
8. [FAQ](#faq)

---

## 🧭 Introduction

Cette application web permet de visualiser et d'imprimer des données provenant de fichiers CSV ou Excel dans un format optimisé pour l'impression sur papier A4. Elle offre une grille de 13 lignes par 5 colonnes avec un contrôle précis de la mise en page.

---

## ⚙️ Fonctionnalités

### 🔹 Principales
- **Importation de fichiers** : CSV, XLS, XLSX
- **Prévisualisation ajustable** : zoom de 50% à 150%
- **Contrôle de la mise en page** :
  - Padding de la page (cm/px)
  - Taille des cellules (hauteur en cm/px)
  - Taille de police (px/pt)
- **Impression optimisée** : format A4 avec sauts de page automatiques

### 🔸 Techniques
- Détection automatique des séparateurs (virgule, point-virgule, tabulation, barre verticale)
- Prise en charge des caractères spéciaux
- Affichage responsive pour la prévisualisation

---

## 📘 Guide d'Utilisation

### 1. Importation des données
1. Cliquez sur "Sélectionner un fichier"
2. Choisissez un fichier CSV ou Excel
3. Les données s'affichent automatiquement dans la zone de prévisualisation

### 2. Personnalisation de l'affichage
Utilisez les contrôles dans le panneau de configuration pour :
- **Padding** : Espace autour du contenu (1cm par défaut)
- **Cellules** : Hauteur des cellules (80px par défaut)
- **Police** : Taille du texte (12px par défaut)
- **Zoom** : Ajustez le niveau de zoom (100% par défaut)

Cliquez sur **"Appliquer les modifications"** pour mettre à jour l'affichage.

### 3. Impression
1. Cliquez sur le bouton **"Imprimer"**
2. Dans le dialogue d'impression :
   - Vérifiez que le format est réglé sur A4
   - Activez les marges personnalisées si nécessaire
3. Lancez l'impression

---

## 📂 Format des Fichiers

### Fichiers CSV acceptés
- Séparateurs : `,` `;` `|` ou tabulation
- Encodage : UTF-8 recommandé
- Première ligne : en-têtes des colonnes

**Exemple :**
```

IMSI,MSISDN,Status
123456789,0612345678,Actif
987654321,0698765432,Inactif

```

### Fichiers Excel acceptés
- Formats : `.xls`, `.xlsx`
- La première feuille du classeur sera utilisée

---

## 🧪 Paramètres Personnalisables

| Paramètre        | Options       | Valeur par défaut | Description                         |
|------------------|---------------|-------------------|-------------------------------------|
| Padding          | 0-10 cm/px    | 1cm               | Marge intérieure des pages          |
| Hauteur cellules | 10-200 px/cm  | 80px              | Hauteur de chaque cellule           |
| Taille police    | 6-24 px/pt    | 12px              | Taille du texte dans les cellules   |
| Zoom             | 50-150%       | 100%              | Niveau de zoom de la prévisualisation |

---

## 🖨️ Options d'Impression

Pour des résultats optimaux :
- **Orientation** : Portrait
- **Format du papier** : A4
- **Marges** : Par défaut (ou minimales)
- **Options** :
  - Activer les arrière-plans (pour les couleurs d'en-tête)
  - Désactiver les en-têtes et pieds de page du navigateur

---

## ⚠️ Limitations

1. **Taille des fichiers** :
   - Limité par la mémoire du navigateur
   - Recommandé : moins de 10 000 lignes

2. **Colonnes affichées** :
   - Seules les 3 premières colonnes sont mises en avant
   - Les autres colonnes sont accessibles mais moins visibles

3. **Compatibilité** :
   - Navigateurs modernes (Chrome, Firefox, Edge)
   - Non testé sur Internet Explorer

---

## ❓ FAQ

**Q: Pourquoi certaines données ne s'affichent-elles pas correctement ?**  
**R:** Vérifiez le séparateur utilisé dans votre fichier CSV. Si le problème persiste, essayez d'enregistrer votre fichier en UTF-8.

**Q: Comment imprimer uniquement certaines pages ?**  
**R:** Dans le dialogue d'impression de votre navigateur, spécifiez la plage de pages souhaitée.

**Q: Puis-je sauvegarder mes paramètres ?**  
**R:** Non, les paramètres ne sont pas sauvegardés entre les sessions. Vous devez les reconfigurer à chaque utilisation.

**Q: L'application prend en charge quelles versions d'Excel ?**  
**R:** Toutes les versions (anciens `.xls` et modernes `.xlsx`).

---

📫 **Pour toute question supplémentaire**, veuillez consulter le code source ou contacter le développeur : eudesmylhand.
```


