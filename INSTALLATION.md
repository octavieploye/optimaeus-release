# OPTIMAEUS Installation Guide

## Step-by-Step Instructions for All Platforms

---

## 🍎 macOS Installation

### Step 1: Download
1. Go to the [Latest Release](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Click on `OPTIMAEUS_1.0.0_aarch64.dmg` (Apple Silicon) or `OPTIMAEUS_1.0.0_x64.dmg` (Intel)
3. Wait for download to complete

### Step 2: Install
1. **Double-click** the downloaded `.dmg` file
2. A window will open showing the OPTIMAEUS app
3. **Drag** the OPTIMAEUS icon to the Applications folder
4. Close the window

### Step 3: First Launch (Important!)
Since OPTIMAEUS is not from the App Store, macOS will ask for permission:

1. Open **Finder** → Go to **Applications**
2. Find **OPTIMAEUS**
3. **Right-click** (or Control-click) on OPTIMAEUS
4. Click **"Open"** from the menu
5. A dialog will appear saying the app is from an unidentified developer
6. Click **"Open"** to confirm

> ⚠️ **Note:** You only need to do the right-click step once. After that, you can open OPTIMAEUS normally.

### Step 4: Set Up
1. The app will open and ask you to create a **Parent Password**
2. Enter a password you'll remember (this protects parent settings)
3. You're ready to start!

---

## 🪟 Windows Installation

### Step 1: Download
1. Go to the [Latest Release](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Click on `OPTIMAEUS_1.0.0_x64_en-US.msi` or `OPTIMAEUS_1.0.0_x64-setup.exe`
3. Wait for download to complete

### Step 2: Install
1. **Double-click** the downloaded `.msi` or `.exe` file
2. Windows may show a security warning:
   - Click **"More info"**
   - Click **"Run anyway"**
3. Follow the installer prompts
4. Choose installation location (default is fine)
5. Click **"Install"**
6. Click **"Finish"** when done

### Step 3: Launch
1. Find OPTIMAEUS in your **Start Menu**, or
2. Double-click the **desktop shortcut** (if created)

### Step 4: Set Up
1. The app will open and ask you to create a **Parent Password**
2. Enter a password you'll remember
3. You're ready to start!

---

## 🐧 Linux Installation

### Option A: Ubuntu/Debian (.deb)

1. Download the `.deb` file from [Latest Release](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Open Terminal in the download folder
3. Run:
```bash
sudo dpkg -i OPTIMAEUS_1.0.0_amd64.deb

# If you see dependency errors:
sudo apt-get install -f
```

Launch from your application menu or run: `optimaeus`

### Option B: Fedora/RHEL (.rpm)

1. Download the `.rpm` file from [Latest Release](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Open Terminal in the download folder
3. Run:
```bash
sudo dnf install OPTIMAEUS_1.0.0_amd64.rpm
# Or:
sudo rpm -i OPTIMAEUS_1.0.0_amd64.rpm
```

Launch from your application menu or run: `optimaeus`

### Option C: AppImage (Universal - No Install Needed)

1. Download the `.AppImage` file from [Latest Release](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Open Terminal in the download folder
3. Run:
```bash
# Make it executable
chmod +x OPTIMAEUS_1.0.0_amd64.AppImage

# Run it
./OPTIMAEUS_1.0.0_amd64.AppImage
```

> **Tip:** You can move the AppImage to any folder and run it from there. No installation required!

---

## 🤖 Downloading the AI Model

After installing OPTIMAEUS, you'll need to download an AI model (about 4-5 GB):

### Step 1: Open Parent Dashboard
1. Launch OPTIMAEUS
2. Enter your parent password
3. Go to **Settings** or **Model Configuration**

### Step 2: Download Recommended Model
1. The app will show recommended models based on your computer
2. Click **"Download"** next to the recommended model
3. Wait for download (may take 10-30 minutes depending on internet speed)

### Step 3: Set Model Path
1. After download, the app will ask where you saved the model
2. Navigate to the downloaded `.gguf` file
3. Click **"Select"** or **"Open"**

### Step 4: Test It Works
1. Go to Kid's Room
2. Create a test profile
3. Send a message like "Hello!"
4. If the AI responds, you're all set! 🎉

---

## 👨‍👩‍👧‍👦 Setting Up Kid Profiles

### Add a Child
1. Open OPTIMAEUS and log in as parent
2. Go to **Parent Dashboard**
3. Click **"Add Kid"**
4. Enter the child's name
5. Create a 4-digit PIN for them
6. Click **"Save"**

### Kid Login
1. On the main screen, the child selects their name
2. They enter their 4-digit PIN
3. They choose a buddy (Homework, Art, or Research)
4. They can start chatting!

---

## 🗑️ Uninstalling OPTIMAEUS

### macOS
1. Open **Finder** → **Applications**
2. Find **OPTIMAEUS**
3. Drag it to the **Trash**
4. Empty Trash

To remove all data:
```bash
rm -rf ~/Library/Application\ Support/com.optimaeus.desktop
```

### Windows
1. Open **Settings** → **Apps** → **Installed Apps**
2. Find **OPTIMAEUS**
3. Click the **three dots** (⋮) → **Uninstall**
4. Confirm uninstall

Or use Control Panel → Programs → Uninstall a Program

### Linux

**Debian/Ubuntu:**
```bash
sudo apt remove optimaeus
```

**Fedora/RHEL:**
```bash
sudo dnf remove optimaeus
```

**AppImage:** Just delete the AppImage file (no uninstall needed)

To remove all data:
```bash
rm -rf ~/.local/share/com.optimaeus.desktop
```

---

## ❓ Troubleshooting

### "App won't open" (macOS)
- Make sure you **right-clicked** and selected "Open" (see Step 3 above)
- Try: System Preferences → Security & Privacy → Click "Open Anyway"

### "Unknown publisher" warning (Windows)
- This is normal for apps not from the Microsoft Store
- Click "More info" → "Run anyway"

### "App is slow" (Windows/Linux)
- This is expected - the current version uses CPU for AI processing
- Response times of 10-30 seconds are normal
- macOS is faster because it uses GPU acceleration

### "Model file not found"
- Make sure you downloaded a `.gguf` model file
- Check the file path has no special characters
- Try placing the model in a simple path like `Documents/models/`

### "Out of memory" error
- Close other applications
- Try a smaller model (Q4 instead of Q6)
- You need at least 8GB RAM

---

## 🆘 Still Need Help?

Contact us:
- Email: octavie.ploye@timaeus-consulting.com

We're happy to help you get set up! 😊
