# Betterexp

**Betterexp** is a lightweight client-side modpack for *Lethal Company*, designed to be used **as a dependency or addon for other modpacks**.  
The main focus is **quality-of-life improvements, stability, and minimal performance impact**, without heavy visual or runtime mods.

Starting from version **2.0.0**, the modpack went through a targeted performance cleanup, removing mods that were known to cause FPS drops, micro-stutters, or runtime overhead.

---

## 🔧 Core Principles

- ✅ Client-side QoL mods without changing game balance  
- ✅ Compatible with large and custom modpacks  
- ✅ Minimal CPU / GC overhead  
- ❌ No heavy enemy-skin or runtime material swap mods  
- ❌ No client-only behavior that can break multiplayer consistency  

---

## 📦 What's Included

This modpack focuses on:
- UI and HUD improvements  
- Input, chat, and communication enhancements  
- Small gameplay quality-of-life tweaks  
- Stability and bug-fix mods  

All included mods are chosen with **performance and compatibility** in mind.

---

## ⚡ Performance First

Betterexp intentionally avoids mods that:
- Run heavy logic in `Update()`  
- Perform frequent `FindObjectsOfType` or reflection scans  
- Replace enemy meshes, materials, or skins at runtime  

This ensures smoother gameplay, especially in large lobbies or heavily modded sessions.

---

## 🔄 Versioning Policy

- **Major versions** indicate significant changes to mod selection or performance philosophy  
- **Minor versions** include additions, removals, or safe updates  
- **Patch versions** are reserved for small fixes and metadata changes  

---

## 👥 Multiplayer Notes

- Safe to use in multiplayer  
- Designed to avoid client-only desync or exploit behavior  
- Can be freely combined with host-required or server-side modpacks  

---

## 📌 Recommended Usage

- As a base QoL layer for larger modpacks  
- For players who want stability and smooth performance  
- For creators who want a clean client-side dependency  

---

## 🛠️ Support & Source

- GitHub: https://github.com/BeInForIt  
- Issues and suggestions are welcome

---

**Betterexp** — clean, lightweight, and performance-focused.
