# Alternative Controller – Visual Particle Experience  
*Unreal Engine 5 – Niagara – Controller Alternatif*

![Status](https://img.shields.io/badge/Prototype-Yes-blue)
![Engine](https://img.shields.io/badge/Engine-UE5-black)
![Controller](https://img.shields.io/badge/Controller-Alternative-green)

---

## Description du projet

![](https://media.discordapp.net/attachments/1291787537907454064/1441390119931347006/Capture_decran_2025-11-21_122135.png?ex=69219ea8&is=69204d28&hm=9d3d9280ed86569c426405492970fbffe33a82dd94ece85e793834307c6ffcd8&=&format=webp&quality=lossless&width=1711&height=800)

Ce projet propose une expérience visuelle mettant en avant **Niagara (UE5)**.  
Le joueur contrôle une **sphère de particules colorées** évoluant dans un environnement **entièrement noir**, uniquement structuré par des **néons lumineux** délimitant la carte.

![](https://media.discordapp.net/attachments/1291787537907454064/1441390032333312010/Video_sans_titre_Realisee_avec_Clipchamp.gif?ex=69219e93&is=69204d13&hm=3ce4e5d53fb4023bb5bd3fa8bc586e5fb5367ccbda67d05083fcca10bfbc394b&=&width=533&height=300)

En traversant certaines **zones de lumière**, la sphère absorbe leurs **couleurs**, créant un contraste fort au sein de l'obscurité.

---

## Objectifs

- Mettre en scène les capacités visuelles de **Niagara**  
- Créer un environnement minimaliste basé sur la lumière  
- Expérimenter avec un **controller alternatif physique**

---

## Controller Alternatif

![](https://media.discordapp.net/attachments/1291787537907454064/1441390031670607922/20251121_121033.jpg?ex=69219e93&is=69204d13&hm=d32560aba1b50c2a715eaf9cf56f5a1e32fa3b8e3c046e0fc8ba27999604a3f0&=&format=webp&width=1730&height=799)

### 🔸 Déplacement — Souffle + Ballon  
Le joueur souffle dans un ballon qui, en se gonflant, presse un **bouton physique**.  
Lorsque le bouton s’active, la sphère avance.

![](https://media.discordapp.net/attachments/1291787537907454064/1441390120933785610/Capture_decran_2025-11-21_122723.png?ex=69219ea8&is=69204d28&hm=4dcbc36e1ce882432f135f09afc40aed4134d0e5a8cfe89055bf7e3c9a1a51f1&=&format=webp&quality=lossless&width=1154&height=646)

**Logique :** interaction basée sur le **flux d’air** et la mise sous pression.

### 🔸 Rotation — Volant manuel  
Un **volant physique** permet de tourner à droite et à gauche.

![](https://media.discordapp.net/attachments/1291787537907454064/1441390032001826858/Capture_decran_2025-11-21_122627.png?ex=69219e93&is=69204d13&hm=4d77a20ecce72f534f17484334394f31d6ecbbd3c119086aff6d176a3972cf86&=&format=webp&quality=lossless&width=1150&height=624)

---

## Gameplay

- Observer les mouvements des particules de la sphère dans un monde sombre et silencieux
- Utiliser les **néons** comme repères et limites
- Changer de couleur en traversant les zones lumineuses  
- Jouer physiquement : souffler, tourner, manipuler le controller

---

## Technologies utilisées

| Technologie | Utilisation |
|------------|-------------|
| **UE5** | Moteur du jeu |
| **Niagara** | Particules & effets visuels |
| **Microcontroller / Capteurs** | Inputs & carte mère |
| **Prototype en carton** | Structure physique actuelle |

---

## Axes d'amélioration

### 1. Capteur d’air / pression  
Remplacer le ballon par :  
- un **capteur de pression différentielle**, ou  
- un **capteur de flux d’air**.

 Objectif : **précision**, **durabilité**, **hygiène**, meilleure **réactivité**.

### 2. Structure du controller  

![](https://media.discordapp.net/attachments/1291787537907454064/1441390120518418625/Capture_decran_2025-11-21_122627.png?ex=69219ea8&is=69204d28&hm=2dd04e7408e39f438fdfbdc75b33906a9e7c077b693429c50d10c1d0afd46fbe&=&format=webp&quality=lossless&width=765&height=800)

Le controller est actuellement en **carton**.  
Une future version pourrait inclure :

- **Structure imprimée en 3D**  
- Composants internes mieux intégrés à la structure
- Amélioration de l’ergonomie générale  

 Objectif : **solidité**, **qualité**.
