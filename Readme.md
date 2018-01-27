# Awesome USD [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Projects and resources relating to Pixar's [Universal Scene Description](http://openusd.org)


## Contents

- [Reference](#reference)
- [Samples](#samples)
- [Building and Distros](#building-and-distros)
- [Integrations](#integrations)
- [Tools](#tools)
- [Hydra](#hydra)

## Reference

- [openusd.org](http://openusd.org) The official website
- [USD Interest Google Group](https://groups.google.com/forum/#!forum/usd-interest)
- [Introductory Videos](http://graphics.pixar.com/usd/downloads.html) Several video presentations by Pixar
- [UsdSkel](http://graphics.pixar.com/usd/files/SkinningOM.md.html) All about skinning schemas for USD
- [Using USD with Apple's technologies](https://developer.apple.com/videos/play/wwdc2017/610/) WWDC 2017 presentation

## Samples
- [Samples from Pixar](http://graphics.pixar.com/usd/downloads.html) Two assets are available for testing here

## Building and Distros

There are a variety of strategies for building USD.

- [Official USD repo](https://github.com/PixarAnimationStudios/USD) The repo includes a robust build script that pulls canonical dependency sources, and can build for all supported platforms.
- [USD Build Club](https://github.com/vfxpro99/usd-build-club) This is the most thorough and flexible method for building USD and all its dependencies for macOS and Windows. Dependencies are fetched from canonical sources.
- [Saturn](https://github.com/VictorYudin/saturn) Windows build recipes, and AppVeyor build of binaries.
- [Ubuntu scripts](https://github.com/tlorach/USD_build)
- [Rez](https://github.com/piratecrew/rez-usd)
- [Docker Package](https://github.com/AnimalLogic/docker-usd)
- [RodeoFX's dependency builds](https://github.com/rodeofx/usd-deps) Includes tarred sources for USD dependencies at vfxplatform point revisions.


## Tools

- [Syntax Highlighting](https://github.com/superfunc/usda-syntax) Syntax Highlighting for usda files in vim, emacs, atom, vscode & sublime.
- [Sublime Syntax Highlighter](https://github.com/davidlatwe/PixarUSD-Sublime) Syntax highlighter for Sublime.
- [Notepad++ Highlighter](https://github.com/Andrew/Hazelden/PIXAR-USD-Syntax-Highlighter) Syntax highlighter for Notepad++

## Hydra

- [GTC 2015](http://on-demand.gputechconf.com/gtc/2015/presentation/S5327-Jeremy-Cowles.pdf) Jeremy Cowles' GTC2015 presentation introducing Hydra
- [Switch](https://github.com/VictorYudin/switch) Victor Yudin has built a game using Hydra as the render engine
- [Tutorials](https://github.com/dboogert/USD/tree/tutorials/extras/usd/tutorials/IETutorials) Tutorials on using Hydra as a stand-alone render system
- [USD-tests](https://github.com/dboogert/USD-tests) Examples for learning USD and Hydra APIs

## Integrations

- [AL_USDMaya](https://github.com/AnimalLogic/AL_USDMaya) Animal Logic's exporter maintains a live connection between the Maya and USD scenegraphs
- [Arnold](https://github.com/LumaPictures/usd-arnold) Luma Pictures USD bridge for Arnold
- [Houdini](https://graphics.pixar.com/usd/docs/Houdini-USD-Plugins.html)
- [Katana](https://graphics.pixar.com/usd/docs/Katana-USD-Plugins.html)
- [Model I/O](https://developer.apple.com/documentation/modelio) Apple's Model I/O brings USD to Metal
- [Multiverse](http://multi-verse.io/) Scene assembly, set dressing, and inter-op with DCC applications
- [SceneKit](https://developer.apple.com/documentation/scenekit) Apple's SceneKit can read and write USD files for native rendering on all Apple platforms
- [TiltBrush](https://docs.google.com/document/d/11ZsHozYn9FnWG7y3s3WAyKIACfbfwb4PbaS8cZ_xjvo/preview) TiltBrush v15 can export USD camera tracks
- [Unreal](https://github.com/epicgames/unrealengine) Unreal 4.18 includes a USD importer
- [USD for Unity](https://github.com/unity3d-jp/USDForUnity) USD and Alembic importer/exporter plugin for Unity
- [USD Qt](https://github.com/LumaPictures/usd-qt) Luma Pictures has created some reusable Qt widgets to work with USD

## Contribute

Contributions are welcome - see the[contribution guidelines](contributing.md)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and
related or neighboring rights to this work.
