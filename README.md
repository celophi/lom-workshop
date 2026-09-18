# LoM Workshop

<p align="center">
  <img src=".github/assets/anvil.webp" alt="LoM Workshop" width="500">
</p>

<p align="center">
  <strong>An open-source modding framework, SDK, and build toolkit for Legend of Mana on PlayStation.</strong>
</p>

> [!IMPORTANT]
> **Status: Coming soon.**
>
> LoM Workshop is currently in the design and early development stage.

LoM Workshop builds on the reverse-engineering work of [lom-decomp](https://github.com/celophi/lom-decomp) to provide a practical environment for creating, combining, and building mods for the PlayStation version of **Legend of Mana**.

## Planned Features

- C-based game modifications
- Asset and game-data replacement
- Mod packaging and composition
- Automated PlayStation disc rebuilding
- Reproducible containerized PS1 build environment
- Command-line tooling
- Graphical modding and development tools

## How It Will Work

LoM Workshop will provide a modern frontend around the game's reconstructed source, build system, and asset formats.

Mods will be able to contain code, assets, and data changes which Workshop combines into a customized build of the game.

The build environment will use a reproducible Docker image containing the required open-source PlayStation development tools.

Legend of Mana game data will **not** be distributed with LoM Workshop. Users will provide their own game files.

## Related Project

LoM Workshop is made possible by [lom-decomp](https://github.com/celophi/lom-decomp), a matching decompilation of the PlayStation version of Legend of Mana.

## License

LoM Workshop is licensed under the [MIT License](LICENSE).

---

*Legend of Mana is the property of its respective copyright holders. LoM Workshop is an independent fan project and is not affiliated with or endorsed by Square Enix.*
