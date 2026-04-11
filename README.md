<div align="center">

# 🏎️ SAAQ Pro : Simulateur Haute-Fidélité v7.5
**Une immersion totale dans l'examen de conduite du Québec. Apprenez par l'expérience, pas par cœur.**

![Header](https://capsule-render.vercel.app/render?type=soft&color=003399&height=200&section=header&text=SAAQ%20PRO%20v7.5&fontSize=80&animation=fadeIn)

[![Version](https://img.shields.io/badge/Version-7.5_Stable-00f2ff?style=for-the-badge&logo=target)](https://github.com/votre-repo)
[![UI](https://img.shields.io/badge/Interface-High_Tech-ff3c00?style=for-the-badge&logo=air-canada)](https://github.com/votre-repo)
[![Region](https://img.shields.io/badge/Region-Quebec_CA-003399?style=for-the-badge&logo=quebec&logoColor=white)](https://www.quebec.ca)

---

### "L'expertise ne s'apprend pas, elle se simule."
*Ce projet n'est pas un simple questionnaire. C'est un simulateur de tableau de bord interactif conçu pour maîtriser les systèmes critiques et la signalisation routière du Québec.*

</div>

## 🛠️ Spécifications Techniques

> [!TIP]
> L'interface utilise un système de **Highlighter Dynamique** pour focaliser l'attention sur les jauges (RPM, Air, Vitesse) lors des questions critiques.

* **Dashboard Engine :** Simulation temps-réel des manomètres (PSI) et du tachymètre.
* **Visual Stack :** Intégration fluide via TailwindCSS et polices futuristes (Orbitron, JetBrains Mono).
* **Sign Index :** Répertoire complet de 100+ panneaux de signalisation catégorisés.
* **Expert System :** Logique de feedback immédiat sur les voyants d'alerte (ABS, Huile, Frein de parc).

---

## 📸 Aperçu du Cockpit

<details>
<summary><b>📐 Architecture de l'interface (Cliquez pour voir)</b></summary>

| Module | Rôle | Technologie |
| :--- | :--- | :--- |
| **Gauges Pods** | Rendu des aiguilles et vitesse | CSS Transforms / JS State |
| **LCD Display** | Alertes systèmes et messages critiques | Dynamic DOM Injection |
| **Status Grid** | Monitoring des capteurs (SVG Libs) | SVG Vector Mapping |

</details>

---

## 🚦 Catégories d'Examen Incluses

- [x] **Systèmes de Freinage à Air :** Gestion de la pression (Manomètres) et alertes sous 60 PSI.
- [x] **Signalisation Routière :** Reconnaissance visuelle haute performance (100 types).
- [x] **Comportement & Lois :** Maîtrise du Code de la sécurité routière du Québec.
- [ ] **Simulateur de Conduite Hivernale :** (Prévu pour la v8.0).

---

## 🚀 Installation & Lancement

Le projet est "Zero-Dependency" (Standalone HTML/JS).

1. **Cloner le projet**
   ```bash
   git clone [https://github.com/votre-utilisateur/SAAQ-Pro-v7.5.git](https://github.com/votre-utilisateur/SAAQ-Pro-v7.5.git)