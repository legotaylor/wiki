---
title: Resourcepack Guide
layout: page
lang: en
parent: Luminance
nav_order: 1
---
# Resourcepack Guide

{: .note }
> This guide has been ported over from [mclegoman/luminance:ResourcepackGuide](https://github.com/mclegoman/luminance/blob/master/ResourcepackGuide), which is licenced under [LGPL-3.0-or-later](https://github.com/mclegoman/luminance/blob/master/licence).

{: .author }
> [Nettakrim](https://bsky.app/profile/nettakrim.netal.co.uk)

This guide is split into 3 parts, each part assumes knowledge from the previous section

1. [Setting up a Resourcepack](./PackSetup)
2. [Adding a Shader](./AddingShaders)
3. [Writing custom Shader code](./WritingShaderCode)

This is specifically a guide for making a [Luminance](https://modrinth.com/mod/luminance) compatible resourcepack, for use with [Souper Secret Settings](https://modrinth.com/mod/souper-secret-settings) or [Perspective](https://modrinth.com/mod/mclegoman-perspective) (or any other mod that uses Luminance)

However, it also covers a lot of general post shader topics, so you could also use this as a guide for making vanilla post shaders (e.g, to then apply through the transparency.json from fabulous graphics)

There is a discord server called [shaderLABS](https://discord.gg/RpzWN9S) for vanilla/optifine/iris shaders - while the people there can probably help with some things, Luminance adds extra features so it isnt *exactly* the same as working with vanilla post shaders

The guide will use Souper Secret Settings specifically to demonstrate how features work, since it exposes a lot of the structure of existing shaders

This guide is written by [Nettakrim](https://bsky.app/profile/nettakrim.netal.co.uk), if there are any problems, let me know!

# Guides for mods using Luminance

Souper Secret Settings has a few specific features, see [its page](Soup) for a guide.

As does Perspective, see [it's page](./Perspective) for a guide.

