# travis-ci-shell

*This project has been created only for educational purposes.*

## Story

It may happen that you need **urgent access** to the **Bash** shell even if you're working on a **Windows** computer. Imagine that you don't have the SSH private key to your host or any AWS credentials to spawn a micro instance. Why don't you use the **Travis CI** building host using **only browser**?

## Features

 * support for **multiple programming languages** and **databases** (see: [Minimal and Generic](https://docs.travis-ci.com/user/languages/minimal-and-generic/)): go, jvm, php, ruby, etc.
 * **only browser** required (thanks to [GoTTY](github.com/yudai/gotty))
 * shell **time limit** is set according to the Travis CI pricing plan (**free plan** - currently **50 min**)
 * support for **HTTPS tunnel** (thanks to [ngrok](https://ngrok.com/))

## Getting started

1. Fork the repository.

2. Configure Travis CI to trigger builds.

3. Trigger new manual build. It will spawn a new shell.

4. Watch build output and follow the tunnel URL, e.g. https://4f5575e5.ngrok.io

5. Merry Xmas!

## Screenshots

Trigger manual build...

<img src="https://github.com/mtojek/travis-ci-shell/blob/master/screenshots/scr-1.png" width="640px" />

Watch for the tunnel URL...

<img src="https://github.com/mtojek/travis-ci-shell/blob/master/screenshots/scr-2.png" width="640px" />

Open terminal within your browser!

<img src="https://github.com/mtojek/travis-ci-shell/blob/master/screenshots/scr-3.png" width="640px" />


