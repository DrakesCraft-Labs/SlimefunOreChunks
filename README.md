<p align="center"><img src="docs/banner.svg" alt="SlimefunOreChunks banner" width="100%"></p>

# SlimefunOreChunks

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
