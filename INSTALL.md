# تثبيت إضافة Vora لـ VS Code
# Vora VS Code Extension Installation Guide

<div dir="rtl">

## 📥 طرق التثبيت

### الطريقة الأولى: من سوق VS Code (موصى بها)

1. افتح VS Code
2. اضغط `Ctrl+Shift+X` لفتح Extensions
3. ابحث عن "Vora"
4. اضغط **Install**

### الطريقة الثانية: التثبيت اليدوي (VSIX)

#### Windows (PowerShell):
```powershell
code --install-extension vora-1.0.0.vsix --force
```

#### Windows (Command Prompt):
```cmd
code --install-extension vora-1.0.0.vsix --force
```

#### Linux/macOS:
```bash
code --install-extension vora-1.0.0.vsix --force
```

### الطريقة الثالثة: من داخل VS Code

1. اضغط `Ctrl+Shift+P` (أو `Cmd+Shift+P` على macOS)
2. اكتب: `Extensions: Install from VSIX...`
3. اختر ملف `vora-1.0.0.vsix`
4. أغلق VS Code بالكامل (`Alt+F4`)
5. أعد فتح VS Code

---

## ✅ التحقق من التثبيت

بعد التثبيت:

1. افتح VS Code
2. اضغط `Ctrl+Shift+E` لفتح File Explorer
3. افتح أي ملف `.vora`
4. يجب أن تظهر:
   - 🎨 الأيقونة الزرقاء بجانب الملف
   - 📊 "Vora" في شريط الحالة (Status Bar)
   - 🌈 Syntax Highlighting ملون

---

## 🎨 تفعيل الثيم (Theme)

1. اضغط `Ctrl+K` ثم `Ctrl+T`
2. اختر **"Vora Dark"**

أو عبر الإعدادات:
```json
{
  "workbench.colorTheme": "Vora Dark"
}
```

---

## ⚙️ الإعدادات الموصى بها

أضف هذا إلى `settings.json`:

```json
{
  // Vora Compiler
  "vora.compiler.path": "vorac",
  
  // Formatting
  "vora.format.indentSize": 4,
  "[vora]": {
    "editor.defaultFormatter": "cup-code-studio.vora",
    "editor.formatOnSave": true,
    "editor.tabSize": 4
  },
  
  // Linting
  "vora.linting.enabled": true,
  
  // Files
  "files.associations": {
    "*.vora": "vora"
  }
}
```

---

## 🔧 حل المشاكل

### الأيقونة لا تظهر

**الحل:**
1. أغلق VS Code بالكامل (`Alt+F4`)
2. انتظر 5 ثوان
3. أعد فتح VS Code
4. ⚠️ **ملاحظة**: `Reload Window` لن يعمل!

### Syntax Highlighting لا يعمل

**الحل:**
1. افتح ملف `.vora`
2. اضغط `Ctrl+K` ثم `M`
3. اختر "Vora" من القائمة

### الإضافة لا تظهر في Extensions

**تحقق من التثبيت:**
```powershell
code --list-extensions | Select-String "vora"
```

**إعادة التثبيت:**
```powershell
# إلغاء التثبيت
code --uninstall-extension cup-code-studio.vora

# إعادة التثبيت
code --install-extension vora-1.0.0.vsix --force
```

---

## 🚀 الاختصارات (Shortcuts)

| الاختصار | الوظيفة |
|---------|---------|
| `Ctrl+Shift+B` | Compile Current File |
| `F5` | Run Current File |
| `Shift+Alt+F` | Format Document |
| `Ctrl+Space` | IntelliSense |
| `Ctrl+Shift+P` | Command Palette |

---

## 📚 الموارد

- **Discord**: [discord.gg/KuJCrVGZv8](https://discord.gg/KuJCrVGZv8)
- **GitHub**: [Cup-Code-Studio/Vora-Language-Majd-Engine](https://github.com/Cup-Code-Studio/Vora-Language-Majd-Engine)
- **Documentation**: [Majd Engine Docs](../../Docs/)

---

## 💡 نصائح

1. **استخدم الـ Snippets**: اكتب `func` ثم `Tab` لإنشاء دالة سريعة
2. **IntelliSense**: اضغط `Ctrl+Space` للحصول على اقتراحات
3. **الثيم**: جرب "Vora Dark" theme للحصول على أفضل تجربة
4. **Status Bar**: اضغط على "Vora" في الشريط السفلي للوصول السريع

---

<p align="center">
  Made with ❤️ by Cup Code Studio 🇸🇦
</p>

</div>
