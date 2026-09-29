# ultimate-pi-bmad

Optional BMAD bridge for [Ultimate PI](https://github.com/VisionCraft3r/ultimate-pi).

A default Ultimate PI install does not include this package and does not download it. Install asks separately: "Install the BMAD bridge? Only if this machine uses BMAD." The default is no. Answering yes runs `pi install git:github.com/VisionCraft3r/ultimate-pi-bmad`.

`ultimate-pi setup packages` can add it later. `ultimate-pi uninstall --full` removes it with the other third-party packages.

Pi loads `extensions/bmad-bridge.ts` only. Helpers live in `lib/` so they are not treated as extensions.
