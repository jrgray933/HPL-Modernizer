# HPL Modernizer

HPL Modernizer gives **Amnesia: The Dark Descent**, **Justine**, **Amnesia: A Machine for Pigs**, and **SOMA** a shared Windows launcher, modern display options, and optional higher-resolution textures. You’ll need your own Steam copy of each game you want to play.

## What you can play

| Game | Features | Optional textures |
| --- | --- | --- |
| **Amnesia: The Dark Descent and Justine** | OpenGL or Vulkan, field-of-view and frame-rate controls, and Vulkan options for softer shadows, lighting, water effects, and edge smoothing. Launch the original campaign, Justine, or installed custom stories. | 2× or 4× |
| **Amnesia: A Machine for Pigs** | OpenGL or Vulkan, field-of-view and frame-rate controls, and Vulkan graphics options including color controls, adjustable world brightness, and lantern brightness and beam width. | 2× or 4× |
| **SOMA** | Adjustable field of view and frame-rate limit, anti-aliasing and texture filtering, a depth-of-field toggle, and an option to prepare shaders during loading for smoother play. | 4× |

You can use the games’ original textures or choose an installed texture pack. The launcher also offers themes and adjustable interface size.

## Install and play

1. Open [Releases](https://github.com/jrgray933/HPL-Modernizer/releases/latest). Download **HPL Modernizer Launcher** and the game downloads you want. You’ll need 64-bit Windows 10 or 11 and the corresponding games installed through Steam.
2. Extract the launcher ZIP and run the installer inside. Install the launcher first, even if you only want SOMA.
3. For either Amnesia game, install the [Microsoft Visual C++ Redistributable for x64](https://aka.ms/vc14/vc_redist.x64.exe). If Microsoft’s installer says a newer version is already installed, you can continue.
4. Extract and run each game installer. When asked, choose your HPL Modernizer launcher folder and the game’s original Steam folder. In Steam, right-click the game and choose **Manage → Browse local files** to find it. The Dark Descent installer also covers Justine.
5. Install any optional texture packs using the steps below. Open **HPL Modernizer** from the Start menu, choose your game, and launch it.

SOMA requires Steam build 20049349.

The first launch can take a few minutes while HPL Modernizer prepares the game. Texture packs need extra free space for both installation and that first launch.

## Install a texture pack

1. Install the matching game component first. Download the texture pack you want, including **every numbered part** if it has more than one ZIP.
2. Right-click each ZIP and choose **Extract All**. For a numbered pack, pick the **same extraction destination** for every part. Each ZIP places its files in the same named pack folder.
3. After extracting every part, open the pack folder and run the installer. Leave the files ending in **.cab** next to the installer.
4. Select the texture pack for your game in HPL Modernizer.

## Custom stories and uninstalling

- Put The Dark Descent custom stories in the original game’s **custom_stories** folder, then select the story in HPL Modernizer.
- Close your game before installing, repairing, or removing a component. Use **Installed apps** in Windows to remove texture packs first, then game components, then the launcher. Your original games and saves are preserved.
