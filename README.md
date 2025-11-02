# Vora Language Extension for VS Code

<p align="center">
  <img src="../images/icon.png" alt="Vora Logo" width="128" height="128">
</p>

<p align="center">
  <strong>Official VS Code Extension for Vora Programming Language</strong><br>
  The native scripting language of Majd Engine 🇸🇦
</p>

<p align="center">
  <a href="https://discord.gg/KuJCrVGZv8"><img src="https://img.shields.io/discord/YOUR_DISCORD_ID?color=7289da&label=Discord&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine"><img src="https://img.shields.io/github/stars/Cup-Code-Studio/Vora-Language-Majd-Engine?style=social" alt="GitHub Stars"></a>
  <a href="https://marketplace.visualstudio.com/items?itemName=cup-code-studio.vora"><img src="https://img.shields.io/visual-studio-marketplace/v/cup-code-studio.vora" alt="VS Code Marketplace"></a>
</p>

---

## 📥 Installation

### Method 1: From VS Code Marketplace (Recommended)
1. Open VS Code
2. Press `Ctrl+Shift+X` to open Extensions
3. Search for "Vora"
4. Click **Install**

### Method 2: Manual Installation (VSIX)
1. Download `vora-1.0.0.vsix` from [Releases](https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine/releases)
2. Open VS Code
3. Press `Ctrl+Shift+P`
4. Type "Install from VSIX"
5. Select the downloaded file

### Method 3: Command Line
```bash
code --install-extension vora-1.0.0.vsix
```

---

## ✨ Features

### 🎨 Syntax Highlighting
- Keywords: `func`, `class`, `if`, `for`, `while`, `return`, etc.
- Types: `int`, `float`, `string`, `bool`, `vec2`, `vec3`, etc.
- ECS decorators: `@Component`, `@System`, `@Entity`
- Comments and strings with proper highlighting

### 📝 IntelliSense & Auto-completion
- Smart code completion
- Function signatures
- Parameter hints
- Context-aware suggestions

### 🔧 Code Snippets
- `func` - Create a function
- `class` - Create a class
- `if` - If statement
- `for` - For loop
- `component` - ECS Component
- `system` - ECS System
- And many more...

### 🎯 Commands
- **Vora: Compile Current File** (`Ctrl+Shift+B`)
- **Vora: Run Current File** (`F5`)
- **Vora: Format Document** (`Shift+Alt+F`)

### 🌙 Vora Dark Theme
Custom dark theme optimized for Vora syntax with:
- Blue keywords
- Orange strings
- Green comments
- Cyan classes and types

### 📊 Status Bar Integration
- Shows Vora icon when editing `.vora` files
- Quick access to documentation, Discord, and GitHub

---

## 🚀 Quick Start

### 1. Create a new file: `hello.vora`

```vora
// Hello World in Vora
func main() {
    print("Hello, Majd Engine!");
}
```

### 2. Compile & Run
- Press `Ctrl+Shift+B` to compile
- Press `F5` to run

### 3. Use ECS Components

```vora
@Component
class Transform {
    position: vec3;
    rotation: vec3;
    scale: vec3;
}

@System
func MovementSystem(entity: Entity) {
    let transform = entity.get<Transform>();
    transform.position += vec3(1.0, 0.0, 0.0);
}
```

---

## 📚 Documentation

- **Official Docs**: [majdengine.com/docs](https://majdengine.com/docs)
- **Tutorials**: [Getting Started Guide](../../Docs/Tutorials/04_VoraLanguage.md)
- **Discord**: [Join our community](https://discord.gg/KuJCrVGZv8)
- **GitHub**: [Source Code](https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine)

---

## ⚙️ Configuration

Configure the extension in VS Code settings:

```json
{
  "vora.compiler.path": "vorac",
  "vora.format.indentSize": 4,
  "vora.linting.enabled": true
}
```

---

## 🎮 Majd Engine Integration

This extension is part of the **Majd Engine** ecosystem:

- **Engine**: C++ game engine with ECS architecture
- **Vora**: Native scripting language
- **Visual Editor**: Drag-and-drop game editor
- **Blueprint System**: Visual scripting
- **Launcher**: Project manager and launcher

---

## 🐛 Known Issues

- Language Server Protocol (LSP) support is planned for v1.1
- Debugging integration coming in v1.2

See [CHANGELOG.md](../CHANGELOG.md) for full version history.

---

## 🤝 Contributing

Contributions are welcome! Please check our [GitHub repository](https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine).

---

## 📄 License

MIT License - Copyright (c) 2025 Cup Code Studio 🇸🇦

---

## 🌟 Support

- ⭐ Star us on [GitHub](https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine)
- 💬 Join our [Discord](https://discord.gg/KuJCrVGZv8)
- 🐛 Report issues on [GitHub Issues](https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine/issues)

---

<p align="center">
  Made with ❤️ by Cup Code Studio 🇸🇦
</p>
