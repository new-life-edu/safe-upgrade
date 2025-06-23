# safe-upgrade

![Shell Script](https://img.shields.io/badge/script-bash-green.svg)

**Safely upgrade Debian/Ubuntu or Termux packages in small, manageable segments.**

This script lets you split `apt upgrade` operations into smaller install scripts, so you can review and control updates safely.

---

## ✅ Features

- Works on **Termux** and **Debian-based Linux** (Ubuntu, Parrot, etc.)
- Automatically uses `sudo` where needed
- Lets you define how many packages to install per batch
- Generates individual install scripts for each group

---

## 🚀 How to Use

1. Clone the repo or download the script:

```bash
   git clone https://github.com/new-life-edu/safe-upgrade.git
   cd safe-upgrade
   chmod +x safe-upgrade.sh
------------------------------
2. Run the script:
   ./safe-upgrade.sh
------------------------------
3. Enter how many packages you'd like per install group (e.g., 5, 10, 20).
------------------------------
4. The script will:

    Update your package list
    List upgradeable packages
    Split them into chunks
    Create scripts like install_package_segment_aa.sh
--------------------------------------
 5. To install:

   ./install_package_segment_aa.sh
------------------------------------------
            THE END


