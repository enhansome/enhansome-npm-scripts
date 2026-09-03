<!--lint ignore awesome-heading-->

# Awesome npm Scripts with stars

[<img src="npm-logo.png" align="right" width="150">](https://www.npmjs.com)

> Everything awesome for using npm as a build tool.

You might also like [awesome-npm](https://github.com/sindresorhus/awesome-npm) ⭐ 4,737 | 🐛 1 | 📅 2026-04-20.

**Notice: I'm currently too busy to actively expand this list; therefore, I've decided to make this an [OPEN Open Source Project](http://openopensource.github.io/). Individuals making significant and valuable contributions are given commit-access to the project to contribute as they see fit.**

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->

<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

* [Articles](#articles)
* [Videos/Talks](#videostalks)
* [Task Runners](#task-runners)
* [File Watchers](#file-watchers)
* [Dev Servers](#dev-servers)
* [Cross-platform Utilities](#cross-platform-utilities)
  * [Utility Packs](#utility-packs)
* [Other Utilities](#other-utilities)
* [Miscellaneous](#miscellaneous)
* [Cross-platform Shell Reference](#cross-platform-shell-reference)
* [`npm run` Reference](#npm-run-reference)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Articles

* [Why we should stop using Grunt & Gulp](https://www.keithcirkel.co.uk/why-we-should-stop-using-grunt/) - Blog post by Keith Cirkel.
* [How to Use npm as a Build Tool](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/) - Sequel to »Why we should stop using Grunt & Gulp«.
* [Why I Left Gulp and Grunt for npm Scripts](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8) -  Article by Cory House.
* [Helpers and tips for npm run scripts](http://michael-kuehnel.de/tooling/2018/03/22/helpers-and-tips-for-npm-run-scripts.html) - Blog post by Michael Kühnel covering advanced topics.
* [Running cross-platform tasks via npm package scripts](https://exploringjs.com/nodejs-shell-scripting/ch_package-scripts.html) - The most comprehensive guide to using npm Scripts by Dr. Axel Rauschmayer.

## Videos/Talks

* [Advanced front-end automation with npm scripts](https://www.youtube.com/watch?v=0RYETb9YVrk) - Talk at Nordic.js 2015 by Kate Hudson.
* [How to create a build system with npm scripts](http://www.penta-code.com/how-to-create-a-build-system-with-npm-scripts/) - Video tutorial series on setting up a front-end build system.

## Task Runners

Tools for running multiple commands or npm scripts in parallel or sequentially.

* [npm-run-all2](https://github.com/bcomnes/npm-run-all2) ⭐ 440 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-31 - Fully featured task runner.
* [redrun](https://github.com/coderaiser/redrun) ⭐ 127 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-20 - Expand scripts from package.json to improve execution speed.
* [script-runner](https://github.com/paulpflug/script-runner) ⭐ 27 | 🐛 0 | 🌐 CoffeeScript | 📅 2018-08-13 - Simple task runner with a terse syntax.

## File Watchers

Tools to watch your source files and run a build command whenever any of the files change.

* [watch](https://github.com/mikeal/watch) ⭐ 1,280 | 🐛 59 | 🌐 JavaScript | 📅 2023-01-22 - `watch <command> <directory>`.
* [onchange](https://github.com/Qard/onchange) ⭐ 826 | 🐛 5 | 🌐 TypeScript | 📅 2026-06-18 - `onchange <glob> -- <command>`.

## Dev Servers

* [http-server](https://github.com/indexzero/http-server) ⭐ 14,234 | 🐛 108 | 🌐 JavaScript | 📅 2026-04-15 - Simple zero-configuration command-line http server.
* [live-server](https://github.com/tapio/live-server) ⭐ 4,564 | 🐛 213 | 🌐 JavaScript | 📅 2024-04-28 - Simple development http server with live reload capability.

## Cross-platform Utilities

Utilities to perform common command-line tasks without worrying about cross-platform compatibility.

* [cross-env](https://github.com/kentcdodds/cross-env) ⚠️ Archived - Set environment variables for scripts, unix-style.
* [rimraf](https://github.com/isaacs/rimraf) ⭐ 5,852 | 🐛 10 | 🌐 TypeScript | 📅 2026-05-15 - Delete files or directories; like `rm -rf`.
* [copyfiles](https://github.com/calvinmetcalf/copyfiles) ⭐ 421 | 🐛 56 | 🌐 JavaScript | 📅 2024-07-11 - Copy a list of files into a directory.
* [cpy-cli](https://github.com/sindresorhus/cpy-cli) ⭐ 360 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-05 - File/directory copying/renaming.
* [del-cli](https://github.com/sindresorhus/del-cli) ⭐ 332 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-18 - Safer file and folder deletion.
* [cpr](https://github.com/davglass/cpr) ⭐ 82 | 🐛 19 | 🌐 JavaScript | 📅 2021-05-26 - `cp -r` for Node.js.
* [clear-cli](https://github.com/sindresorhus/clear-cli) ⭐ 46 | 🐛 0 | 🌐 JavaScript | 📅 2021-10-13 - Clear the terminal.
* [cross-os](https://github.com/milewski/cross-os) ⭐ 45 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-09 - Run platform-specific npm scripts.
* [sync-files](https://github.com/byteclubfr/node-sync-files) ⭐ 44 | 🐛 10 | 🌐 JavaScript | 📅 2018-10-17 - `rsync`-like directory syncing with watch mode.
* [ntee](https://github.com/stefanmaric/ntee) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2019-05-25 - Utility that reads from standard input and writes to standard output and files; like Unix `tee`.
* [echo-cli](https://github.com/iamakulov/echo-cli) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2021-12-01 - Cross-platform `echo` with JS escape sequence support.
* [mkdirp](https://github.com/substack/node-mkdirp) - Create a directory, creating parent directories if needed; like `mkdir -p`.
* [catw](https://github.com/substack/catw) - Print a file to stdout, with optional watch mode; sorta like Unix `cat`.

### Utility Packs

* [shx](https://github.com/shelljs/shx) ⭐ 1,873 | 🐛 21 | 🌐 JavaScript | 📅 2026-06-08 - Collection of common Unix utilities implemented in Node.js; example usage: `shx rm somefile`.

## Other Utilities

* [opn-cli](https://github.com/sindresorhus/opn-cli) ⭐ 449 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-25 - Open websites, files, executables, etc. with the user's preferred application.
* [gzip-size-cli](https://github.com/sindresorhus/gzip-size-cli) ⭐ 193 | 🐛 0 | 🌐 JavaScript | 📅 2021-11-23 - Get the gzipped size of a file or stdin.
* [hashmark](https://github.com/keithamus/hashmark) ⭐ 190 | 🐛 8 | 🌐 JavaScript | 📅 2020-05-24 -  Take contents of a file and output as new file with a hash in the name.
* [cli-error-notifier](https://github.com/micromata/cli-error-notifier) ⭐ 72 | 🐛 10 | 🌐 JavaScript | 📅 2023-07-19 - Send native desktop notifications when npm scripts fail.
* [headr](https://github.com/heldr/headr) ⭐ 4 | 🐛 3 | 🌐 JavaScript | 📅 2016-08-24 - Add header / banner info to a file.
* [Bower files CLI](https://github.com/thompsonemerson/bower-files-cli) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-11 - Get main bower files on the command line.

## Miscellaneous

* [ntl](https://github.com/ruyadorno/ntl) ⭐ 964 | 🐛 26 | 🌐 JavaScript | 📅 2024-05-23 - Interactive cli menu to list and run npm scripts.
* [Forrest](https://github.com/stefanjudis/forrest) ⭐ 339 | 🐛 11 | 🌐 Vue | 📅 2019-01-31 - npm scripts desktop client.
* [run-npm](https://github.com/timoxley/npm-run) ⭐ 187 | 🐛 6 | 🌐 JavaScript | 📅 2018-11-14 - Run locally-installed node module executables. Useful for debugging npm scripts.
* [npm-quick-run](https://github.com/bahmutov/npm-quick-run) ⭐ 148 | 🐛 6 | 🌐 JavaScript | 📅 2022-01-11 - Quickly run npm scripts by prefix without typing the full name.
* [screwy](https://github.com/samueleaton/screwy) ⚠️ Archived - The npm scripts GUI.
* [edit-script](https://github.com/RyanZim/edit-script) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2022-12-24 - Edit npm scripts from the command line without worrying about JSON escaping.

## Cross-platform Shell Reference

A quick reference of the shell operators & commands that work the same on Unix and Windows.

* Use `&&` to run commands in sequence. If a command fails, the script exits.
* Use `|` to pipe the stdout of one command into the stdin of the next. (`do-something | something else`)
* Use `>` to write the stdout of a command to a file. (`do-something > file`)
* Use `<` to send the contents of a file to a command's stdin. (`command < file`)
* Use `cd <dir>` to change the current working directory to `<dir>`. Note that `cd` alone prints the current working directory on windows, but changes the working directory to `~` on \*nix.

## `npm run` Reference

You can use `npm run-script` or `npm run`; they both do the same thing, but `npm run` is shorter.

* Run just `npm run` to print a list of scripts.
* Running `npm run script` (where `script` is the name of your script) will run `prescript`, `script`, and `postscript`; in that order.
  * You can't nest `pre` and `post` hooks (i.e. `preprescript` won't work).
* You can pass arguments to your scripts by passing `--` to `npm run`, followed by the arguments. Example: Given the script `"mocha": "mocha"`, you can run `npm run mocha -- --reporter xunit`. This effectively runs `mocha --reporter xunit`.
* Running `npm test` is the same as running `npm run test`. The same applies to `npm start` and `npm stop`.
* You can run `npm run <script> -s` to silence the default npm output (useful for calling a script within another script).

## Contributing

See [CONTRIBUTING.md](https://github.com/RyanZim/awesome-npm-scripts/blob/master/CONTRIBUTING.md) ⭐ 741 | 🐛 1 | 📅 2026-07-23.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-03._
