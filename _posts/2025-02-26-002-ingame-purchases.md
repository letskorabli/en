---
title: "How to Purchase In-game Items"
date: 2025-02-26
permalink: /ingame-purchases/
---

## Introduction

Lesta Games itself **do not** distribute English localization files with Lesta Game Center, So we need to add English localization manually with a modification.

[LocalizedKorabli](https://github.com/LocalizedKorabli) provides a usable English localization.

## Installation

Steps:

1. Visit [Google Drive](https://drive.google.com/file/d/1XtSlaVIqykIAi7GhV4IjB4FnMIStIgmZ) or [latest release](https://github.com/LocalizedKorabli/LestaGameCenterL10n/releases/latest) to download the LGC localization package.

2. Follow the instructions in the Picture 1&2 to check the current version and open the working directory of Lesta Game Center.
    
    P1
    ![Picture 1](/en/assets/set-english-for-lgc/1.png)

    P2
    ![Picture 2](/en/assets/set-english-for-lgc/2.png)

3. Check if the version displayed in the application matches with the one in the archive's file name. If not, update the Lesta Game Center or check the release page for a newer version of the localization pack.

4. Exit Lesta Game Center.

5. Backup the `dlls` folder in the opened directory;

6. Extract the `dlls` folder in the archive to the opened directory, and make sure a `lgc_res.dat` is replaced.

7. Launch Lesta Game Center.

8. Follow the instructions in the Picture 3 to set the language.

    P3
    ![Picture 3](/en/assets/set-english-for-lgc/3.png)

9. You are all set! Note that hardcoded contents and news will still be in Russian.

    ![Showcase](/en/assets/set-english-for-lgc/showcase.png)

## Q&A

- Q: Why is it in Russian again?

  A: Lesta Game Center itself updated the `lgc_res.dat` file. Reinstall the localization pack again.
  
- Q: Some texts missing or not translated?

  A: After the Lesta Game Center updates, it may take a while for us to sort out the new text and release the new translation, so please keep an eye on the release page. When necessary, go to LestaGameCenterL10n's [issues](https://github.com/LocalizedKorabli/LestaGameCenterL10n/issues) and create a new issue.