# Vora VS Code Extension - Release v1.0.0

## 🎉 Initial Release

تاريخ الإصدار: November 2, 2025

---

## ✨ الميزات الجديدة

### 🎨 Syntax Highlighting
- تلوين كامل لجميع كلمات Vora المفتاحية
- دعم ECS decorators (@Component, @System, @Entity)
- تمييز الأنواع المدمجة (int, float, vec2, vec3, string, etc.)
- تلوين التعليقات والنصوص

### 📝 IntelliSense & Auto-completion
- إكمال تلقائي للكود
- اقتراحات ذكية حسب السياق
- عرض توقيعات الدوال
- مساعدة في المعاملات

### 🔧 Code Snippets
أكثر من 20 snippet جاهز:
- `func` - إنشاء دالة
- `class` - إنشاء صف
- `component` - ECS Component
- `system` - ECS System
- `if`, `for`, `while` - Control flow
- وأكثر...

### 🎯 الأوامر
- **Vora: Compile Current File** - ترجمة الملف الحالي
- **Vora: Run Current File** - تشغيل الملف الحالي
- **Vora: Format Document** - تنسيق الكود

### ⌨️ Keyboard Shortcuts
- `Ctrl+Shift+B` - Compile
- `F5` - Run
- `Shift+Alt+F` - Format

### 🌙 Vora Dark Theme
ثيم مخصص للغة Vora مع:
- ألوان محسّنة للكلمات المفتاحية
- تمييز واضح للأنواع والدوال
- راحة للعين في الوضع الداكن

### 📊 Status Bar Integration
- أيقونة Vora في شريط الحالة
- روابط سريعة للدوكمنتيشن والـ Discord

### 🎨 أيقونة مخصصة
- أيقونة زرقاء داكنة مع V سماوي
- تظهر في File Explorer بجانب ملفات .vora
- تظهر في Extensions view

---

## 📦 محتويات الإصدار

### الملفات المضمنة:
- `vora-1.0.0.vsix` - حزمة الإضافة (430 KB)
- `README.md` - دليل الاستخدام
- `INSTALL.md` - دليل التثبيت (عربي + English)
- `RELEASE_NOTES.md` - ملاحظات الإصدار

---

## 📥 التثبيت

### من VS Code:
```bash
code --install-extension vora-1.0.0.vsix --force
```

### من داخل VS Code:
1. `Ctrl+Shift+P`
2. اكتب: `Extensions: Install from VSIX...`
3. اختر `vora-1.0.0.vsix`

**⚠️ مهم**: أغلق VS Code بالكامل (`Alt+F4`) بعد التثبيت!

---

## ⚙️ الإعدادات

```json
{
  "vora.compiler.path": "vorac",
  "vora.format.indentSize": 4,
  "vora.linting.enabled": true,
  "[vora]": {
    "editor.defaultFormatter": "cup-code-studio.vora",
    "editor.formatOnSave": true
  }
}
```

---

## 🐛 المشاكل المعروفة

- LSP (Language Server Protocol) قيد التطوير
- دعم الـ Debugging سيأتي في v1.2

---

## 🔮 الخطط المستقبلية

### v1.1 (قريباً)
- [ ] Language Server Protocol (LSP)
- [ ] Go to Definition
- [ ] Find All References
- [ ] Rename Symbol
- [ ] Hover Information

### v1.2
- [ ] Debugging Support
- [ ] Breakpoints
- [ ] Variable Inspection
- [ ] Call Stack

### v2.0
- [ ] Visual Blueprint Integration
- [ ] Live Preview
- [ ] Asset Browser Integration

---

## 📚 الروابط المهمة

- **Discord**: https://discord.gg/KuJCrVGZv8
- **GitHub**: https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine
- **Documentation**: https://majdengine.com/docs
- **Issues**: https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine/issues

---

## 🤝 المساهمة

نرحب بالمساهمات! زر مستودع GitHub للمزيد من التفاصيل.

---

## 📄 الترخيص

MIT License - Copyright (c) 2025 Cup Code Studio 🇸🇦

---

## 🙏 شكر خاص

شكراً لجميع المساهمين والمختبرين الأوائل!

---

<p align="center">
  Made with ❤️ by Cup Code Studio 🇸🇦
</p>
