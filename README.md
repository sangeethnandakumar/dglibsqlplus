# Turso in DataGrip

# dglibsqlplus

> Is a DataGrip driver for **Turso Remote** with improved stability, compatibility, and bug fixes focusing specific only to DataGrip and Remote DB connections.

`dglibsqlplus` is a maintained by `Sangeeth Nandakumar` which is a fork of the original `datagrip-libsql` project.
The primary goal is to provide **first-class support for Turso/libSQL Remote databases in JetBrains DataGrip**, while fixing bugs and improving compatibility with recent DataGrip versions.

## Why this fork?
This fork focuses only on:

* ✅ Major bug fixes
* ✅ Firstclass DataGrip support only (No support for any other IDEs)
* ✅ Turso remote connections only (No support for SQLite files)
* ✅ MIT Licensed

The goal is simple: **make connecting to Turso from DataGrip feel like a native experience.**

---

# Installation

The plugin is **not currently published on the JetBrains Marketplace**.

## Install manually

1. Download the latest ZIP file from the project's **GitHub Releases**.
2. Open **DataGrip**.
3. Go to:

```
Settings / Preferences
→ Plugins
→ ⚙️ (Gear Icon)
→ Install Plugin from Disk...
```

4. Select the downloaded ZIP file.
5. Restart DataGrip.

After restarting, you can configure a **"Turso Remote"** connection.

---

# Credits

This project is based on the excellent work done in the original `datagrip-libsql` project and only focus on adding more features on top of it.

---

# License

This project is licensed under the MIT License.

See the `LICENSE` file for details.
