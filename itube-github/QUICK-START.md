# ⚡ QUICK START - Pujar ITuBè a GitHub

**Guia ràpida per pujar ITuBè a GitHub en 10 minuts**

## ✅ Prerequisites

- [ ] Git instal·lat
- [ ] Compte de GitHub
- [ ] Arxius d'ITuBè descarregats

## 📦 PASSOS RÀPIDS

### 1. Crea el repositori a GitHub (2 min)

1. Ves a [github.com](https://github.com)
2. Clica **"+" → "New repository"**
3. Omple:
   - Name: `itube`
   - Description: "ITuBè v3.0 - Aplicació de seguiment emocional 100% offline"
   - Public ✅
4. Clica **"Create repository"**

### 2. Prepara els arxius (3 min)

```bash
# Crea carpeta
mkdir ~/itube-project
cd ~/itube-project

# Mou tots els arxius descarregats aquí
# (Arrossega els arxius del navegador a aquesta carpeta)

# Verifica que tens tots els arxius
ls -la

# Hauries de veure:
# - index.html
# - README.md
# - LICENSE
# - .gitignore
# - CHANGELOG.md
# - 00-LLEGEIX-PRIMER.md
# - QUICK-START.md
# - CONTRIBUTING.md
```

### 3. Puja a GitHub (3 min)

```bash
# Inicialitza Git
git init

# Configura (només primer cop)
git config --global user.name "Enric"
git config --global user.email "el-teu-email@exemple.com"

# Afegeix arxius
git add .

# Primer commit
git commit -m "🎉 Primera versió - ITuBè v3.0 completa"

# Connecta amb GitHub
git remote add origin https://github.com/sofrutoficina/itube.git

# Puja
git branch -M main
git push -u origin main
```

### 4. Activa GitHub Pages (2 min)

1. Ves al repositori
2. **Settings** → **Pages**
3. Source:
   - Branch: `main`
   - Folder: `/ (root)`
4. **Save**
5. Espera 1-2 minuts
6. Visita: `https://sofrutoficina.github.io/itube`

## 🎉 FET!

Ara tens:
- ✅ Repositori públic
- ✅ Aplicació accessible online
- ✅ Historial de versions
- ✅ Pàgina web funcionant

## 🚀 SEGÜENTS PASSOS

### Instal·lar Claude Code (opcional)

```bash
# Instal·la Node.js des de: https://nodejs.org/

# Instal·la Claude Code
npm install -g @anthropic-ai/claude-code

# Configura
claude configure
```

### Fer canvis al projecte

```bash
# 1. Fes canvis a index.html o altres arxius

# 2. Guarda'ls a GitHub
git add .
git commit -m "✨ descripció del canvi"
git push

# 3. Els canvis es publicaran automàticament a GitHub Pages
```

## 💡 CONSELLS

- **Fes commits freqüents** - Cada canvi petit mereix un commit
- **Usa missatges descriptius** - "✨ feat: Afegir botó export" és millor que "update"
- **Prova localment primer** - Obre index.html abans de pujar
- **GitHub Pages tarda 1-2 min** - Sigues pacient després de fer push

## 🆘 PROBLEMES COMUNS

### Git no reconeix les credencials
```bash
# Usa Personal Access Token en lloc de password
# Crea'l a: GitHub → Settings → Developer settings → Personal access tokens
```

### No es veu la pàgina a GitHub Pages
- Espera 2-3 minuts
- Verifica que Settings → Pages estigui activat
- Comprova que l'arxiu es diu `index.html` (no `Index.html`)

### Els arxius no es pugen
```bash
# Verifica que estàs a la carpeta correcta
pwd

# Verifica que els arxius existeixen
ls -la
```

---

**Creat:** Novembre 2024  
**Per:** ITuBè v3.0
