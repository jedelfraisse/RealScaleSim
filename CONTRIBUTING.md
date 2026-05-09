# Contributing to RealScaleSim

Thank you for your interest in contributing to RealScaleSim!  
This project aims to build a modular, first‑person real‑scale simulation framework capable of powering theme parks, malls, stores, zoos, warehouses, and other real‑world environments.

We welcome contributions of all kinds — code, design, documentation, testing, and ideas.

---

## 🧱 Project Philosophy

RealScaleSim is built on five core principles:

1. **True Scale** — Environments match real‑world dimensions for immersion and accuracy.  
2. **Modularity** — Each domain (parks, retail, warehouses, etc.) is a plug‑in module.  
3. **First‑Person Immersion** — Ground‑level interaction is central to the experience.  
4. **Simulation‑Driven** — AI agents and world logic operate independently of rendering.  
5. **Extensibility** — The framework should grow with community contributions.

---

## 🛠 How to Contribute

### 1. Fork the Repository
Create your own fork of the project and clone it locally.

### 2. Create a Feature Branch
Use a clear, descriptive branch name:
feature/building-system
feature/ai-navigation
fix/placement-bug
docs/module-architecture

### 3. Follow Coding Standards
- Unreal Engine C++ conventions  
- Blueprint organization best practices  
- Keep modules self‑contained  
- Avoid committing binaries or generated files  
- Use the `.gitignore` provided  

### 4. Write Clear Commit Messages
Good examples:
Add basic first-person building placement system
Implement modular AI agent interface
Refactor grid snapping for performance

### 5. Submit a Pull Request
Include:
- A clear description of the change  
- Screenshots or videos (if applicable)  
- Any known limitations  
- Steps to test the feature  

PRs will be reviewed for:
- Code quality  
- Modularity  
- Performance impact  
- Alignment with project goals  

---

## 🧪 Testing

Before submitting a PR:
- Ensure the project compiles in Unreal  
- Test in both PIE and standalone  
- Validate performance in real‑scale environments  
- Confirm no new warnings or errors appear  

---

## 📁 Project Structure

The project will follow this structure:
/Source
/RealScaleSimCore
/Modules
/ThemePark
/Retail
/Warehouse
/Content
/Core
/Modules
/Docs


---

## 🗣 Communication

Use GitHub Issues for:
- Feature requests  
- Bug reports  
- Module proposals  
- Architecture discussions  

---

## 📜 License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

Thank you for helping build RealScaleSim — a new foundation for real‑scale simulation.

