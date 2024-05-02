# Lucy JetBrains Theme - Unofficial

Since I started programming, I've always used and loved the Lucy theme from VS Code. However, there was never an
official version for the JetBrains IDE's, so I made my own.

It is worth noting that this theme was generated from the
official [Jetbrains Tool](https://github.com/JetBrains/colorSchemeTool) that converts VS Code themes to JetBrains IDE's

# How to use

1. Clone the `colorSchemeTool` code.
2. Download the JSON file with the VS Code theme you’d like to convert.
3. Move the JSON file to the `vscThemes` folder under `colorSchemeTool`.
4. Run the `convert.sh` script.
5. Check the `intellijThemes` folder – you should find a new `.icls` file there.

## How to apply converted theme

1. In your IDE, go to `Preferences / Settings | Editor | Color Scheme`.
2. Click on the `Show Scheme Actions` gear icon and select `Import Scheme...`.
3. Choose the newly converted `.icls` file.

# Commands used

```bash
 node vscToTm.js ".\vscThemes\lucy-evening.json" ".\out\lucy-evening.tmTheme"
 node vscToTm.js ".\vscThemes\lucy.json" ".\out\lucy.tmTheme"Ø
```