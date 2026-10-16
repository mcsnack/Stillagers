# Stillagers — Minecraft 26.3 fork

A fork of [Stillagers by surfrock66](https://github.com/surfrock66/Stillagers), updated for Minecraft Java Edition 26.3.

The 26.3 data pack format is 121.0. This fork updates the pack metadata and extends the modern function-layout overlay to that format. The functions and gameplay behavior remain the same as upstream.

## Use

1. Put the `stillagers` folder (or the contents of `Stillagers-26.3.zip`) in the world's `datapacks` directory.
2. Run `/reload`.
3. Name-tag a villager `Stillager` or `stillager` to stop its AI and pathfinding. Its trades are manually restocked at 08:00 and 14:00 Minecraft time.
4. Name-tag it `Moveager` or `moveager` to restore its AI.
5. Run `/function stillagers:uninstall` to remove the pack's effects and scheduled function.

Back up the world before installing. Since AI is disabled, villagers will not use workstations or restock through normal AI; the pack resets up to ten trade uses twice per Minecraft day.

## Attribution and license

Based on Stillagers by Surfrock66. Original work and this fork are licensed under the GNU Affero General Public License v3 or later; see [LICENSE](LICENSE).
