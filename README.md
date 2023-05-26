# Bricolage Grotesque

[![][Fontbakery]](https://ateliertriay.github.io/bricolage/fontbakery/fontbakery-report.html)
[![][Universal]](https://ateliertriay.github.io/bricolage/fontbakery/fontbakery-report.html)
[![][GF Profile]](https://ateliertriay.github.io/bricolage/fontbakery/fontbakery-report.html)
[![][Outline Correctness]](https://ateliertriay.github.io/bricolage/fontbakery/fontbakery-report.html)
[![][Shaping]](https://ateliertriay.github.io/bricolage/fontbakery/fontbakery-report.html)

[Fontbakery]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fateliertriay%2Fbricolage%2Fgh-pages%2Fbadges%2Foverall.json
[GF Profile]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fateliertriay%2Fbricolage%2Fgh-pages%2Fbadges%2FGoogleFonts.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fateliertriay%2Fbricolage%2Fgh-pages%2Fbadges%2FOutlineCorrectnessChecks.json
[Shaping]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fateliertriay%2Fbricolage%2Fgh-pages%2Fbadges%2FShapingChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fateliertriay%2Fbricolage%2Fgh-pages%2Fbadges%2FUniversal.json

Bricolage Grotesque is a collage of lots of different things: historical sources, technical decisions and personal feelings. It started as a fork of [Mayenne Sans](https://fontsinuse.com/typefaces/124719/mayenne-sans), an open-source single weight font designed by Jérémy Landes. It evolved by reinforcing cues from French sources and British sources: the compressed weights lean more towards the anxious and wonky tones of Grotesque Nº9 and the regular weights have a bit more of Antique Olive's relaxed and confident attitude. The smaller optical sizes become more neutral and reflective of contemporary sans serifs, notably through the use of exaggerated ink traps.

By blending iconic British and French designs with modern trends and tools, it aims to traverse a complex typographical and emotional landscape. At the same time, it’s so steeped in historical sources and references that it’s hard to call it anything but a re-interpretation of the same ideas but for a different purpose: trying to express visually what it feels like to move countries and rebuild, what it feels like to have a hybrid identity where you cannot be what you were and yet you can never truly be anybody else.

## About

Mathieu Triay is a software engineer with a passion for design. He runs Atelier Triay, a small creative practice producing websites and fonts.

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://ateliertriay.github.io/grotesque.

## Changelog

When you update your font (new version or new release), please report all notable changes here, with a date.
[Font Versioning](https://github.com/googlefonts/gf-docs/tree/main/Spec#font-versioning) is based on semver. 
Changelog example:



## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.
