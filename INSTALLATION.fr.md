# Guide d'installation OPTIMAEUS

## Instructions étape par étape pour toutes les plateformes

---

## 🍎 Installation macOS

### Étape 1: Téléchargement
1. Allez sur la [Dernière version](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Cliquez sur `OPTIMAEUS_1.0.0_aarch64.dmg` (Apple Silicon) ou `OPTIMAEUS_1.0.0_x64.dmg` (Intel)
3. Attendez que le téléchargement se termine

### Étape 2: Installation
1. **Double-cliquez** sur le fichier `.dmg` téléchargé
2. Une fenêtre s'ouvrira montrant l'application OPTIMAEUS
3. **Glissez** l'icône OPTIMAEUS vers le dossier Applications
4. Fermez la fenêtre

### Étape 3: Premier lancement (Important!)
Comme OPTIMAEUS n'est pas de l'App Store, macOS demandera une autorisation:

1. Ouvrez **Finder** → Allez dans **Applications**
2. Trouvez **OPTIMAEUS**
3. **Clic droit** (ou Contrôle-clic) sur OPTIMAEUS
4. Cliquez sur **"Ouvrir"** dans le menu
5. Une boîte de dialogue apparaîtra indiquant que l'app provient d'un développeur non identifié
6. Cliquez sur **"Ouvrir"** pour confirmer

> ⚠️ **Note:** Vous n'avez besoin de faire l'étape du clic droit qu'une seule fois. Après cela, vous pouvez ouvrir OPTIMAEUS normalement.

### Étape 4: Configuration
1. L'application s'ouvrira et vous demandera de créer un **Mot de passe parent**
2. Entrez un mot de passe que vous vous souviendrez (cela protège les paramètres parentaux)
3. Vous êtes prêt à commencer!

---

## 🪟 Installation Windows

### Étape 1: Téléchargement
1. Allez sur la [Dernière version](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Cliquez sur `OPTIMAEUS_1.0.0_x64_en-US.msi` ou `OPTIMAEUS_1.0.0_x64-setup.exe`
3. Attendez que le téléchargement se termine

### Étape 2: Installation
1. **Double-cliquez** sur le fichier `.msi` ou `.exe` téléchargé
2. Windows peut afficher un avertissement de sécurité:
   - Cliquez sur **"Plus d'infos"**
   - Cliquez sur **"Exécuter quand même"**
3. Suivez les invites de l'installateur
4. Choisissez l'emplacement d'installation (par défaut est bien)
5. Cliquez sur **"Installer"**
6. Cliquez sur **"Terminer"** une fois terminé

### Étape 3: Lancement
1. Trouvez OPTIMAEUS dans votre **Menu Démarrer**, ou
2. Double-cliquez sur le **raccourci du bureau** (s'il a été créé)

### Étape 4: Configuration
1. L'application s'ouvrira et vous demandera de créer un **Mot de passe parent**
2. Entrez un mot de passe que vous vous souviendrez
3. Vous êtes prêt à commencer!

---

## 🐧 Installation Linux

### Option A: Ubuntu/Debian (.deb)

1. Téléchargez le fichier `.deb` depuis la [Dernière version](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Ouvrez le Terminal dans le dossier de téléchargement
3. Exécutez:
```bash
sudo dpkg -i OPTIMAEUS_1.0.0_amd64.deb

# Si vous voyez des erreurs de dépendances:
sudo apt-get install -f
```

Lancez depuis le menu de votre application ou exécutez: `optimaeus`

### Option B: Fedora/RHEL (.rpm)

1. Téléchargez le fichier `.rpm` depuis la [Dernière version](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Ouvrez le Terminal dans le dossier de téléchargement
3. Exécutez:
```bash
sudo dnf install OPTIMAEUS_1.0.0_amd64.rpm
# Ou:
sudo rpm -i OPTIMAEUS_1.0.0_amd64.rpm
```

Lancez depuis le menu de votre application ou exécutez: `optimaeus`

### Option C: AppImage (Universel - Pas d'installation nécessaire)

1. Téléchargez le fichier `.AppImage` depuis la [Dernière version](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Ouvrez le Terminal dans le dossier de téléchargement
3. Exécutez:
```bash
# Rendre exécutable
chmod +x OPTIMAEUS_1.0.0_amd64.AppImage

# L'exécuter
./OPTIMAEUS_1.0.0_amd64.AppImage
```

> **Astuce:** Vous pouvez déplacer l'AppImage dans n'importe quel dossier et l'exécuter depuis là. Aucune installation requise!

---

## 🤖 Téléchargement du modèle IA

Après avoir installé OPTIMAEUS, vous devrez télécharger un modèle IA (environ 4-5 Go):

### Étape 1: Ouvrir le Tableau de bord Parent
1. Lancez OPTIMAEUS
2. Entrez votre mot de passe parent
3. Allez dans **Paramètres** ou **Configuration du modèle**

### Étape 2: Télécharger le modèle recommandé
1. L'application affichera les modèles recommandés en fonction de votre ordinateur
2. Cliquez sur **"Télécharger"** à côté du modèle recommandé
3. Attendez le téléchargement (peut prendre 10-30 minutes selon la vitesse d'internet)

### Étape 3: Définir le chemin du modèle
1. Après le téléchargement, l'application demandera où vous avez enregistré le modèle
2. Naviguez vers le fichier `.gguf` téléchargé
3. Cliquez sur **"Sélectionner"** ou **"Ouvrir"**

### Étape 4: Tester que ça fonctionne
1. Allez dans la Salle des Enfants
2. Créez un profil de test
3. Envoyez un message comme "Bonjour!"
4. Si l'IA répond, vous êtes prêt! 🎉

---

## 👨‍👩‍👧‍👦 Configuration des profils enfants

### Ajouter un enfant
1. Ouvrez OPTIMAEUS et connectez-vous en tant que parent
2. Allez dans le **Tableau de bord Parent**
3. Cliquez sur **"Ajouter un enfant"**
4. Entrez le nom de l'enfant
5. Créez un code PIN à 4 chiffres pour eux
6. Cliquez sur **"Enregistrer"**

### Connexion enfant
1. Sur l'écran principal, l'enfant sélectionne son nom
2. Il entre son code PIN à 4 chiffres
3. Il choisit un compagnon (Devoirs, Art, ou Recherche)
4. Il peut commencer à discuter!

---

## 🗑️ Désinstallation d'OPTIMAEUS

### macOS
1. Ouvrez **Finder** → **Applications**
2. Trouvez **OPTIMAEUS**
3. Glissez-le vers la **Corbeille**
4. Videz la Corbeille

Pour supprimer toutes les données:
```bash
rm -rf ~/Library/Application\ Support/com.optimaeus.desktop
```

### Windows
1. Ouvrez **Paramètres** → **Applications** → **Applications installées**
2. Trouvez **OPTIMAEUS**
3. Cliquez sur les **trois points** (⋮) → **Désinstaller**
4. Confirmez la désinstallation

Ou utilisez le Panneau de configuration → Programmes → Désinstaller un programme

### Linux

**Debian/Ubuntu:**
```bash
sudo apt remove optimaeus
```

**Fedora/RHEL:**
```bash
sudo dnf remove optimaeus
```

**AppImage:** Supprimez simplement le fichier AppImage (pas besoin de désinstallation)

Pour supprimer toutes les données:
```bash
rm -rf ~/.local/share/com.optimaeus.desktop
```

---

## ❓ Dépannage

### "L'application ne s'ouvre pas" (macOS)
- Assurez-vous d'avoir fait un **clic droit** et sélectionné "Ouvrir" (voir Étape 3 ci-dessus)
- Essayez: Préférences Système → Sécurité et confidentialité → Cliquez sur "Ouvrir quand même"

### Avertissement "Éditeur inconnu" (Windows)
- C'est normal pour les applications qui ne proviennent pas du Microsoft Store
- Cliquez sur "Plus d'infos" → "Exécuter quand même"

### "L'application est lente" (Windows/Linux)
- C'est attendu - la version actuelle utilise le CPU pour le traitement IA
- Les temps de réponse de 10-30 secondes sont normaux
- macOS est plus rapide car il utilise l'accélération GPU

### "Fichier modèle introuvable"
- Assurez-vous d'avoir téléchargé un fichier modèle `.gguf`
- Vérifiez que le chemin du fichier n'a pas de caractères spéciaux
- Essayez de placer le modèle dans un chemin simple comme `Documents/models/`

### Erreur "Mémoire insuffisante"
- Fermez les autres applications
- Essayez un modèle plus petit (Q4 au lieu de Q6)
- Vous avez besoin d'au moins 8 Go de RAM

---

## 🆘 Besoin d'aide supplémentaire?

Contactez-nous:
- Email: octavie.ploye@timaeus-consulting.com

Nous sommes heureux de vous aider à vous configurer! 😊
