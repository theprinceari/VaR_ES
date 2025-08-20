# 📊 Projet VaR & Expected Shortfall (ES)

## 🔍 Description
Ce projet implémente la mesure du risque d'un portefeuille d'actions via deux indicateurs financiers :
- **VaR (Value-at-Risk)** : perte maximale probable sur un horizon donné, pour un certain niveau de confiance.
- **ES (Expected Shortfall / CVaR)** : perte moyenne attendue au-delà de la VaR, plus prudente.

Le projet montre également comment simuler le portefeuille et calculer ces métriques via Monte Carlo.

---

## 🛠️ Contenu du repo

- `VaR_ES.ipynb` → Notebook Python contenant :
  - Téléchargement de données réelles (AAPL, MSFT, SPY)
  - Calcul des rendements du portefeuille
  - Calcul de VaR et ES (historique, paramétrique, Monte Carlo)
  - Visualisations des résultats
- `rapport.pdf` → Explication mathématique détaillée des concepts
- `README.md` → Ce fichier

---

## ▶️ Utilisation

### 1. Cloner le repo
```bash
git clone https://github.com/TonPseudo/VaR_ES.git
cd VaR_ES

2. Installer les dépendances

pip install numpy pandas yfinance matplotlib scipy

3. Lancer le notebook

Ouvrir dans Jupyter ou Google Colab :

jupyter notebook VaR_ES.ipynb

📊 Résultats attendus

    Rendements quotidiens du portefeuille

    VaR et ES calculés par trois méthodes :

        Historique

        Paramétrique

        Monte Carlo (bonus)

    Visualisations comparatives des méthodes

📌 Références

    Jorion, P. (2007). Value at Risk: The New Benchmark for Managing Financial Risk.

    Glasserman, P. (2003). Monte Carlo Methods in Financial Engineering
