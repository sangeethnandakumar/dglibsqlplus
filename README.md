# Turso in DataGrip
<img width="413" height="121" alt="image" src="https://github.com/user-attachments/assets/934fc2a9-8c55-46c4-9455-be665300960b" />
<img width="293" height="121" alt="image" src="https://github.com/user-attachments/assets/808edfe2-8ad9-4660-8ed7-2110bd98f370" />

# dglibsqlplus

> A JetBrains DataGrip driver for connecting to remote Turso databases.

`dglibsqlplus` is a fork of `datagrip-libsql` to improve it and **provide the best possible Turso experience in JetBrains DataGrip**.

This project is maintained by **Sangeeth Nandakumar** and focuses exclusively on improving the DataGrip integration through bug fixes, compatibility improvements.

- It **does not aim to be a general-purpose libSQL driver**.
- Its only goal is to make connecting to **remote Turso databases** from **JetBrains DataGrip** feel like a native, first-class experience.
- If a feature does not improve the DataGrip + Turso workflow, it is likely out of scope.

| ✅ In Scope | ❌ Out of Scope |
|-------------|-----------------|
| First-class JetBrains DataGrip support | General-purpose libSQL development |
| Only Turso remote database connections | Anything other than Turso or libSQL specific |
| Remote Turso connections & Bug fixes | Local SQLite databases |
| Compatibility with newer DataGrip releases | Other JetBrains IDEs |
| Stability and user experience improvements | Features unrelated to the DataGrip + Turso workflow |

---

# How To Use This PlugIn

## Installation

### 1. Download the plugin as ZIP file

Download the latest plugin ZIP from the project's Releases page:

https://github.com/sangeethnandakumar/dglibsqlplus/releases

> **Do not extract the ZIP file.** DataGrip installs the plugin directly from the downloaded ZIP.

---

### 2. Install the plugin

In **JetBrains DataGrip**, navigate to:

**File → Settings → Plugins → ⚙️ (Gear Icon) → Install Plugin from Disk...**

Select the downloaded ZIP file and complete the installation.

---

### 3. Restart DataGrip

Restart DataGrip to activate the plugin.

---

### 4. Create a Turso connection

Navigate to:

**File → New → Data Source → Turso Remote**

---

### 5. Configure the connection

Enter your Turso connection details in the **Host** field using the following format:

```text
<HOST>?authToken=<TOKEN>
```

Example:

```text
your-database.aws-ap-south-1.turso.io?authToken=eyJhbGciOi...
```

> **Do not enter a username or password.**
>
> Authentication is handled entirely through the `authToken` provided in the Host field.

---

### 6. Connect

Click **Test Connection** (optional), then **OK** to start querying your remote Turso database from DataGrip.

---

# Credits

This project is based on the excellent work done in the original `datagrip-libsql` project and only focus on adding more features on top of it.

---

# License

This project is licensed under the MIT License.

See the `LICENSE` file for details.
