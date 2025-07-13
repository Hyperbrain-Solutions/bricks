# 🧱 Bricks

A collection of custom [Mason](https://docs.brickhub.dev/) bricks built and maintained by [Adamu Muktar](https://github.com/mkhtradm01).

These bricks are designed to streamline Flutter development with reusable templates that follow best practices. Perfect for MVPs, full-scale apps, and client projects.

---

## 🚀 Features

- ✨ Modular and scalable architecture
- ⚙️ CI/CD setup bricks (GitHub Actions, Fastlane)
- 🧱 Bricks for features, packages, and entire apps
- 🎯 Support for multiple state management options

---

## 📁 Repository Structure
```bricks/
├── feature_module/
│   ├── brick.yaml
│   └── brick/
├── flutter_app_clean_arch/
│   ├── brick.yaml
│   └── brick/
└── …
```
Each subdirectory in `bricks/` represents a fully functional custom Mason brick.

---

## 📦 Getting Started

### 1. Install Mason (if not already installed):
```bash
dart pub global activate mason_cli 
```

### 2. Add a brick from this repo:
```bash
mason add <brick_name> --path ./bricks/<brick_name>
```

### 3. Generate code from the brick:
```bash
mason make <brick_name>
```

### 4. 🤝 Contributing

Contributions are welcome! If you have improvements, ideas, or new bricks to suggest:
	1.	Fork the repository
	2.	Create a feature branch (git checkout -b feature/your-brick)
	3.	Commit your changes
	4.	Push to your branch
	5.	Open a Pull Request

Please follow the existing structure and naming conventions when adding new bricks.

### 5. 🙌 Acknowledgements
	•	[Mason CLI](https://docs.brickhub.dev/)

### 6. 📫 Contact

For issues, ideas, or collaboration:

📧 mkhtradm01@gmail.com