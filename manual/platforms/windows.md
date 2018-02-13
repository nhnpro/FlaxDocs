# Windows

## Build options

![Build Options](media/build-windows.jpg)

| Property | Description |
|--------|--------|
| **Output** | The builded game output folder (relative to the project). |
| **Show Output** | If checked, after building the output folder will be shown in an Explorer. |
| **Configuration Mode** | Game building mode. Possible options: <table><tbody><tr><th>Option</th><th>Description</th></tr><tr><td>**Release**</td><td>The release build ready for shipment.</td></tr><tr><td>**Debug**</td><td>The debug build for testing and profiling.</td></tr></tbody></table>|
| **Architecture** | Target platform CPU type. Possible options: <table><tbody><tr><th>Option</th><th>Description</th></tr><tr><td>**x64**</td><td>The 64-bit.</td></tr><tr><td>**x86**</td><td>The 32-bit.</td></tr></tbody></table>|
| **Defines** | Array of custom script defines to use during source code compilation. |

## Platform settings

![Settings](media/settings-windows.jpg)

| Property | Description |
|--------|--------|
| **Fullscreen Mode** | If checked, game will use fullscreen mode as default. |
| **Screen Width** | The default game window width (in pixels). |
| **Screen Height** | The default game window height (in pixels). |
| **Resizable Window** | Enables resizing the game window by the user. |
| **Run In Background** | Enables game running when application window loses focus. |
| **Force Single Instance** | Limits maximum amount of concurrent game instances running to one, otherwise user may launch application more than once. |
| **Override Icon** | Custom icon texture to use for the application (overrides the default one). |
| **Support DirectX 10** | If checked, game will support DirectX 10 and DirectX 10.1. Otherwise app won't launch if no DirectX 11 supported. This reduces compiled shaders count. |
