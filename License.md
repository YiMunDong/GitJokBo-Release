# GitJokBo License Agreement

Version 1.0 — effective 2026-10-07

Copyright (c) 2026 YiMunDong. All rights reserved.

"GitJokBo" (the "Software") is created and owned by an individual, YiMunDong (the "Author").
By downloading, installing, copying or using the Software you agree to this agreement. If you do not agree, do not use the Software.
**This English text is the governing version.**

## 1. Free use

The Author grants you a non-exclusive, non-transferable, worldwide, royalty-free license to install and use the Software, in its unmodified form, for any purpose —
personal, educational, corporate, commercial or governmental — at no charge, on any number of your own computers.
You may use the Software for your paid work, and you may install it for your employees and contractors to use in their work for you.
The Author does not charge for the Software and may not later charge you for the version you already received.

## 2. Ownership

The Software, its name, logo, icons, text and design are protected by copyright and other laws. All rights, title and interest remain solely with the Author.
This agreement grants a license to use the Software; it does not transfer ownership of the Software or any part of it.
No user or third party may claim ownership of, or copyright in, the Software or any part of it.
You own your own data that you create with the Software; the Author claims no rights to it.

## 3. Restrictions

You may not, without the Author's prior written permission:

1. **Sell, rent, lease, sublicense or otherwise charge money for** the Software, whether modified or not, including charging for access to a download, or including the Software in a paid product, service, subscription or paid software collection.
2. **Redistribute** the Software, except as allowed in section 4.
3. **Modify, adapt, translate or create derivative works of** the Software, or **reverse engineer, decompile or disassemble** it, or try to extract its source code or any part of it, including the code of the framework it is built on, except to the extent that applicable law expressly allows despite this restriction.
4. **Remove or alter** copyright, license or trademark notices in the Software.
5. **Use the name "GitJokBo" or its logo** for another product or in a way that suggests the Author endorses you or your work. Saying truthfully that your work "works with GitJokBo" is allowed.

The source code of the Software is proprietary. It is not published, and nothing in this agreement gives you any right to it.

## 4. Free sharing

You may share an **unmodified, complete copy** of the Software with others, free of charge, if you (a) keep this license agreement with it, (b) charge nothing for it (recovering only your actual cost of media or bandwidth is fine), and (c) do not present it as your own work.
An organization may keep an unmodified copy on its own internal file server to install the Software on its own computers.

Language pack files (`*.properties`) that you write yourself for the Software are your own work; you may share them as you wish.

## 5. Third-party components and the framework

5.1 **Third-party components.** The Software contains third-party components (for example, open source libraries and typefaces). They are licensed to you under their own license terms,
shown in the "Third-party notices" part of the About screen of the Software. This agreement does not change those terms, and nothing here restricts any rights those licenses give you.

5.2 **Framework.** The Software is built on the SiBelHommeGUI GUI framework, which is statically linked into the Software. The framework was created and is owned by the Author; it is not third-party software.
It is proprietary and its source code and libraries are not published. It is provided to you only as part of the Software, under this agreement; this agreement grants no separate right to it, and sections 2 and 3 apply to it.

## 6. What the Software does

GitJokBo is a Windows desktop client for Git repositories. It shows the commit history of a repository as a lineage view and, when you ask it to, performs Git operations such as staging, committing, creating and switching branches, merging, stashing, discarding changes, fetching, pulling and pushing.

**It runs the Git that you installed.** The Software does not include Git. It finds Git for Windows on your computer (or uses the path you set) and runs it to read and change your repositories. Git for Windows is licensed to you by its own authors, not under this agreement.

**You are responsible for the operations you run.** Git operations change the files in your working folders, the history of your repositories and, when you push, the repositories on your remote servers. Some operations (for example discarding changes, deleting branches or stashes, or pushing over a remote branch) can lose work. The Software asks for confirmation before such operations and keeps a backup patch before it discards changes, but confirmations and backups are best-effort aids, not guarantees. Keep your own backups of important work.

**Sign-in.** The Software uses the credential helper and SSH settings that your Git already uses. When Git asks a question such as a password, passphrase or host key confirmation, the Software shows it in a dialog and passes your answer to that Git process only. The Software does not store your passwords or tokens.

**Data and network.**

- The Software stores its settings and your own language packs in `%APPDATA%\GitJokBo`, and may store logs, caches and backup patches of discarded changes in `%LOCALAPPDATA%\GitJokBo` on your computer. It does not send them anywhere.
- The Software sends nothing to the Author. It has no telemetry, no usage statistics, no accounts and no automatic update checks.
- The Software itself does not open network connections. Network connections are made only by Git when you run an operation that needs one (for example clone, fetch, pull or push), and only to the remote repositories that you configured or entered.
- Links shown in the Software (for example the Git for Windows download page) open in your web browser only when you click them.

## 7. Disclaimer of warranty

TO THE FULLEST EXTENT PERMITTED BY LAW, THE SOFTWARE IS PROVIDED "AS IS" AND "AS AVAILABLE", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, ACCURACY, AVAILABILITY, OR THAT THE SOFTWARE WILL BE ERROR-FREE, SECURE OR UNINTERRUPTED. THE AUTHOR IS AN INDIVIDUAL AND PROVIDES NO SUPPORT, MAINTENANCE OR UPDATES UNLESS THE AUTHOR CHOOSES TO.

## 8. Limitation of liability

TO THE FULLEST EXTENT PERMITTED BY LAW, THE AUTHOR IS NOT LIABLE FOR ANY CLAIM, LOSS OR DAMAGE (DIRECT, INDIRECT, INCIDENTAL, SPECIAL, CONSEQUENTIAL OR PUNITIVE), INCLUDING LOSS OF DATA, PROFITS, BUSINESS OR SYSTEM DAMAGE,
ARISING FROM THE USE OF, OR INABILITY TO USE, THE SOFTWARE, EVEN IF THE AUTHOR WAS TOLD IT MIGHT HAPPEN.
Because the Software is free, the Author's total liability for any claim relating to it is limited, to the extent the law allows, to the amount you paid the Author for it, which is zero.
If the law of your country does not allow part of these exclusions, they apply only to the extent that the law allows; the rest of this agreement remains valid.

## 9. Term and termination

This agreement lasts as long as you use the Software. If you breach it, your license ends automatically, and you must stop using the Software and delete all copies.
The Author may stop distributing the Software, or release new versions under new terms, at any time. A version you already have stays under the terms you received it with, as long as you follow them.

## 10. Feedback

If you send the Author ideas, suggestions or bug reports, the Author may use them freely without payment or obligation to you. Do not send secrets or personal data.

## 11. General

- **Governing law and courts:** the laws of the Republic of Korea govern this agreement, and the Seoul Central District Court has exclusive jurisdiction of first instance over any dispute, to the extent the law of your country allows this choice.
- **Rights that cannot be waived:** nothing in this agreement limits rights you have under mandatory law (for example consumer protection law), where such law applies.
- **If one clause is invalid,** the others remain in force.
- **Entire agreement:** this is the whole agreement about the Software between you and the Author. The Author may publish a newer version of this agreement for newer versions of the Software.
- **No waiver:** if the Author does not enforce a clause at some time, the Author does not give up that right.
- **Reserved rights:** all rights not expressly granted here are reserved by the Author.
