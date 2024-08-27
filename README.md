<h1 align="center">Hi there I'm <span style="color: #F2A93B">Puddi</span> 👋</h1>

<div  align="center">
    <p>Full stack dev. I prefer to learn both logic and meaning of things, since code is just a way to express them</p>
    <p>Everything I learned has been a mistake I have made. Learning something new every day!</p>
</div>

</br>

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import {IExperience} from "./interfaces/ISideProject.sol";

contract 0xPuddi is IExperience {
    string private constant TIME_ZONE = "UTC+2";
    string private constant QUALITY = "Self Learner";
    string private constant WEAKNESS = "Maverick";
    uint8 private constant YEARS_OF_EXPERIENCE = 2;
    uint248 public practice = 999;

    event Completion(string indexed project, uint256 practice);

    struct Projects {
        mapping(string => uint256) level;
        mapping(string => bool) completed;
    }
    Projects private _projects;

    /**
     * @notice Routine keeps running
     */
    function Routine(string memory project, uint248 completionLevel) external {
        uint256 level = _projects.level[project];

        for (uint256 i = level; i < completionLevel;) {
            // Try
            // Try again
            // Try again and again

            unchecked {
                ++i;
            }
        }

        _projects.level[project] = completionLevel;
        practice += completionLevel;
        _projects.completed[project] = true;

        emit Completion(project, practice);
    }
}
```

<picture display="absolute">
    <source
        srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=0xPuddi&layout=normal&custom_title=What+I+Like&bg_color=0E1116&border_color=0E1116&title_color=F2A93B&text_color=f5c275"
        media="(prefers-color-scheme: dark)"
    >
    <source
        srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=0xPuddi&layout=normal&custom_title=What+I+Like&&title_color=f5c275&text_color=F2A93B"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
    >
    <img
        src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xPuddi&layout=normal"
        alt="Top Languages"
    >
</picture>


## $\textsf{\color{Orange}\textbf{Skill\ Set}}$
### $\textsf{\color{Orange}{Frontend}}$
<p float="left">
  <img src="./assets/Logos/html5-original.svg" height="48px">
  <img src="./assets/Logos/css3-original.svg" height="48px">
  <img src="./assets/Logos/javascript-original.svg" height="48px">
  <img src="./assets/Logos/svelte-original.svg" height="48px">
  <picture>
    <source
        srcset="./assets/Logos/fiber-original-black.svg"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
        height="48px"
    >
    <source
        srcset="./assets/Logos/fiber-original.svg"
        media="(prefers-color-scheme: dark)"
        height="48px"
    >
    <img
        src="./assets/Logos/fiber-original.svg"
        height="48px"
    >
  </picture>
  <img src="./assets/Logos/react-original.svg" height="48px">
  <picture>
    <source
        srcset="./assets/Logos/nextjs-original.svg"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
        height="48px"
    >
    <source
        srcset="./assets/Logos/nextjs-original-white.svg"
        media="(prefers-color-scheme: dark)"
        height="48px"
    >
    <img
        src="./assets/Logos/nextjs-original-white.svg"
        height="48px"
    >
  </picture>
</p>

### $\textsf{\color{Orange}{Backend}}$
<p float="left">
  <picture>
    <source
        srcset="./assets/Logos/solidity-original.svg"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
        height="48px"
    >
    <source
        srcset="./assets/Logos/solidity-original-white.svg"
        media="(prefers-color-scheme: dark)"
        height="48px"
    >
    <img
        src="./assets/Logos/solidity-original.svg"
        height="48px"
    >
  </picture>
  <img src="./assets/Logos/go-original.svg" height="48px">
  <img src="./assets/Logos/javascript-original.svg" height="48px">
  <img src="./assets/Logos/java-original.svg" height="48px">
  <img src="./assets/Logos/python-original.svg" height="48px">
  <img src="./assets/Logos/rust-original.svg" height="48px">
  <img src="./assets/Logos/postgresql-original.svg" height="48px">
  <img src="./assets/Logos/c-original.svg" height="48px">
</p>

### $\textsf{\color{Orange}{DevOps}}$
<p float="left">
  <img src="./assets/Logos/docker-original.svg" height="48px">
  <img src="./assets/Logos/git-plain.svg" height="48px">
  <picture>
    <source
        srcset="./assets/Logos/github-original.svg"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
        height="48px"
    >
    <source
        srcset="./assets/Logos/github-original-white.svg"
        media="(prefers-color-scheme: dark)"
        height="48px"
    >
    <img
        src="./assets/Logos/github-original.svg"
        height="48px"
    >
  </picture>
  <picture>
    <source
        srcset="./assets/Logos/bash-original.svg"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
        height="48px"
    >
    <source
        srcset="./assets/Logos/bash-original-white.svg"
        media="(prefers-color-scheme: dark)"
        height="48px"
    >
    <img
        src="./assets/Logos/bash-original.svg"
        height="48px"
    >
  </picture>
  <img src="./assets/Logos/linux-original.svg" height="48px">
</p>

### $\textsf{\color{Orange}{Libararies}}$
<p float="left">
  <img src="./assets/Logos/hardhat-original.svg" height="48px">
  <img src="./assets/Logos/jest-plain.svg" height="48px">
  <img src="./assets/Logos/foundry-original.png" height="48px">
</p>

### $\textsf{\color{Orange}{Sometimes\ I\ use}}$
<p float="left">
  <img src="./assets/Logos/bevy-original.svg" height="48px">
  <img src="./assets/Logos/electron-original.svg" height="48px">
  <img src="./assets/Logos/tauri-original.svg" height="48px">
  <picture>
    <source
        srcset="./assets/Logos/threejs-original.svg"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
        height="48px"
    >
    <source
        srcset="./assets/Logos/threejs-original-white.svg"
        media="(prefers-color-scheme: dark)"
        height="48px"
    >
    <img
        src="./assets/Logos/threejs-original.svg"
        height="48px"
    >
  </picture>
  <img src="./assets/Logos/tensorflow-original.svg" height="48px">
  <img src="./assets/Logos/pytorch-original.svg" height="48px">
  <picture>
    <source
        srcset="./assets/Logos/latex-original.svg"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
        height="48px"
    >
    <source
        srcset="./assets/Logos/latex-original-white.svg"
        media="(prefers-color-scheme: dark)"
        height="48px"
    >
    <img
        src="./assets/Logos/latex-original.svg"
        height="48px"
    >
  </picture>
</p>