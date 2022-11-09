# Awesome Electron.js hacking & pentesting resources

This list aims to cover Electron.js security related topics.

<p align="center">
    <img src="https://github.com/doyensec/electronegativity/raw/master/docs/resources/img/electron-logo.png">
</p>

**Feel free to contribute** by opening a PR if you think something is missing to this list!

## Presentations

- ["Electronegativity - A Study of Electron Security", Luca Carettoni, BlackHat USA 2017](https://www.blackhat.com/docs/us-17/thursday/us-17-Carettoni-Electronegativity-A-Study-Of-Electron-Security.pdf) & [video](https://www.youtube.com/watch?v=oJWsBHlt0ZM)
- ["MarkDoom: How I Hacked Every Major IDE in 2 Weeks", Matt Austin, APPSEC Cali 2018](https://docs.google.com/presentation/d/1wQM4fhjCJ9r3DQ-c98XJFkrd83odM94FaJPqstTR68c) & [video](https://www.youtube.com/watch?v=a-YnG3Mx-Tg)
- ["Building a secure web browser in Electron", Yan @bcrypt, Electron Meetup 2/2018](https://www.youtube.com/watch?v=Qirdy1TP1Rw)
- ["Electron: Abusing the lack of context isolation", Masato Kinugawa, CureCon 2018](https://speakerdeck.com/masatokinugawa/electron-abusing-the-lack-of-context-isolation-curecon-en)
- ["Only An Electron Away From Code Execution", Silvia Väli, Hack.lu 2018](https://www.youtube.com/watch?v=kvi6XX71VXM)
- ["Preloading Insecurity In Your Electron", Luca Carettoni, BlackHat Asia 2019](https://doyensec.com/resources/Asia-19-Carettoni-Preloading-Insecurity-In-Your-Electron.pdf) & [video](https://www.youtube.com/watch?v=Hw6JShd8Jxw)
- ["app setAsDefaultRCE Client: Electron, scheme handlers and stealthy security patches", Juho Nurminen, ZeroNights 2019](https://2019.zeronights.ru/wp-content/themes/zeronights-2019/public/materials/1_ZN2019_Juho_Nurminen.pdf) and [video](https://www.youtube.com/watch?v=A9qJHqWYl_4)
- ["Full Steam Ahead: Remotely Executing Code in Modern Desktop Application Architectures", Thomas Shadwell, INFILTRATE 2019](https://vimeo.com/335206831)
- ["Democratizing Electron.js Security", Luca Carettoni, Covalence 2020 SF](https://doyensec.com/resources/Covalence-2020-Carettoni-DemocratizingElectronSecurity.pdf) & [video](https://www.youtube.com/watch?v=N2GGWz-Pkeg)
- ["Remote Code Execution on Electron Applications", PwnFunction](https://www.youtube.com/watch?v=jkJWA_CWrQs)
- ["Shifting left for Electron.js security", Ksenia Peguero, Midwinter Night's Con 2020](https://www.youtube.com/watch?v=Fiqj37HiyAY)
- ["How to harden your Electron app", Mitchell Cohen, NorthSec 2021](https://youtu.be/_P6qI4ahBVk?t=5111)
- ["Hacking ELECTRON: JavaScript Desktop Applications w/ 7aSecurity", John Hammond](https://www.youtube.com/watch?v=P8QvSjL8F9w)
- ["ElectroVolt - Pwning Popular Desktop apps while uncovering new attack surface on Electron", Mohan Sri Rama Krishna Max Garrett Aaditya Purani William Bowling, BlackHat USA 2022 and Nullcon Goa 2022](https://i.blackhat.com/USA-22/Thursday/US-22-Purani-ElectroVolt-Pwning-Popular-Desktop-Apps.pdf) & [video](https://www.youtube.com/watch?v=J0bZGugLoYk)

## Open-Source & Commercial Tools

- Electronegativity, a static code analysis tool to find vulnerabilities in Electron-based applications [code](https://github.com/doyensec/electronegativity) & [slides](https://doyensec.com/resources/Electronegativity_ArsenalBHUS2019.pdf)
- [Devtron](https://www.electronjs.org/blog/electron-1-0#devtron), an Electron DevTools extension
- [Fiddle](https://github.com/electron/fiddle), to quickly create and play with small Electron experiments across different Electron versions 
- [ElectroNG](https://get-electrong.com/) Premium SAST tool built after Electronegativity to help  automate  security reviews

[![electrong-banner-small](https://user-images.githubusercontent.com/6027823/195326803-56a1181c-2ae4-4ba5-81ea-cd8148c81bea.png)](https://get-electrong.com/)

## Papers

- ["Electron Security Checklist", Luca Carettoni, 2017](https://doyensec.com/resources/us-17-Carettoni-Electronegativity-A-Study-Of-Electron-Security-wp.pdf)
- ["Analysis of Electron-based Applications to Identify Xss Flaws Escalating to Code Execution in Open-source Applications", Silvia Väli, 2017](https://digikogu.taltech.ee/en/Download/01ec8ff7-fff8-4a83-86a4-4048178a3ed5)
- ["Pentest-Report Ethereum Mist", Cure53, 2017](https://cure53.de/pentest-report_mist.pdf)
- ["Pentest-Report Frame Electron App", Cure53, 2018](https://cure53.de/pentest-report_frame.pdf)
- ["An Analysis of the State of Electron Security in the Wild", Benjamin Altpeter, 2020](https://benjamin-altpeter.de/doc/thesis-electron.pdf)
- ["Electrolint and Security of Electron Applications", Ksenia Peguero, 2021](https://www.sciencedirect.com/science/article/pii/S2667295221000040)

## Vulnerabilities Write-Ups and Exploits

- ["Hacking Mattermost #2: Year of Node.js on the Desktop", Andreas Lindh](http://haxx.ml/post/145508617751/hacking-mattermost-2-year-of-nodejs-on-the?is_related_post=1)
- ["Modern Alchemy: Turning XSS into RCE", Doyensec Blog](https://blog.doyensec.com/2017/08/03/electron-framework-security.html)
- ["Subverting Electron Apps via Insecure Preload", Doyensec Blog](https://blog.doyensec.com/2019/04/03/subverting-electron-apps-via-insecure-preload.html)
- ["CVE-2018-15685 - Electron WebPreferences Remote Code Execution Finding", Matt Austin](https://www.contrastsecurity.com/security-influencers/cve-2018-15685), [PoC](https://github.com/matt-/CVE-2018-15685)
- ["Remote Code Execution in Rocket.Chat Desktop", Matt Austin](https://hackerone.com/reports/276031)
- ["Rocket.Chat Cross-Site Scripting leading to Remote Code Execution CVE-2020-15926", Pawel Wylecial](https://blog.redteam.pl/2020/08/rocket-chat-xss-rce-cve-2020-15926.html)
- ["Rocket.Chat Client-side Remote Code Execution", SSD Advisory](https://ssd-disclosure.com/ssd-advisory-rocket-chat-client-side-remote-code-execution/)
- ["Remote Code Execution in Wordpress Desktop", Matt Austin](https://hackerone.com/reports/301458)
- ["URL Spoof / Brave Shield Bypass", Matt Austin](https://hackerone.com/reports/255991)
- ["\[Simplenote for Windows\] Client RCE via External JavaScript Inclusion leveraging Electron", @ysx](https://hackerone.com/reports/291539)
- ["XSS in Steam react chat client", @zemnmez](https://hackerone.com/reports/409850)
- ["Security bug in Google Hangouts Chat desktop application – how to make Open Redirect great again", Michał Bentkowski](https://research.securitum.com/security-bug-in-google-hangouts-chat-desktop-application-how-to-make-open-redirect-great-again/)
- ["Critical Security Flaw Found in WhatsApp Desktop Platform Allowing Cybercriminals Read From The File System Access", Gal Weizman](https://www.perimeterx.com/tech-blog/2020/whatsapp-fs-read-vuln-disclosure/)
- ["signal-desktop HTML tag injection"](https://web.archive.org/web/20200427095259/https://ivan.barreraoro.com.ar/signal-desktop-html-tag-injection/) and ["signal-desktop HTML tag injection variant 2, Ivan A. Barrera Oro"](https://web.archive.org/web/20190517134857/https://ivan.barreraoro.com.ar/signal-desktop-html-tag-injection-variant-2/)
- ["Signature Validation Bypass Leading to RCE In Electron-Updater", Doyensec Blog](https://blog.doyensec.com/2020/02/24/electron-updater-update-signature-bypass.html)
- ["Electron Windows Protocol Handler MITM/RCE (bypass for CVE-2018-1000006 fix)", Doyensec Blog](https://blog.doyensec.com/2018/05/24/electron-win-protocol-handler-bug-bypass.html)
- ["Top 5 Day Two: Electron Boogaloo - A case for technodiversity",  Vincent Lee](https://www.thezdi.com/blog/2018/12/18/top-5-day-two-electron-boogaloo-a-case-for-technodiversity)
- ["Exploiting Electron RCE in Exodus wallet", Tomas Lažauninkas](https://hackernoon.com/exploiting-electron-rce-in-exodus-wallet-d9e6db13c374)
- ["Chaining Three Bugs to Get RCE in Microsoft AttackSurfaceAnalyzer", Parsia Hakimian](https://parsiya.net/blog/2019-06-18-chaining-three-bugs-to-get-rce-in-microsoft-attacksurfaceanalyzer/)
- ["Open Sesame: Escalating Open Redirect to RCE with Electron Code Review", Eugene Lim](https://spaceraccoon.dev/open-sesame-escalating-open-redirect-to-rce-with-electron-code-review)
- ["From Markdown to RCE in Atom", Lukas Reschke](https://statuscode.ch/2017/11/from-markdown-to-rce-in-atom)
- ["Visual Studio Code silently fixed a remote code execution vulnerability", CodeColorist](https://blog.chichou.me/2018/03/16/visual-studio-code-silently-fixed-a-remote-code-execution-vulnerability/)
- ["OVE-20210809-0001 Visual Studio Code .ipynb Jupyter Notebook XSS (Arbitrary File Read)", Justin Steven](https://github.com/justinsteven/advisories/blob/master/2021_vscode_ipynb_xss_arbitrary_file_read.md)
- ["Visual Studio Code Jupyter Notebook RCE ( CVE-2021-26437)", Doyensec Blog](https://blog.doyensec.com/2022/10/27/jupytervscode.html)
- ["Visual Studio Code - Remote Code Execution in Restricted Mode (CVE-2021-43908)", TheGrandPew and s1r1us](https://blog.electrovolt.io/posts/vscode-rce/)
- ["Remote Code Execution in Slack desktop apps + bonus", Oskars Vegeris](https://hackerone.com/reports/783877)
- ["Important, Spoofing - zero-click, wormable, cross-platform remote code execution in Microsoft Teams", Oskars Vegeris](https://github.com/oskarsve/ms-teams-rce)
- ["Cross-site scripting (XSS) in Microsoft Teams", Evan Grant](https://www.tenable.com/security/research/tra-2019-54)
- ["Dependency Confusion Vulnerability in Microsoft Teams", Matt Austin](https://www.contrastsecurity.com/security-influencers/contrast-labs-reveals-dependency-confusion-vulnerability-in-microsoft-teams)
- ["RCE in Jitsi Meet Electron prior to 2.3.0 due to insecure use of shell.openExternal() (CVE-2020-25019)", Benjamin Altpeter](https://benjamin-altpeter.de/jitsi-meet-electron-rce-shell-openexternal/)
- ["Insecure use of shell.openExternal() in Wire Desktop", Benjamin Altpeter](https://github.com/wireapp/wire-desktop/security/advisories/GHSA-5gpx-9976-ggpm)
- ["Jitsi Meet Electron – Arbitrary Client Remote Code Execution (CVE-2020-27162)", Robert Wessen](https://research.nccgroup.com/2020/10/23/technical-advisory-jitsi-meet-electron-arbitrary-client-remote-code-execution-cve-2020-27162/) and ["Jitsi Meet Electron – Limited Certificate Validation Bypass (CVE-2020-27161)", Robert Wessen](https://research.nccgroup.com/2020/10/23/technical-advisory-jitsi-meet-electron-limited-certificate-validation-bypass-cve-2020-27161/)
- ["Brave Arbitrary IPC Messages via Prototype Pollution in Function.prototype.call",  Masato Kinugawa](https://hackerone.com/reports/187542), ["via Prototype Pollution in Function.prototype.apply",  Masato Kinugawa](https://hackerone.com/reports/188086) and ["via Prototype Pollution in Array.prototype.push",  Masato Kinugawa](https://hackerone.com/reports/188561)
- ["Prototype Pollution Vulnerabilities in Electron Apps", @s1r1u5](https://github.com/msrkp/electron-research)
- ["Websites Can Run Arbitrary Code on Machines Running the 'PlayStation Now' Application", Parsia Hakimian](https://hackerone.com/reports/873614)
- ["Discord Desktop App RCE", Masato Kinugawa](https://mksben.l0.cm/2020/10/discord-desktop-rce.html)
- ["Discord Desktop - Remote Code Execution", s1r1us](https://blog.electrovolt.io/posts/discord-rce/)
- ["Vulnerability in Electron-based Application: Unintentionally Giving Malicious Code Room to Run", CertiK](https://certik.io/blog/technology/vulnerability-electron-based-application-malicious-code-execution)
- ["Joplin ElectronJS based Client: from XSS to RCE", Jaroslav Lobacevski](https://blog.devsecurity.eu/en/blog/joplin-electron-rce)
- ["Facebook Messenger Desktop App Arbitrary File Read", Renwa](https://medium.com/@renwa/facebook-messenger-desktop-app-arbitrary-file-read-db2374550f6d)
- ["RCE in Mattermost Desktop earlier than 4.2.0", Nathan Lowe](https://dev.to/nlowe/rce-in-mattermost-desktop-earlier-than-420-5aef)
- ["GitHub Desktop RCE (OSX)", André Baptista](https://pwning.re/2018/12/04/github-desktop-rce/)
- ["RCE in GitHub Desktop < 2.9.4", Vladimir Metnew](https://github.com/Metnew/write-ups/tree/main/rce-github-desktop-2.9.3)
- ["CVE-2020–16608", Sourov Ghosh](https://sghosh2402.medium.com/cve-2020-16608-8cdad9f4d9b4)
- ["HEY Desktop RCE Chain", Doyensec Team](https://doyensec.com/resources/Doyensec_Basecamp_HEY_PlatformTesting_Q32020_SAS.pdf)
- ["CVE-2018-1000136 - Electron nodeIntegration Bypass", Brendan Scarvell](https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/cve-2018-1000136-electron-nodeintegration-bypass)
- ["Remote Code Execution on Element Desktop Application using Node Integration in Sub Frames Bypass", s1r1us and TheGrandPew](https://blog.electrovolt.io/posts/element-rce/)
- ["CVE-2022-29247 - Disable Electron Context Isolation or enable Node Integration in SubFrames", s1r1us](https://hackerone.com/reports/1647287)

## Blog Posts and Articles

- ["Security, Native Capabilities, and Your Responsibility", Electron's Documentation](https://www.electronjs.org/docs/tutorial/security)
- ["Instrumenting Electron Apps for Security Testing", Doyensec Blog](https://blog.doyensec.com/2018/07/19/instrumenting-electron-app.html)
- ["Reasonably Secure Electron", Joe DeMesy](https://know.bishopfox.com/research/reasonably-secure-electron) & [code](https://github.com/moloch--/reasonably-secure-electron)
- ["As It Stands - Electron Security"](http://blog.scottlogic.com/2016/03/09/As-It-Stands-Electron-Security.html) and ["An update on Electron Security", Dean Kerr](http://blog.scottlogic.com/2016/06/01/An-update-on-Electron-Security.html)
- ["Exploiting Electron Applications using Debug Feature", Esecurity Lab](https://evren.ninja/blog/en/post/exploiting-electron-applications-/)
- ["Why Electron apps can’t store your secrets confidentially: \` — inspect\`option", Vladimir Metnew](https://medium.com/@metnew/why-electron-apps-cant-store-your-secrets-confidentially-inspect-option-a49950d6d51f)
- ["The App Sandbox", Charlie Hess](https://slack.engineering/the-app-sandbox/)
- ["Abusing Electron apps to bypass macOS' security controls", Wojciech Reguła](https://wojciechregula.blog/post/abusing-electron-apps-to-bypass-macos-security-controls/)
- ["The dangers of Electron's shell.openExternal() — many paths to remote code execution", Benjamin Altpeter](https://benjamin-altpeter.de/shell-openexternal-dangers/)
- ["1-click RCE in Electron Applications", Pavel Shabarkin](https://shabarkin.medium.com/1-click-rce-in-electron-applications-79b52e1fe8b8)

## Books

- ["Cross-Platform Desktop Applications Using Node, Electron, and NW.js", Paul B. Jensen](https://www.manning.com/books/cross-platform-desktop-applications)
- ["Electron in Action", Steve Kinney](https://www.manning.com/books/electron-in-action)


## Related lists

- [Awesome Node.js Security](https://github.com/lirantal/awesome-nodejs-security)
- [Awesome Electron](https://github.com/sindresorhus/awesome-electron)
