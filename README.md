# Awesome Frida with stars

A curated list of awesome projects, libraries, and tools powered by Frida.

## What is Frida?

Frida is [Greasemonkey](https://en.wikipedia.org/wiki/Greasemonkey) for native apps, or, put in more technical terms, it’s a dynamic code instrumentation toolkit. It lets you inject snippets of JavaScript into native apps that run on Windows, Mac, Linux, iOS and Android.

Frida is an open source software.

More info [here](http://www.frida.re/).

## Table of Contents

<!-- MarkdownTOC depth=4 -->

* [Libraries](#libraries)
* [Projects](#projects)
* [Talks & Papers](#talks-and-papers)
* [Powered by Frida](#frida-powered-by)
* [Videos](#videos)
* [Blog posts](#blogs)
* [Community](#community)

<!-- /MarkdownTOC -->

<a name="libraries" />

## Libraries

* [frida-android-hooks](https://github.com/antojoseph/frida-android-hooks) ⭐ 396 | 🐛 1 | 🌐 Python | 📅 2019-07-30 - Hook method calls in Android
* [frida-trace](https://github.com/nowsecure/frida-trace) ⭐ 237 | 🐛 20 | 🌐 JavaScript | 📅 2025-06-16 - Trace APIs declaratively
* [frida-compile](https://github.com/frida/frida-compile) ⭐ 228 | 🐛 36 | 🌐 JavaScript | 📅 2026-03-27 - Compile a Frida script comprised of one or more Node.js modules
* [FridaAndroidTracer](https://github.com/Piasy/FridaAndroidTracer) ⭐ 136 | 🐛 0 | 🌐 Java | 📅 2018-04-14 - A runnable jar that generate Javascript hook script to hook Android classes
* [frida-uikit](https://github.com/nowsecure/frida-uikit) ⭐ 61 | 🐛 4 | 🌐 JavaScript | 📅 2025-06-16 - Inspect and manipulate UIKit-based GUIs
* [frida-screenshot](https://github.com/nowsecure/frida-screenshot) ⭐ 51 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-18 - Grab (iOS) screenshots
* [frida-uiwebview](https://github.com/nowsecure/frida-uiwebview) ⭐ 50 | 🐛 0 | 🌐 JavaScript | 📅 2025-06-16 - Inspect and manipulate UIWebView-hosted GUIs
* [frida-fs](https://github.com/nowsecure/frida-fs) ⭐ 50 | 🐛 7 | 🌐 TypeScript | 📅 2026-03-25 - Create a stream from a filesystem resource.
* [frida-push](https://github.com/AndroidTamer/frida-push) ⭐ 42 | 🐛 12 | 🌐 Python | 📅 2022-12-26 - Automatically `adb push` the correct frida-server matching your current frida installation.
* [frida-contrib](https://github.com/dweinstein/node-frida-contrib) ⭐ 24 | 🐛 2 | 🌐 JavaScript | 📅 2016-09-01 - Frida utility-belt
* [frida-remote-stream](https://github.com/nowsecure/frida-remote-stream) ⭐ 22 | 🐛 1 | 🌐 TypeScript | 📅 2025-06-16 - Create an outbound stream over a message transport.
* [frida-panic](https://github.com/nowsecure/frida-panic) ⭐ 18 | 🐛 3 | 🌐 JavaScript | 📅 2019-08-19 - Easy crash-reporting for Frida-based applications
* [frida-memory-stream](https://github.com/nowsecure/frida-memory-stream) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2024-01-22 - Create a stream from one or more memory regions.
* [frida-load](https://github.com/frida/frida-load) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2017-08-09 - Load a Frida script comprised of one or more Node.js modules (Deprecated, use [frida-compile](https://github.com/frida/frida-compile) ⭐ 228 | 🐛 36 | 🌐 JavaScript | 📅 2026-03-27)
* [frida-definitions-generator](https://git.sr.ht/~yotam/frida-definitions-generator) - Generate TypeScript definitions for a given APK file or unpacked apk directory.

<a name="projects" />

## Projects

* [iddoeldor/frida-snippets](https://github.com/iddoeldor/frida-snippets) ⭐ 2,533 | 🐛 5 | 🌐 JavaScript | 📅 2024-11-29 - another useful frida snippets repository
* [0xdea/frida-scripts](https://github.com/0xdea/frida-scripts) ⭐ 1,653 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-02 - instrumentation scripts to facilitate reverse engineering of android and iOS Apps.
* [r2frida](https://github.com/nowsecure/r2frida) ⭐ 1,434 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-24 - static and dynamic analysis synergy
* [frida-cycript](https://github.com/nowsecure/frida-cycript) ⭐ 396 | 🐛 13 | 🌐 C | 📅 2023-03-04 - Fork of cycript with new runtime called [Mjølner](https://github.com/nowsecure/mjolner) ⭐ 24 | 🐛 2 | 🌐 JavaScript | 📅 2021-07-07 powered by Frida.
* [Arida](https://github.com/lateautumn4lin/arida) ⭐ 247 | 🐛 3 | 🌐 Python | 📅 2020-11-02 - A Frida-RPC tool based on FastAPI, Help users quickly realize interface exposure.
* [as0ler/frida-scripts](https://github.com/as0ler/frida-scripts) ⭐ 244 | 🐛 0 | 🌐 JavaScript | 📅 2021-12-21 - Repository including some useful frida script for iOS Reversing
* [XposedFridaBridge](https://github.com/monkeylord/XposedFridaBridge) ⭐ 211 | 🐛 3 | 🌐 JavaScript | 📅 2021-09-24 - A frida script implement XposedBridge & load xposed modules, without installing xposed framwork.
* [ios-inject-custom](https://github.com/oleavr/ios-inject-custom) ⭐ 170 | 🐛 1 | 🌐 C | 📅 2020-05-26 - use Frida for standalone injection of a custom payload for iOS.
* [poxyran/misc](https://github.com/poxyran/misc) ⭐ 157 | 🐛 0 | 🌐 Python | 📅 2019-06-27 - Misc Frida scripts [read-process-memory.py](https://github.com/poxyran/misc/blob/master/frida-read-process-memory.py) ⭐ 157 | 🐛 0 | 🌐 Python | 📅 2019-06-27, [write-process-memory.py](https://github.com/poxyran/misc/blob/master/frida-write-process-memory.py) ⭐ 157 | 🐛 0 | 🌐 Python | 📅 2019-06-27, [frida-heap-trace](https://github.com/poxyran/misc/blob/master/frida-heap-trace.py) ⭐ 157 | 🐛 0 | 🌐 Python | 📅 2019-06-27,
* [IDA Pro plugin](https://github.com/techbliss/Frida_For_Ida_Pro) ⭐ 127 | 🐛 1 | 🌐 Python | 📅 2015-04-05 - IDA Pro plugin
* [davuxcom/frida-scripts](https://github.com/davuxcom/frida-scripts) ⭐ 102 | 🐛 2 | 🌐 JavaScript | 📅 2019-07-29 - Repository including scripts for COM, .NET and WinRT for Windows
* [RoboDroid](https://github.com/cybersecsi/robodroid) ⭐ 91 | 🐛 4 | 🌐 Python | 📅 2024-01-15 - A tool for manage and deploy Android machines with pre-defined behaviors (made with Frida) for Cyber Range environments.
* [easy-frida](https://github.com/tacesrever/easy-frida) ⭐ 84 | 🐛 0 | 🌐 C++ | 📅 2025-07-11 - A tool for easily develop frida agent script/module when reversing, including some useful frida scripts.
* [rekit](https://github.com/b-erdem/rekit) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-05-01 - Reverse engineering toolkit for mobile APIs. Captures Android HTTP traffic via Frida hooks (OkHttp, Dio, URLConnection, WebView) above TLS without proxy setup, outputs HAR files, and includes tools for endpoint scanning, TLS fingerprint testing, and API client generation.
* [roxanagogonea/frida-scripts](https://gitlab.com/roxanagogonea/frida-scripts) - Repository including some useful frida scripts for Android

<a name="talks-and-papers" />

## Talks & Papers

* [r2con 2016 - r2frida](http://rada.re/con/) ([PDF](https://github.com/radareorg/r2con/raw/master/2016/talks/08-r2frida/r2frida.pdf) ⭐ 212 | 🐛 1 | 🌐 Makefile | 📅 2025-10-26 · [Recording](https://www.youtube.com/watch?v=ivCucqeVeZI))
* [NLUUG 2015](https://www.nluug.nl/activiteiten/events/nj15/index.html):
  [Frida: Putting the open back into closed software](https://www.nluug.nl/activiteiten/events/nj15/abstracts/ab08.html)
  ([Slides](http://slides.com/oleavr/nluug-2015-frida-putting-the-open-back-into-closed-software)
  · [Demos](https://github.com/frida/frida-presentations/tree/master/NLUUG2015) ⭐ 102 | 🐛 0 | 🌐 JavaScript | 📅 2019-08-18
  · [Recording](https://youtu.be/3lo1Y2oKkE4))
* [ZeroNights 2015](http://2015.zeronights.org/):
  [Cross-platform reversing with Frida](http://2015.zeronights.org/workshops.html)
  ([PDF](zeronights-2015-cross-platform-reversing-with-frida.pdf)
  · [Demos](https://github.com/frida/frida-presentations/tree/master/ZeroNights2015) ⭐ 102 | 🐛 0 | 🌐 JavaScript | 📅 2019-08-18)
* [OSDC 2015](http://act.osdc.no/osdc2015no/):
  [Putting the open back into closed software](http://act.osdc.no/osdc2015no/talk/6165)
  ([PDF](osdc-2015-putting-the-open-back-into-closed-software.pdf) · [Recording](https://youtu.be/tmpjftTHzH8))
* [OSDC 2015](http://act.osdc.no/osdc2015no/):
  [The engineering behind the reverse engineering](http://act.osdc.no/osdc2015no/talk/6195)
  ([PDF](osdc-2015-the-engineering-behind-the-reverse-engineering.pdf) · [Recording](https://youtu.be/uc1mbN9EJKQ))
* [RMLL 2017](https://2017.rmll.info/) Unlocking secrets of proprietary software (@oleavr) ([slides](https://slides.com/oleavr/frida-rmll-2017#/) · [Recording](https://rmll.ubicast.tv/videos/frida_03038/))

<a name="frida-powered-by" />

## Powered by Frida

* [objection](https://github.com/sensepost/objection) ⭐ 9,346 | 🐛 55 | 🌐 Python | 📅 2026-07-23 - Runtime Mobile Exploration for iOS and Android
* [Runtime Mobile Security (RMS)](https://github.com/m0bilesecurity/RMS-Runtime-Mobile-Security) ⭐ 3,075 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-03 - A powerful web interface that helps you to manipulate Android and iOS Apps at Runtime
* [brida](https://github.com/federicodotta/Brida) ⭐ 1,889 | 🐛 11 | 🌐 Java | 📅 2025-10-30 - Bridge between Burp Suite and Frida
* [passionfruit](https://github.com/chaitin/passionfruit) ⚠️ Archived - iOS App Analyzer with Web UI
* [Appmon](https://github.com/dpnishant/appmon) ⚠️ Archived - Runtime Security Testing Framework for iOS, Mac OS X and Android Apps
* [bagbak](https://github.com/ChiChou/bagbak) ⭐ 1,494 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-24 - Decrypt apps from AppStore on jailbroken devices. Supports decrypting app extensions.
* [House](https://github.com/nccgroup/house) ⭐ 1,463 | 🐛 16 | 🌐 JavaScript | 📅 2021-06-03 - A runtime mobile application analysis toolkit with a Web GUI, powered by Frida
* [r2frida](https://github.com/nowsecure/r2frida) ⭐ 1,434 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-24 [memory search](https://www.nowsecure.com/blog/2017/03/14/spearing-data-mobile-memory-building-better-r2frida-memory-search/)
* [Dwarf](https://github.com/igio90/Dwarf) ⭐ 1,317 | 🐛 5 | 🌐 Python | 📅 2024-05-16 - A debugger built on top of PyQt5 and frida
* [Dexcalibur](https://github.com/FrenchYeti/dexcalibur) ⭐ 1,168 | 🐛 36 | 🌐 TypeScript | 📅 2026-08-11 - A dynamic binary instrumentation tool designed for Android apps and powered by Frida
* [google/ssl\_logger](https://github.com/google/ssl_logger) ⚠️ Archived - Decrypts and logs a process's SSL traffic.
* [Fridump](https://github.com/Nightbringer21/fridump) ⭐ 858 | 🐛 27 | 🌐 Python | 📅 2024-08-07 - A universal memory dumper using Frida
* [CryptoShark](https://github.com/frida/cryptoshark) ⭐ 601 | 🐛 13 | 🌐 C++ | 📅 2022-07-20 - Self-optimizing cross-platform code tracer based on dynamic recompilation
* [friTap](https://github.com/fkie-cad/friTap) ⭐ 536 | 🐛 8 | 🌐 Python | 📅 2026-08-10 - Decrypts and logs a process's SSL/TLS traffic on all major platforms. Beside this it intercepts the generation of encryption keys used by SSL/TLS and logs them as a SSLKEYLOGFILE.
* [google/tcp\_killer](https://github.com/google/tcp_killer) ⚠️ Archived - Shuts down a TCP connection based using output from a `netstat` cmd.
* [r2frida-wiki](https://github.com/enovella/r2frida-wiki) ⭐ 202 | 🐛 2 | 📅 2020-12-11 - Unofficial wiki that provides practical examples on how to use r2frida
* [diff-gui](https://github.com/antojoseph/diff-gui) ⭐ 182 | 🐛 2 | 🌐 JavaScript | 📅 2016-11-03 - Web GUI for instrumenting Android
* [CatFrida](https://github.com/neil-wu/CatFrida) ⭐ 117 | 🐛 1 | 🌐 C | 📅 2021-01-20 - A macOS app for inspecting a running iOS app. Building with frida-swift, CatFrida provide an awesome easy way to dive into an app.
* [frida-extract](https://github.com/OALabs/frida-extract) ⭐ 114 | 🐛 1 | 🌐 JavaScript | 📅 2017-03-02 - Automatically extract and reconstruct a PE file that has been injected using the RunPE method
* [PAPIMonitor](https://github.com/Dado1513/PAPIMonitor) ⭐ 87 | 🐛 3 | 🌐 JavaScript | 📅 2024-07-04 - **P**ython **API** **Monitor** for Android apps is a tool, powered by Frida, to monitor user-selected APIs during app execution.
* [Aurora](https://github.com/frida/aurora) ⭐ 29 | 🐛 1 | 🌐 JavaScript | 📅 2015-05-10 - Web app built on top of Frida
* [CloudSpy](https://github.com/frida/cloudspy) ⭐ 22 | 🐛 0 | 🌐 JavaScript | 📅 2015-04-11 - Web app built on top of Frida
* ~~[Lobotomy](https://github.com/LifeForm-Labs/lobotomy)~~[Lobotomy Fork](https://github.com/AndroidSecurityTools/lobotomy) - Android Reverse Engineering Framework & Toolkit

<a name="videos" />

## Videos

* [Frida vs Spotify](https://www.youtube.com/watch?v=dvOdwHpQycw) - Spotify RE
* [CryptoShark](https://www.youtube.com/watch?v=hzDsxtcRavY) - a self-optimizing cross-platform code tracer based on dynamic recompilation, powered by Frida and Capstone
* [Frida Memory Hacking - Angry Birds](https://www.youtube.com/watch?v=nk3rUn2ip0g) - Frida having fun with Angry Birds running on an iPhone
* [Frida Memory Hacking - Windows Live Messenger](https://www.youtube.com/watch?v=0Blc0T-Z-ys) - Frida having fun with Windows Live Messenger
* [Frida Intro @ NowSecure](https://www.youtube.com/watch?v=4Ag-2LZQM8g) - Frida introduction by Ole
* ~~[Lobotomy - Frida Demo](https://asciinema.org/a/24269) - This demo is leveraging the Frida toolkit to instrument a target app's Activity calls.~~
* [Install SSL CA to device via ManagedConfiguration tracing](https://www.youtube.com/watch?v=qfOm5b9MZtk)

<a name="blogs" />

## Blog posts

* [Build a debugger in 5 minutes](https://medium.com/@oleavr/build-a-debugger-in-5-minutes-1-5-51dce98c3544#.mn48pvhok)
* [Reverse Engineering with Javascript](https://www.nowsecure.com/blog/2015/08/06/reverse-engineering-with-javascript/)
* [iOS 9 Reverse Engineering with Javascript](https://www.nowsecure.com/blog/2015/11/16/ios-9-reverse-engineering-with-javascript/)
* [iOS Instrumentation without Jailbreak](https://www.nowsecure.com/blog/2015/11/23/ios-instrumentation-without-jailbreak/)
* [Introduction to Fridump](http://pentestcorner.com/introduction-to-fridump/) - Fridump is an open source memory dumper tool
* [Hacking Android apps with Frida part1](https://www.codemetrix.net/hacking-android-apps-with-frida-1/), [part2/crackme](https://www.codemetrix.net/hacking-android-apps-with-frida-2/), [part3](https://www.codemetrix.net/hacking-android-apps-with-frida-3/)
* [OWASP iOS crackme tutorial: Solved with Frida](https://www.nowsecure.com/blog/2017/04/27/owasp-ios-crackme-tutorial-frida/)
* Detecting Frida [poxyran](https://crackinglandia.wordpress.com/2015/11/10/anti-instrumentation-techniques-i-know-youre-there-frida/), [Bernhard Mueller](http://www.vantagepoint.sg/blog/90-the-jiu-jitsu-of-detecting-frida)
* [Maddie Stone, Google project Zero - Blackhat 2020 - Reversing the Root. Identifying the Exploited Vulnerability in 0-days Used In-The-Wild](https://i.blackhat.com/USA-20/Wednesday/us-20-Stone-Reversing-The-Root-Identifying-The-Exploited-Vulnerability-In-0-Days-Used-In-The-Wild.pdf)
* [Natalie Silvanovich, Google Project Zero - January 2022 - Zooming in on Zero-click Exploits](https://googleprojectzero.blogspot.com/2022/01/zooming-in-on-zero-click-exploits.html)
* [BlackBerry - April 2021 - Malware analysis with dynamic binary instrumentation frameworks](https://blogs.blackberry.com/en/2021/04/malware-analysis-with-dynamic-binary-instrumentation-frameworks)

<a name="community" />

## Community

* [Stack Overflow](http://stackoverflow.com/questions/tagged/frida)
* [@fridaotre on Twitter](https://twitter.com/fridadotre)
* [@oleavr on Twitter](https://twitter.com/oleavr)
* [Reddit](https://www.reddit.com/r/frida)
* [Frida CodeShare](https://codeshare.frida.re/) - Share frida snippets and recipes with others.

<a name="contributions" />

## Contributions

Your contributions are always welcome!

If you want to contribute to this list (please do), send me a pull request or contact me [@insitusec](https://twitter.com/insitusec)

Also, if you notice that a listing should be deprecated or replaced:

* Repository's owner explicitly say that "this library is not maintained".
* Not committed for long time (2\~3 years).

More info on the [guidelines](https://github.com/dweinstein/awesome-frida/blob/master/CONTRIBUTING.md) ⭐ 3,516 | 🐛 5 | 📅 2026-04-10

<a name="credits" />

## Credits

* This awesome list was originally based on [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) ⭐ 17,550 | 🐛 34 | 📅 2026-02-08

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-26._
