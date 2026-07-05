# 🚀 Math Invaders — Beta

> Un shoot'em up éducatif où tu défends la Terre à coups de bonnes réponses.
> Version **0.1.0-beta** — merci de tester ! 🙏

---

## 📥 Télécharger

Va dans **[Releases](../../releases/latest)** et prends l'archive de ton système :

| Système | Fichier | Notes |
|---|---|---|
| 🪟 **Windows** (10/11, 64 bits) | [`MathInvaders-Windows.zip`](../../releases/latest/download/MathInvaders-Windows.zip) | Voir « Windows » ci-dessous |
| 🐧 **Linux** (64 bits) | [`MathInvaders-Linux.tar.gz`](../../releases/latest/download/MathInvaders-Linux.tar.gz) | |
| 🍎 **macOS** (Intel + Apple Silicon) | [`MathInvaders-macOS.zip`](../../releases/latest/download/MathInvaders-macOS.zip) | Voir « macOS » ci-dessous |

> ⚠️ **Ce sont des builds de test non signés.** Ton système va probablement râler (« éditeur inconnu »). C'est normal — le jeu est sain, il n'est juste pas signé numériquement (ça coûte cher, inutile pour une beta). Suis les étapes ci-dessous pour l'ouvrir.

---

## ▶️ Installer & lancer

### 🪟 Windows
1. Décompresse le `.zip` (clic droit → **Extraire tout**).
2. Double-clique sur **`MathInvaders.exe`**.
3. Windows affiche un écran bleu **« Windows a protégé votre PC »** → clique sur **« Informations complémentaires »** puis **« Exécuter quand même »**.

### 🍎 macOS
1. Décompresse le `.zip` → tu obtiens **`Math Invaders.app`**.
2. Au **premier lancement**, un double-clic sera **bloqué** (« développeur non identifié »). Il faut donc :
   - **Clic droit** (ou Ctrl+clic) sur `Math Invaders.app` → **Ouvrir** → dans la fenêtre, re-clique **Ouvrir**.
   - Si macOS refuse toujours (« l'app est endommagée »), ouvre **Terminal** et lance cette commande, puis réessaie :
     ```
     xattr -cr "/chemin/vers/Math Invaders.app"
     ```
     (astuce : tape `xattr -cr ` puis glisse-dépose l'app dans le Terminal pour insérer le chemin, et Entrée.)

### 🐧 Linux
```bash
tar xzf MathInvaders-Linux.tar.gz
chmod +x MathInvaders.x86_64
./MathInvaders.x86_64
```

---

## 🎮 Contrôles

| Touche | Action |
|---|---|
| **← →** | Se déplacer |
| **Espace** | Tirer / valider la réponse / arme spéciale (pendant la fenêtre de boss) |
| **B** | Arrêt du temps (quand tu en as en stock) |
| **F11** | Plein écran ↔ fenêtré |
| **Échap** | Pause / reprendre / retour |

Tout se joue au clavier. Le jeu démarre en plein écran (F11 pour repasser en fenêtré).

---

## 🐛 Remonter un bug ou donner ton avis

**C'est le plus important pour moi !** Même un truc minuscule, dis-le.

### 👉 [Formulaire de retour (2 min, aucun compte requis)](__FORM_URL__)

Dans ton retour, essaie de préciser :
- Ton **système** (Windows / Mac / Linux)
- **Ce que tu faisais** (niveau, boss, menu…)
- **Ce qui a merdé** vs ce que tu attendais
- Une **capture d'écran** si possible (Windows : `Win+Maj+S` · Mac : `Cmd+Maj+4`)

---

## ⚙️ Config & limites connues

- **64 bits uniquement.** Rendu en OpenGL (compatible vieilles machines).
- Builds **non signés** (voir plus haut) — pas de virus, juste pas de certificat payant.
- macOS : testé sur Intel et Apple Silicon via build universel, mais **je n'ai pas de Mac pour tester en vrai** → tes retours Mac sont précieux.

Merci d'avoir joué. 💛
