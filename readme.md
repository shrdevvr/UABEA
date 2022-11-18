<p align="center"><img src="UABEAvalonia/Assets/logo.png" /></p>

[Latest Nightly Build](https://nightly.link/nesrak1/UABEA/workflows/dotnet-desktop/at3/uabea-windows.zip) | [Latest Release](https://github.com/nesrak1/UABEA/releases)

[![GitHub issues](https://img.shields.io/github/issues/nesrak1/UABEA?logo=GitHub&style=flat-square)](https://github.com/nesrak1/UABEA/issues) [![discord](https://img.shields.io/discord/862035581491478558?label=discord&logo=discord&logoColor=FFFFFF&style=flat-square)](https://discord.gg/hd9VdswwZs)

## UABEAvalonia

Cross-platform Asset Bundle/Serialized File reader and writer. Originally based on [UABE](https://github.com/SeriousCache/UABE).

## Extracting assets

I develop UABEA as more of a modding/research tool than an extracting tool. Use [AssetRipper](https://github.com/AssetRipper/AssetRipper) or [AssetStudio](https://github.com/Perfare/AssetStudio/) if you only want to extract assets.

## Addressables

Many games are also now using addressables. You can tell if the bundle you're opening is part of addressables because it has the path `StreamingAssets/aa/XXX/something.bundle`. You will need to clear the CRC checks with the CRC cleaning tool here.

## Libraries

The new update is being worked on here: https://github.com/nesrak1/UABEA/tree/at3