# 🎮 Ready or Not - S-Rank Checklist

An interactive checklist to track your progress toward S-ranking all 29 missions in **Ready or Not**.

**Languages:** [English](README.md) | [Deutsch](README-de.md)

## ✨ Features

- ✅ **29 Missions** - All missions including DLCs
- 📊 **Live Progress** - Statistics and progress bar
- 💾 **Auto-Save** - Data is saved locally in your browser
- 🎯 **Categorized** - Organized by campaign & DLC
- 💡 **Tips** - Hints for particularly challenging missions (hidden as spoilers)
- 🌐 **Bilingual** - Switch between English and German
- 🌙 **Dark Mode** - Comfortable dark theme
- 📱 **Responsive** - Works on desktop, tablet & mobile
- ⚡ **Offline** - Works without internet connection

## 🚀 Usage

### Online (GitHub Pages)
Open the website directly in your browser - no installation needed!

**URL:** `https://username.github.io/ready-or-not-s-rang-checklist`

### Locally
```bash
# Clone the repository
git clone https://github.com/username/ready-or-not-s-rang-checklist.git
cd ready-or-not-s-rang-checklist

# Open with Live Server (VS Code Extension) or simply open index.html in your browser
```

## 📋 Missions

### Main Campaign (18)
Thank You, Come Again • 23 Megabytes A Second • Twisted Nerve • The Spider • A Lethal Obsession • Ides of March • Sinuous Trail • Ends of the Earth • Greased Palms • Valley of the Dolls • Elephant • Rust Belt • Sins of the Father • Neon Tomb • Buy Cheap, Buy Twice • Carriers of the Vine • Relapse • Hide and Seek

### Home Invasion DLC (3)
Dorms • Narcos • Lawmaker

### Los Sueños Stories (2)
Stolen Valor • Hunger Strike

### Dark Waters DLC (3)
Mirage at Sea • Leviathan • 3 Letter Triad

### Boiling Point DLC (3)
No Good Deed • All Gods Burn • A New America

## 💾 Data Storage

The checklist automatically saves your progress in **browser storage (localStorage)**:
- Device-specific (not synced between devices)
- Personal (only you can see your data)
- Persistent (until you clear your browser cache)

**Export your data:** Copy from the browser console:
```javascript
localStorage.getItem('ron-s-rang-data')
```

## 🔧 Development

Make changes directly in `index.html`. The file is self-contained and requires no build tools.

### Adding Missions
In the `<script>` section where `missions` is defined:
```javascript
{ 
  id: 30, 
  name: 'Mission Name', 
  map: 'Map Name', 
  category: 'Category', 
  difficulty: 'easy|medium|hard', 
  tip: 'Optional tip or null'
}
```

### Adding Translations
Edit the `translations` object in the `<script>` section to add new languages or update existing translations.

## 🤝 Collaboration

You can grant other GitHub users access to this repository:

### Adding Collaborators (Private Repo)
1. Go to your repository on GitHub
2. **Settings** → **Collaborators and teams** (or **Collaborators**)
3. Click **Add people**
4. Enter the GitHub username, email, or full name
5. Choose the permission level (Push access recommended)
6. They will receive an invitation by email

### Permission Levels
- **Pull**: Read only
- **Push**: Read + Edit (recommended for collaborators)
- **Admin**: Full access, including settings

## 📝 License

Free to use - feel free to modify and share!

## 🌐 Languages

- 🇬🇧 **English** - [README.md](README.md) (main)
- 🇩🇪 **Deutsch** - [README-de.md](README-de.md)

Switch languages in the app using the 🌐 button in the top right corner.

## 🐛 Troubleshooting

- **Progress disappeared?** → Your browser cache was cleared (localStorage)
- **Styling looks broken?** → Clear your browser cache (Ctrl+Shift+Del)
- **Nothing works?** → Make sure JavaScript is enabled

---

**Made with ❤️ for Ready or Not S-Rank enthusiasts**
