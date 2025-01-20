# React/Next.js Package Finder & Installer

This tool helps you identify and install all necessary npm packages for your React.js or Next.js projects. It consists of two components:

## 1. `React-Next.js-Package-Finder-Installer.exe`
This script scans your project folder for package imports and generates a list of required packages in a `packages.txt` file.

### How to Use:
1. Run `React-Next.js-Package-Finder-Installer.exe`.
2. Select the root folder of your project when prompted.
3. The script will scan all `.js`, `.jsx`, `.ts`, and `.tsx` files for package imports.
4. A `packages.txt` file will be created in the selected folder, listing all identified packages.
5. Run `install_packages.bat` to install all the packages listed in `packages.txt` using `npm install`.

---

## Reminder
If the directory you select contains multiple nested folders with React or Next.js projects, you must repeat this process for each folder individually.

---

This tool simplifies dependency management, saving you time and effort when setting up your projects.
