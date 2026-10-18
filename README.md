# primordial

A fork of **[Anubis](https://github.com/4ldenz/Anubis-client)** by **4ldenz**, a Fabric client mod for Minecraft 1.21.11.

This project is based on Anubis Beta 0.9.9.1. The source was recovered from the official
release jar and is licensed under the **GNU General Public License v3.0**, the same as the
original. See [LICENSE](LICENSE).

## Building

Pushes are built automatically by GitHub Actions; download the jar from the
workflow run's **Artifacts**. To build locally you need JDK 21 and Gradle:

```
gradle build
```

The jar is written to `build/libs/`.

## Credits

- Original client: Anubis by 4ldenz — GPL-3.0
- Third-party licenses: see `src/main/resources/META-INF/anubis-compat/licenses/`
