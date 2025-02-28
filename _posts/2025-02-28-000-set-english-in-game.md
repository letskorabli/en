---
title: "Set Mir Korabley Game to English"
date: 2025-02-28
permalink: /set-english-in-game/
---

## Introduction

Lesta Games itself **do not** distribute English localization files with Mir Korabley, So we need to add English localization manually with a modification.

[LocalizedKorabli](https://github.com/LocalizedKorabli) provides a usable English localization with text translated by generative AI, with basic human proofreading.

## Installation

There are 2 ways to install localization:

### 1. Via LocalizedKorabli I18n Installer

LocalizedKorabli provides a GUI tool to install the latest available localization smoothly.

Steps:

- Visit I18nInstallerGUI's [latest release](https://github.com/LocalizedKorabli/I18nInstallerGUI/releases/latest).

- Go to **Assets**, click the executable file listed to download it.

- Run the executable to install the I18n Installer.

- Run the I18n Installer. Don't worry if you forget to select “Create a desktop shortcut” during the installation process and then unfortunately can't find the Installer. You will find it in the Start Menu.

- If the game is running, **close it**.

- Select the right game dir, choose your desired I18n Source (GitLab - Faster download; GitHub - Always up-to-date), and click **Install I18n**.

- After the installation is complete, a prompt window will pop up. Then you are all set!

### 2. Install Manually

Steps:

- Visit LocalizedKorabli's [post](https://forum.korabli.su/topic/163517-) on the Mir Korabley official forum.

- Click the red **СКАЧАТЬ / DOWNLOAD** button to redirect to Google Drive file sharing page.

- Click the download button in the upper right corner.

- Locate the installation path of Mir Korabley client, usually **X:/Games/Korabli**.

- Go to the **bin** folder where you may see multiple folders named with more than 7 digits, e.g. **8801689**. Select the two of these folders with the largest values and perform the following.

- Go to the designated "digits" folder, and then go to the **res_mods** folder.

- If the game is running, **close it**.

- Unzip the downloaded .zip file to **res_mods**.

- The final directory structure will be like this below (assume that the designated folders are **8801322** and **8801689**):

******
    Game Directory
    └─bin
        ├─8801322
        │   └─res_mods
        │       │   locale_config.xml
        │       └─texts
        │           └─ru
        │              └─LC_MESSAGES
        │                   global.mo
        │
        └─8801689
            └─res_mods
                │   locale_config.xml
                └─texts
                    └─ru
                       └─LC_MESSAGES
                            global.mo
******

## Q&A

- Q: Armory and dockyard unlocalized?

  A: Those are website pages displayed by the game's built-in browser and are not able to be localized via GetText MO localization.
  
- Q: After a certain startup, the game shows up in Russian again?

  A: The build number folder in the **bin** directory is replaced with each version update, just reinstall the localization mod.

- Q: What if there are mistranslated or untranslated texts?

  A: Go to Korabli-LESTA-I18N's [issues](https://github.com/LocalizedKorabli/Korabli-LESTA-I18N/issues) and create a new issue.