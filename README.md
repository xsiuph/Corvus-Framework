# Corvus

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

Here’s how you can use **Corvus**:

```lua
local Corvus = require(path.to.CorvusModule[Preferably ReplicatedStorage])

local loader = Corvus:new()

loader:load(path.to.folder.with.modules, "DIRECTORYNAME") -- All modules within path.to.folder.with.modules will be stored in "Corvus.cache.DIRECTORYNAME"

--If you want to import loaded modules
Corvus("DIRECTORYNAME/MODULENAME")
-- IF you need to import ALL modules inside of a directory just do:
Corvus("DIRECTORYNAME")

```

EXAMPLE:

```lua
local Corvus = require(game.ReplicatedStorage.Modules.Corvus)

local loader = Corvus:new()

loader:load(game.ServerScriptService.Modules.Services, "Services") -- loads all modules inside of Modules.Services into "Corvus.cache.Services"
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

For questions, issues, or suggestions, feel free to open an [Issue](https://github.com/Corvus-Framework/issues) or join our community!

Happy coding! 🚀

