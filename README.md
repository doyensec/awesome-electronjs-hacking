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
- ["app setAsDefaultRCE Client: Electron, scheme handlers and stealthy security patches", Juho Nurminen, ZeroNights 2019](https://zeronights.ru/wp-content/themes/zeronights-2019/public/materials/1_ZN2019_Juho_Nurminen.pdf) and [video](https://www.youtube.com/watch?v=A9qJHqWYl_4)
- ["Full Steam Ahead: Remotely Executing Code in Modern Desktop Application Architectures", Thomas Shadwell, INFILTRATE 2019](https://vimeo.com/335206831)
- ["Democratizing Electron.js Security", Luca Carettoni, Covalence 2020 SF](https://doyensec.com/resources/Covalence-2020-Carettoni-DemocratizingElectronSecurity.pdf) & [video](https://www.youtube.com/watch?v=N2GGWz-Pkeg)
- ["Remote Code Execution on Electron Applications", PwnFunction](https://www.youtube.com/watch?v=jkJWA_CWrQs)

## Open-Source Tools

- Electronegativity, a static code analysis tool to find vulnerabilities in Electron-based applications [code](https://github.com/doyensec/electronegativity) & [slides](https://doyensec.com/resources/Electronegativity_ArsenalBHUS2019.pdf)
- [Devtron](https://www.electronjs.org/devtron), an Electron DevTools extension
- [Fiddle](https://github.com/electron/fiddle), to quickly create and play with small Electron experiments across different Electron versions 

## Papers

- ["Electron Security Checklist", Luca Carettoni, 2017](https://doyensec.com/resources/us-17-Carettoni-Electronegativity-A-Study-Of-Electron-Security-wp.pdf)
- ["Analysis of Electron-based Applications to Identify Xss Flaws Escalating to Code Execution in Open-source Applications", Silvia Väli, 2017](https://digikogu.taltech.ee/en/Download/01ec8ff7-fff8-4a83-86a4-4048178a3ed5)

## Vulnerabilities Write-Ups and Exploits

- ["Rocket.Chat Cross-Site Scripting leading to Remote Code Execution CVE-2020-15926", Pawel Wylecial](https://blog.redteam.pl/2020/08/rocket-chat-xss-rce-cve-2020-15926.html)
- ["Hacking Mattermost #2: Year of Node.js on the Desktop", Andreas Lindh](http://haxx.ml/post/145508617751/hacking-mattermost-2-year-of-nodejs-on-the?is_related_post=1)
- ["Subverting Electron Apps via Insecure Preload", Doyensec Blog](https://blog.doyensec.com/2019/04/03/subverting-electron-apps-via-insecure-preload.html)
- ["CVE-2018-15685 - Electron WebPreferences Remote Code Execution Finding", Matt Austin](https://www.contrastsecurity.com/security-influencers/cve-2018-15685), [PoC](https://github.com/matt-/CVE-2018-15685)
- ["Remote Code Execution in Rocket.Chat Desktop", Matt Austin](https://hackerone.com/reports/276031)
- ["Remote Code Execution in Wordpress Desktop", Matt Austin](https://hackerone.com/reports/301458)
- ["URL Spoof / Brave Shield Bypass", Matt Austin](https://hackerone.com/reports/255991)
- ["\[Simplenote for Windows\] Client RCE via External JavaScript Inclusion leveraging Electron", @ysx](https://hackerone.com/reports/291539)
- ["XSS in Steam react chat client", @zemnmez](https://hackerone.com/reports/409850)
- ["Security bug in Google Hangouts Chat desktop application – how to make Open Redirect great again", Michał Bentkowski](https://research.securitum.com/security-bug-in-google-hangouts-chat-desktop-application-how-to-make-open-redirect-great-again/)
- ["Critical Security Flaw Found in WhatsApp Desktop Platform Allowing Cybercriminals Read From The File System Access", Gal Weizman](https://www.perimeterx.com/tech-blog/2020/whatsapp-fs-read-vuln-disclosure/)
- ["signal-desktop HTML tag injection"](https://ivan.barreraoro.com.ar/signal-desktop-html-tag-injection/) and ["signal-desktop HTML tag injection variant 2"](https://ivan.barreraoro.com.ar/signal-desktop-html-tag-injection-variant-2/), Ivan A. Barrera Oro
- ["Chromium vulnerability affecting Mist Browser Beta", @evertonfraga, Mist Team](https://blog.ethereum.org/2017/12/15/security-alert-chromium-vulnerability-affecting-mist-browser-beta/)
- ["Exploiting Electron RCE in Exodus wallet", Tomas Lažauninkas](https://hackernoon.com/exploiting-electron-rce-in-exodus-wallet-d9e6db13c374)
- ["Signature Validation Bypass Leading to RCE In Electron-Updater", Doyensec Blog](https://blog.doyensec.com/2020/02/24/electron-updater-update-signature-bypass.html)
- ["Electron Windows Protocol Handler MITM/RCE (bypass for CVE-2018-1000006 fix)", Doyensec Blog](https://blog.doyensec.com/2018/05/24/electron-win-protocol-handler-bug-bypass.html)
- ["Modern Alchemy: Turning XSS into RCE", Doyensec Blog](https://blog.doyensec.com/2017/08/03/electron-framework-security.html)
- ["Chaining Three Bugs to Get RCE in Microsoft AttackSurfaceAnalyzer", Parsia Hakimian](https://parsiya.net/blog/2019-06-18-chaining-three-bugs-to-get-rce-in-microsoft-attacksurfaceanalyzer/)
- ["Open Sesame: Escalating Open Redirect to RCE with Electron Code Review", Eugene Lim](https://spaceraccoon.dev/open-sesame-escalating-open-redirect-to-rce-with-electron-code-review)
- ["From Markdown to RCE in Atom", Lukas Reschke](https://statuscode.ch/2017/11/from-markdown-to-rce-in-atom)
- ["Visual Studio Code silently fixed a remote code execution vulnerability", CodeColorist](https://blog.chichou.me/2018/03/16/visual-studio-code-silently-fixed-a-remote-code-execution-vulnerability/)
- ["Remote Code Execution in Slack desktop apps + bonus", @oskars](https://hackerone.com/reports/783877)

## Blog Posts and Articles

- ["Security, Native Capabilities, and Your Responsibility", Electron's Documentation](https://www.electronjs.org/docs/tutorial/security)
- ["Instrumenting Electron Apps for Security Testing", Doyensec Blog](https://blog.doyensec.com/2018/07/19/instrumenting-electron-app.html)
- ["Reasonably Secure Electron", Joe DeMesy](https://know.bishopfox.com/research/reasonably-secure-electron) & [code](https://github.com/moloch--/reasonably-secure-electron)
- ["Top 5 Day Two: Electron Boogaloo - A case for technodiversity",  Vincent Lee](https://www.thezdi.com/blog/2018/12/18/top-5-day-two-electron-boogaloo-a-case-for-technodiversity)
- ["As It Stands - Electron Security"](http://blog.scottlogic.com/2016/03/09/As-It-Stands-Electron-Security.html) and ["An update on Electron Security"](http://blog.scottlogic.com/2016/06/01/An-update-on-Electron-Security.html) by Dean Kerr
- ["Exploiting Electron Applications using Debug Feature", Esecurity Lab](https://evren.ninja/en/post/exploiting-electron-applications-/)
- ["Why Electron apps can’t store your secrets confidentially: \` — inspect\`option", Vladimir Metnew](https://medium.com/@metnew/why-electron-apps-cant-store-your-secrets-confidentially-inspect-option-a49950d6d51f)
- ["Abusing Electron apps to bypass macOS' security controls", Wojciech Reguła](https://wojciechregula.blog/post/abusing-electron-apps-to-bypass-macos-security-controls/)

## Books

- ["Cross-Platform Desktop Applications Using Node, Electron, and NW.js", Paul B. Jensen](https://www.manning.com/books/cross-platform-desktop-applications)
- ["Electron in Action", Steve Kinney](https://www.manning.com/books/electron-in-action)

## Related lists

- [Awesome Node.js Security](https://github.com/lirantal/awesome-nodejs-security)
- [Awesome Electron](https://github.com/sindresorhus/awesome-electron)
