# 🔢 Handwritten Digits Recognition System

Un système intelligent de reconnaissance de chiffres manuscrits avec segmentation automatique multi-lignes et analyse de confiance.


## ✨ Fonctionnalités

- 🔍 **Segmentation automatique** : Détecte et sépare les chiffres individuels
- 📝 **Multi-lignes** : Traite des documents avec plusieurs lignes de chiffres
- 🎯 **Haute précision** : Modèles ML optimisés (KNN, SVM, Random Forest)
- 📊 **Analyse de confiance** : Score de fiabilité pour chaque prédiction
- 🖼️ **Prétraitement avancé** : Amélioration automatique de la qualité d'image
- 📈 **Visualisation complète** : Résultats détaillés avec graphiques
- 💾 **Export multi-format** : TXT, JSON, CSV
- 🚀 **Traitement par lot** : Analyse de multiples images

## 🚀 Installation Rapide

```bash
# Cloner le repository
git clone https://github.com/votre-username/handwritten-digits-recognition.git
cd handwritten-digits-recognition

# Installer les dépendances
pip install -r requirements.txt

# Installation en mode développement
pip install -e .
```

## 📖 Utilisation

### Exemple Simple

```python
from digit_recognition import DigitRecognitionSystem

# Initialiser le système
system = DigitRecognitionSystem()

# Charger un modèle pré-entraîné
system.load_model('models/trained_model.pkl')

# Traiter une image
predictions, confidences = system.process_multi_digit_image('your_image.jpg')

print(f"Chiffres détectés: {''.join(map(str, predictions))}")
```


## 📊 Résultats

| Métrique | Score |
|----------|-------|
| Précision | 94.2% |
| Recall | 93.8% |
| F1-Score | 94.0% |
| Confiance moyenne | 0.89 |


## 🙏 Remerciements

- Dataset MNIST pour l'entraînement initial
- Communauté OpenCV pour les outils de traitement d'image
- Scikit-learn pour les algorithmes ML

---

⭐ **N'hésitez pas à donner une étoile si ce projet vous a aidé !**

---