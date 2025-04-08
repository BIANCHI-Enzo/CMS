# 🌐 EnzoCMS

**EnzoCMS** is a modern, modular, scalable, and fully responsive CMS built from scratch by Enzo **BIANCHI**.  
The goal is to offer a solution that is **ultra user-friendly** for beginners, yet **highly customizable** for advanced users.

---

## 🧱 Key Objectives

- ✅ Fully responsive for all screen sizes (up to 8K)
- ✅ Theme and module management
- ✅ Modern administration interface
- ✅ Automatic installation process
- ✅ Built-in update system
- ✅ Clean and clear MVC architecture
- ✅ Secure, fast, and open to the community

---

## 📂 Project Structure

```
cms/
├── public/                 # Front Controller (index.php) and accessible assets
│   ├── index.php
│   └── .htaccess
│
├── app/                    # Application source code (MVC)
│   ├── Core/               # Core engine (App, Router, BaseController, etc.)
│   ├── Controllers/        # Main controllers (Home, Admin, Install, etc.)
│   ├── Models/             # Data models
│   ├── Views/              # HTML/PHP templates (views)
│   └── Helpers/            # Global utility functions
│
├── config/                 # Configuration files (database, etc.)
│   └── database.php
│
├── storage/                # Generated files (logs, cache, uploads, etc.)
│   ├── logs/
│   ├── cache/
│   └── uploads/
│
├── modules/                # Custom modules or plugins
│   └── ...
│
├── installation/           # Automated installation
│   └── ...
│
├── themes/                 # Configurable frontend themes
│   └── default/
│       ├── css/
│       ├── js/
│       └── views/
│
├── admin/                  # Administration interface (specific controllers/views)
│   ├── Controllers/
│   ├── Views/
│   └── Assets/
│
├── database/               # Migrations, seeds, and backups
│   ├── migrations/
│   ├── seeds/
│   └── backups/
│
├── languages/              # Multilingual support files
│   ├── fr/
│   ├── en/
│   └── es/
│
├── cli/                    # CLI tools for management (install, update, etc.)
│
├── vendor/                 # (future composer integration?)
│
├── LICENSE                 # License Apache-2.0
│
└── README.md               # This file 😉
```

---

## 📌 Author

Proudly developed with passion by **Enzo BIANCHI** 🚀

---

## 🗂 Current Version

**Beta 0.0.1**

The CMS uses a file-based versioning system via the `VERSION` file located at the root of the project.

This allows:
- Tracking of the current version in use
- Comparison with remote versions
- Future integration of an automatic update system
