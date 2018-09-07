# USD Projects and Resources

Projects and resources relating to Pixar's [Universal Scene Description](http://openusd.org)


## Contents

- [Reference](#reference)
- [Integrations](#integrations)
- [Samples](#samples)
- [Building and Distros](#building-and-distros)
- [Syntax Highlighters](#syntax-highlighters)
- [Hydra](#hydra)

## Reference

- [openusd.org](http://openusd.org) The official website
- [USD Interest Google Group](https://groups.google.com/forum/#!forum/usd-interest)
- [Introductory Videos](http://graphics.pixar.com/usd/downloads.html) Several video presentations by Pixar
- [UsdSkel](http://graphics.pixar.com/usd/files/SkinningOM.md.html) All about skinning schemas for USD
- [USD based pipelines](https://vimeo.com/188191100) 2016 presentation on Pixar's use of USD in the pipeline
- [Using USD with Apple's technologies](https://developer.apple.com/videos/play/wwdc2017/610/) WWDC 2017 presentation
- [USDZ at Apple](https://developer.apple.com/videos/play/wwdc2018/603/) WWDC 2018 presentation
- [USD at Animal Logic](https://www.youtube.com/playlist?list=PLNUaMVwYjKk8QDlM8gQSLbl8jxLRgc7d6) video presentations


## Integrations

- Apple Finder and Preview application can display USD files natively
- [AL_USDMaya](https://github.com/AnimalLogic/AL_USDMaya) Animal Logic's exporter maintains a live connection between the Maya and USD scenegraphs
- [AL_USDMaya](https://www.youtube.com/watch?v=RluuvOAXvnk) Presentation about the AL_USDMaya workflow
- [Arnold](https://github.com/LumaPictures/usd-arnold) Luma Pictures USD bridge for Arnold
- [OpenWalter](https://github.com/rodeofx/OpenWalter) Rodeo FX's USD plugin suite for Arnold, Houdini, Katana and Maya.
- [Houdini](https://graphics.pixar.com/usd/docs/Houdini-USD-Plugins.html)
- [Katana](https://graphics.pixar.com/usd/docs/Katana-USD-Plugins.html)
- [Model I/O](https://developer.apple.com/documentation/modelio) Apple's Model I/O brings USD to Metal
- [Multiverse](http://multi-verse.io/) Scene assembly, set dressing, and inter-op with DCC applications
- [SceneKit](https://developer.apple.com/documentation/scenekit) Apple's SceneKit can read and write USD files for native rendering on all Apple platforms
- [TiltBrush](https://docs.google.com/document/d/11ZsHozYn9FnWG7y3s3WAyKIACfbfwb4PbaS8cZ_xjvo/preview) TiltBrush v15 can export USD camera tracks
- [Unreal](https://github.com/epicgames/unrealengine) Unreal 4.18 includes a USD importer
- [Unity USD SDK](https://github.com/googlevr/usd-unity-sdk) Full C# bindings to the USD SDK
- [Unity USD SDK](https://www.youtube.com/watch?v=FnKWixYmSRY) Presentation about the Unity USD SDK
- [USD for Unity](https://github.com/unity3d-jp/USDForUnity) USD and Alembic importer/exporter plugin for Unity
- [USD Qt](https://github.com/LumaPictures/usd-qt) Luma Pictures has created some reusable Qt widgets to work with USD
- [Gaffer](https://github.com/GafferHQ/gaffer) USD is available for SceneReader node and SceneWriter node from v0.42.0.0
- [nVidia RTX](https://www.nvidia.com/en-us/design-visualization/technologies/rtx) USD is supported for asset interchange on the RTX platform
- [Aero](https://www.adobe.com/products/projectaero.html) Adobe's Project Aero
- [Apple News](https://developer.apple.com/documentation/apple_news/arkit) USDZ files can be embedded in Apple News articles

## Hydra

- [GTC 2015](http://on-demand.gputechconf.com/gtc/2015/presentation/S5327-Jeremy-Cowles.pdf) Jeremy Cowles' GTC2015 presentation introducing Hydra
- [Switch](https://github.com/VictorYudin/switch) Victor Yudin has built a game using Hydra as the render engine
- [Tutorials](https://github.com/dboogert/USD/tree/tutorials/extras/usd/tutorials/IETutorials) Tutorials on using Hydra as a stand-alone render system
- [USD-tests](https://github.com/dboogert/USD-tests) Examples for learning USD and Hydra APIs
- [HydraNSI](https://gitlab.com/3DelightOpenSource/HydraNSI) Usdview Hydra delegate for 3Delight NSI
- [AMD ProRender](https://github.com/GPUOpen-LibrariesAndSDKs/RadeonProRenderUSD) AMD ProRender raytracing Hydra delegate


## Samples

- [Samples from Pixar](http://graphics.pixar.com/usd/downloads.html) Two assets are available for testing here
- [ARKit](https://developer.apple.com/arkit/gallery/) USDZ format assets from Apple
- [Samples from FusionAR](https://www.fusionar.app/) USDZ format assets

## Tools

- [gltf2usd](https://github.com/kcoley/gltf2usd) Convert gltf 2.0 files to USD

## Building and Distros

There are a variety of strategies for building USD.

- [Official USD repo](https://github.com/PixarAnimationStudios/USD) The repo includes a robust build script that pulls canonical dependency sources, and can build for all supported platforms.
- [USD Build Club](https://github.com/vfxpro99/usd-build-club) This is the most thorough and flexible method for building USD and all its dependencies for macOS and Windows. Dependencies are fetched from canonical sources.
- [Saturn](https://github.com/VictorYudin/saturn) Windows build recipes, and AppVeyor build of binaries.
- [Ubuntu scripts](https://github.com/tlorach/USD_build)
- [Rez](https://github.com/piratecrew/rez-usd)
- [Docker Container](https://github.com/AnimalLogic/docker-usd)
- [RodeoFX's dependency builds](https://github.com/rodeofx/usd-deps) Includes tarred sources for USD dependencies at vfxplatform point revisions.
- [Apple, macOS](https://developer.apple.com/go/?id=python-usd-library) Apple has a build availble here


## Syntax Highlighters

- [VSCode Highlighting](https://github.com/AnimalLogic/AL_usd_vscode_extension)
- [Syntax Highlighting](https://github.com/superfunc/usda-syntax) for vim, emacs & sublime.
- [Sublime Syntax Highlighter](https://github.com/davidlatwe/PixarUSD-Sublime)
- [Notepad++ Highlighter](https://github.com/Andrew/Hazelden/PIXAR-USD-Syntax-Highlighter)

## Contribute

Contributions are welcome - see the[contribution guidelines](contributing.md)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and
related or neighboring rights to this work.
