<p align="center">
  <a href="https://youtu.be/fibIiCN5sKY">
    <img src="https://i.ytimg.com/vi/fibIiCN5sKY/maxresdefault.jpg" alt="Watch the 15-second GitJokBo promotional video on YouTube" width="960">
  </a>
</p>

<p align="center">
  <a href="https://youtu.be/fibIiCN5sKY"><strong>▶ Watch GitJokBo in 15 seconds — sound on</strong></a><br>
  <sub>Earlier promotional footage. The interface may change before release.</sub>
</p>

<h1 align="center">GitJokBo</h1>

<p align="center">
  <strong>Your code has history. Make it easier to follow.</strong><br>
  A free, native Git client for Windows, with a living view of your repository's history.
</p>

<p align="center">
  <strong>Jokbo</strong> is Korean for <strong>family genealogy</strong>.<br>
  <sub>For everyone who has ever asked, “Which branch was that on?”</sub>
</p>

<p align="center">
  Windows x64 &nbsp; · &nbsp;
  Free for personal &amp; commercial use &nbsp; · &nbsp;
  No GitJokBo account required
</p>

<p align="center">
  <a href="https://github.com/YiMunDong/GitJokBo-Release/releases"><strong>Releases</strong></a>
  &nbsp; · &nbsp;
  <a href="#why-gitjokbo">Explore the features</a>
  &nbsp; · &nbsp;
  <a href="#get-started">Get started</a>
  &nbsp; · &nbsp;
  <a href="License.md">License</a>
</p>

---

**Coming soon.** The first public build has not been published yet. Downloads and release notes will appear on the [Releases page](https://github.com/YiMunDong/GitJokBo-Release/releases). The features below introduce the app currently in development.

## There was a reason for that branch. Probably.

The feature is on one branch. The fix is on another. The commit called `final fix` has three successors.

GitJokBo helps you follow the story with an animated lineage view built around your repository's actual commit relationships. See where work branches off, where it comes together, and what changed along the way.

Review a diff, stage your changes, and make the next commit in the same workspace. GitJokBo runs the Git for Windows you already use, with your existing Git credential helper and SSH configuration.

## Why GitJokBo?

| What you want to do | How GitJokBo helps |
| --- | --- |
| **See how the work connects** | Explore an animated lineage view alongside the commit list. Follow real parent relationships through branches and merges. |
| **Review before you commit** | Inspect file changes and diffs, stage files or individual hunks, and write your commit message in one workspace. |
| **Turn mixed changes into focused commits** | Use the visual commit composer to arrange file and hunk cards into an ordered set of commits, then review the plan before running it. |
| **Keep everyday Git work close** | Create and switch branches, merge, stash changes, and fetch, pull, or push to your remotes. |
| **Trace a change to its source** | Browse file history and line blame, or select a commit for revert or cherry-pick. |
| **Work through conflicts** | Review conflicting changes, mark resolutions, and use an external merge tool when you need one. |
| **Make the workspace your own** | Choose Cyber Joseon or a built-in theme, switch between light and dark modes, and select your interface language. |

## “Fix stuff” deserves a second draft.

You fixed the bug, cleaned up a function, and corrected the README while you were there. Now one working tree contains three perfectly reasonable commits.

The **visual commit composer** gives each change a place before you create the history:

1. **Choose the changes.** Review file and hunk cards from your working tree.
2. **Build the sequence.** Assign cards to commit slots and give each commit its own message.
3. **Review and run.** Check the planned commits, then create them in order. Leave unrelated changes for later.

Give the next person reading your history a fighting chance. There is a good chance it will be you.

## A little Joseon. A little science fiction.

**Cyber Joseon** gives GitJokBo its own visual identity, combining Korean traditional motifs with illuminated paths and animated details that respond to repository state.

Your repository is allowed to have better lighting than your office.

Prefer a different look? Choose a built-in theme and a light, dark, or system appearance. Reduced-motion and high-contrast options help adapt the presentation to your needs.

## Get started

### Requirements

| Component | Requirement |
| --- | --- |
| Operating system | Windows 10 version 1903 or later, x64. Windows 11 recommended. |
| Git | [Git for Windows](https://gitforwindows.org/) 2.35 or later, installed separately. |
| Runtime | [Microsoft Visual C++ Redistributable](https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist), x64, v14. |

### When the first build is available

1. Open the [Releases page](https://github.com/YiMunDong/GitJokBo-Release/releases), read the release notes, and download the packaged ZIP from **Assets**.
2. Extract the complete archive to a folder of your choice.
3. Keep the `Languages` folder and the included license and notice files with `GitJokBo.exe`.
4. Run `GitJokBo.exe`, choose your language and appearance, and open a Git repository. If Git is not detected, set the path to `git.exe` in Settings.

There is no installer. Git and the Visual C++ runtime are separate prerequisites. GitHub's automatically generated **Source code** archives contain this release repository, not the application.

## Your tools. Your language. Your data.

- **Four interface languages:** English, Korean, Japanese, and Simplified Chinese.
- **Custom language packs:** create a translation from the included `en.properties` file and follow `Languages/README.txt` in the application package.
- **Local settings:** preferences and custom language packs live in `%APPDATA%\GitJokBo`. Logs, caches, and backup patches use `%LOCALAPPDATA%\GitJokBo`.
- **No GitJokBo account or telemetry:** remote Git operations use your configured repositories and authentication.

## Questions before you try it?

<details>
<summary><strong>Is GitJokBo free for commercial work?</strong></summary>

Yes. Personal, educational, corporate, commercial, and governmental use is free under the [license agreement](License.md). GitJokBo is proprietary freeware; its source code is not distributed.

</details>

<details>
<summary><strong>Does GitJokBo include Git?</strong></summary>

Git must be installed separately. GitJokBo uses your installed Git for Windows and its credential helper and SSH settings. You can choose a specific `git.exe` in Settings.

</details>

<details>
<summary><strong>Can I share it with someone else?</strong></summary>

You may share a complete, unmodified copy free of charge under the conditions in [section 4 of the license](License.md#4-free-sharing). Sharing the Releases link is an easy way to help others find the available builds.

</details>

<details>
<summary><strong>How do I remove it?</strong></summary>

Close GitJokBo and delete the extracted application folder. Settings and other local data remain in the folders listed above. Remove those separately if you no longer need them, including any backup patches.

</details>

## Help shape GitJokBo

Found something odd? Have a workflow that could use fewer clicks? [Open an issue](https://github.com/YiMunDong/GitJokBo-Release/issues).

For bug reports, include your GitJokBo version, Windows version, Git version, and the steps needed to reproduce the problem. A small reproducible example is especially welcome. Remove credentials and private repository content from any screenshots or logs you share.

This repository is the home for GitJokBo downloads, release notes, and feedback.

---

<p align="center">
  <a href="https://github.com/YiMunDong/GitJokBo-Release/releases">Releases</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/YiMunDong/GitJokBo-Release/issues">Feedback</a>
  &nbsp; · &nbsp;
  <a href="License.md">License</a>
</p>

<p align="center"><sub>Copyright © 2026 YiMunDong. All rights reserved.</sub></p>
