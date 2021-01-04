# Personal Windows Terminal Settings

<!-- Draw inspiration from https://github.com/JanDeDobbeleer/oh-my-posh -->

## Table of Contents

- [About](#about)
- [Windows Terminal](#windows-terminal-settings)
- [PowerShell Core](#powershell-core)

## About

This repository stores my personal settings. I create this for my own reference whenever I need to configure a new development environment. Use this for setting up your own settings for your development environments.

## Windows Terminal Settings

This section talks about settings of the [Windows Terminal](https://github.com/microsoft/terminal). I use this application from Microsoft to run all my shells.

To open up `settings.json` file that stores all the settings, use `Ctrl+,`. My personal settings is stored in the `Windows Terminal` folder of this repo. The file is fully commented so reference that to make your own. However, there are a few notes:

- I use PowerShell Core as my main shell so that is my `defaultProfile`. All GUID is hidden but you can easily generate GUID by using a shell or online resources.
- I use Nerd Font variation of Cascadia Code which can be found [here](https://www.nerdfonts.com/font-downloads). This has the ligatures and glyphs used in my PowerShell prompt customisation (see [PowerShell Core](#powershell-core)).
- I use `One Half Dark` colour scheme for PowerShell, available out of the box with Windows Terminal.
- I use a custom colour scheme called `Ubuntu` to mimic Ubuntu terminal colours. Check the source code for specifics.

## PowerShell Core
