<p align="center"><img src="https://raw.githubusercontent.com/DrakesCraft-Labs/SlimefunOreChunks/main/banner.svg" alt="SlimefunOreChunks banner" width="100%"></p>

# SlimefunOreChunks

> ### 🏰 ¡Únete a la Comunidad Oficial de DrakesCraft!
> 
> * 🎮 **IP del Servidor**: `play.drakescraft.net` *(Java 1.21.11 & Bedrock)*
> * 💬 **Discord Oficial**: [discord.gg/drakescraft](https://discord.gg/rv3vtXZTk7)
> * 🌐 **Web & Guía**: [drakescraft.net](https://drakescraft.net) — 🛒 **Tienda**: [tienda.drakescraft.net](https://tienda.drakescraft.net)
> 
> *¡Juega con este addon y más de 80 expansiones optimizadas en vivo en nuestra network de supervivencia técnica!*

---

Mining progression built around recoverable ore fragments. Ore chunks add an intermediate
processing step that rewards infrastructure without replacing vanilla exploration.

## DrakesCraft edition

- Targets Java 21 and Paper/Purpur 1.21.11.
- Provides 11 registered Slimefun items through the Drakes compatibility API.
- Keeps item IDs and the original package layout stable for existing worlds.
- Uses maintained Maven dependencies and deterministic builds.

## Building

```bash
mvn -B -ntp clean package
```

Install the JAR from `target/` together with
[`Slimefun4-Drake`](https://github.com/DrakesCraft-Labs/Slimefun4-Drake).

## Provenance

Integrated from [SlimefunGuguProject/SlimefunOreChunks](https://github.com/SlimefunGuguProject/SlimefunOreChunks).
The original authorship and MIT license remain intact.

---

## 📄 License & Upstream Attribution

This project is a sovereign fork maintained by [**JackStar6677-1**](https://github.com/JackStar6677-1) under [**DrakesCraft Labs**](https://github.com/DrakesCraft-Labs).

- **Original Project:** Created by the upstream authors and the open-source community.
- **DrakesCraft Optimizations:** Modernized for Paper/Purpur 1.21.11+, Java 21, high concurrency, asynchronous safety, and exploit/duplication prevention.
- **License:** Distributed under the original **GNU General Public License v3.0 (GPLv3)** (or original upstream license). See the [LICENSE](LICENSE) file for complete terms.
