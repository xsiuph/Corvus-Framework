
# synth
A **simple** and **lightweight** Lua framework designed for **efficiency** and **speed**.
---
## 🚀 Features
- ⚡ **Fast & Efficient:** Optimized for performance with minimal overhead.
- 🛠️ **Easy to Use:** Simple APIs to get you started quickly.
- 📦 **Lightweight:** No unnecessary bloat—just what you need.
---
## 📦 Installation
To get started, simply run:
```lua
print("HELLO WORLD!")
```
*(Replace with actual installation instructions)*
---
## 📚 Usage
Here’s how you can use **synth**:
```lua
local synth = require(path.to.synthModule[Preferably ReplicatedStorage])
local loader = synth:new()
loader:load(path.to.folder.with.modules, "DIRECTORYNAME") -- All modules within path.to.folder.with.modules will be stored in "synth.cache.DIRECTORYNAME"
--If you want to import loaded modules
synth("DIRECTORYNAME/MODULENAME")
-- IF you need to import ALL modules inside of a directory just do:
synth("DIRECTORYNAME")
```
EXAMPLE:
```lua
local synth = require(game.ReplicatedStorage.Modules.synth)
local loader = synth:new()
loader:load(game.ServerScriptService.Modules.Services, "Services") -- loads all modules inside of Modules.Services into "synth.cache.Services"
```
---
## 🤝 Contributing
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.
---
## 📄 License
This project is licensed under the [MIT License](LICENSE.md).
---
## 💬 Support
For questions, issues, or suggestions, feel free to open an [Issue](https://github.com/xsiuph/synth-Framework/issues) or join our community!
Happy coding! 🚀
