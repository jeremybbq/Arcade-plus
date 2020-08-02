# Arcade-plus

Arcade is a utility used to edit and preview aff files. The original Arcade repository is DMCA takedowned (see [the DMCA takedown](https://github.com/github/dmca/blob/master/2019/02/2019-02-27-Arcaea.md)). The author of the original Arcade , [cnSchwarzer](https://github.com/cnSchwarzer) aka Sch, refused to remove copyright contents owned by Lowiro, the developer of the Arcaea. Sch use a Chinese code hosting platform after that instead.

This project, Arcade-plus bring it back to GitHub. It does not contains copyright contents, but uses a skinning feature instead. Also we have better commit messages and less bug. We will even adds some new features, get some redesign and do some performance optimization.

The original commit history of Sch are not be included in this repository, since they contains copyright contents.

## Q&A

### Arcade-plus do not work on my OS!

Arcade-plus is only completely tested on Latest Windows 10. However it should works on Windows 7 or 8. Older version of Windows is not supported.

Also, macOS and Linux support is experimental for now, if you find any bug that only happens on your OS, please help us by open a bug-fixing pull request.

### Why this version do not have localisation feature?

Localisation feature was supported in old versions of Arcade. However, Sch decided to remove this feature because bad code design and messing UI layout. Because of this, we removed this feature as well.

Also, UI Layout was completely reworked in this fork, so adding localisation feature back is somehow acceptable, but we will do some other works before that. Pull request is always welcomed though.

### The playfield does not look like the old Arcade!

Due to copyright issue, we can not use old graphic and sound assets. You need to find a set of skin to make it back. The documentation of skinning is not availiable now, but you can read our implementation of skinning system to know the structure of skin folder for now.

## license

Most parts of this project is licensed under the MIT license. See [License](LICENSE). The exceptions are listed below:

- Files under `Packages` folder come from Unity Package Manager. It is recommended by Unity to include the folder in the version control system. These files are licensed by their authors, including Unity Technologies and other authors
- Files under `UIElementsScheme` folder are used by some components in Unity Editors, and licensed by Unity Technologies. We do not use UIElements feature in this project ourself.
- Files under `Assets/Plugins` folder are downloaded and unzipped from NuGet. Unity itself do not provide a way to download and load dependencies from NuGet, so we should put them into assets manually and include them in the version control system. These files are licensed by their authors.
- Files under `Assets/Demigiant` folder and `Assets/Resources` folder are generated by [DOTween plugin](http://dotween.demigiant.com/). These files are licensed by Daniele Giardini.
- Files under `Assets/SFB` comes from [Unity Standalone File Browser](https://github.com/gkngkc/UnityStandaloneFileBrowser). These files are licensed by gkngkc and other authors.
- Files under `Assets/DefaultSkin/Sound` folder are samples bundles with and modified using [LMMS](https://lmms.io). These files are in public domains.
- Files under `Assets/Textures/Icon/MDI` are generated from [Material Design Icons](https://materialdesignicons.com/), go to their site for license issue.
- The `Assets/Textures/Icon/OBS.png` are generated from the icon of [Open Broadcaster Software](https://obsproject.com/), go to their site for license issue.
- Files under `Assets/Fonts` are free font files. These files are licensed by their authors.