# Demo Version Setup Guide

## ✅ What's Included

This demo folder contains:
- `bundle.js` - Compiled application (minified, unreadable)
- `index.html` - Entry point
- `README.md` - Demo documentation
- `.gitignore` - Excludes source code
- `package.json` - Demo metadata

## 🔒 Security Features

### What's NOT Included (Protected):
- ❌ Source code (`.tsx`, `.ts` files)
- ❌ Component files
- ❌ Service files
- ❌ Full authentication system
- ❌ 5000 user credentials

### What IS Included:
- ✅ Compiled bundle (obfuscated)
- ✅ Demo user only (`demo` / `demo123`)
- ✅ Limited functionality
- ✅ Watermarks on exports

## 📤 GitHub Upload Steps

1. **Initialize Git in Demo folder:**
   ```bash
   cd Demo
   git init
   ```

2. **Add files:**
   ```bash
   git add .
   ```

3. **Commit:**
   ```bash
   git commit -m "Initial demo release v1.0.0"
   ```

4. **Add remote:**
   ```bash
   git remote add origin https://github.com/laedrianus/aura-content-planner.git
   ```

5. **Push:**
   ```bash
   git push -u origin main
   ```

6. **Enable GitHub Pages:**
   - Go to repository Settings
   - Pages → Source → main branch
   - Save

## 🎨 Add Screenshots

Before uploading, add screenshots to `screenshots/` folder:
- `dashboard.png` - Main dashboard view
- `calendar.png` - Calendar interface
- `analytics.png` - Analytics screen

## ⚠️ Important Notes

- The `bundle.js` is minified and difficult to reverse-engineer
- No sensitive data or full auth system is exposed
- Demo limitations are hardcoded in the bundle
- Users can see the app but can't steal the full codebase

## 🔗 After Upload

Update these links in README.md:
- Gumroad purchase link
- Support email
- GitHub Pages URL

## ✨ Demo Limitations (Built-in)

- Maximum 10 posts
- Maximum 5 tasks
- 3 AI generations per day
- "DEMO VERSION" watermark
- No data persistence
- Purchase prompt on every action

---

**Ready to upload to GitHub!** 🚀
