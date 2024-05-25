<div align="center">
<h1>DOM Testing Library</h1>

<a href="https://www.emojione.com/emoji/1f419">
  <img
    height="80"
    width="80"
    alt="octopus"
    src="https://raw.githubusercontent.com/dramaorg/adipisci-veritatis/main/other/octopus.png"
  />
</a>

<p>Simple and complete DOM testing utilities that encourage good testing
practices.</p>

[**Read the docs**](https://testing-library.com/dom) |
[Edit the docs](https://github.com/testing-library/testing-library-docs)

</div>

<hr />

<!-- prettier-ignore-start -->
[![Build Status][build-badge]][build]
[![Code Coverage][coverage-badge]][coverage]
[![version][version-badge]][package]
[![downloads][downloads-badge]][npmtrends]
[![MIT License][license-badge]][license]
[![All Contributors][all-contributors-badge]](#contributors)
[![PRs Welcome][prs-badge]][prs]
[![Code of Conduct][coc-badge]][coc]
[![Discord][discord-badge]][discord]

[![Watch on GitHub][github-watch-badge]][github-watch]
[![Star on GitHub][github-star-badge]][github-star]
[![Tweet][twitter-badge]][twitter]
<!-- prettier-ignore-end -->

<div align="center">
  <a href="https://testingjavascript.com">
    <img
      width="500"
      alt="TestingJavaScript.com Learn the smart, efficient way to test any JavaScript application."
      src="https://raw.githubusercontent.com/dramaorg/adipisci-veritatis/main/other/testingjavascript.jpg"
    />
  </a>
</div>

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [The Problem](#the-problem)
- [This Solution](#this-solution)
- [Installation](#installation)
- [Documentation](#documentation)
- [Guiding Principles](#guiding-principles)
- [Contributors](#contributors)
- [LICENSE](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## The Problem

You want to write maintainable tests for your Web UI. As a part of this goal,
you want your tests to avoid including implementation details of your components
and rather focus on making your tests give you the confidence for which they are
intended. As part of this, you want your testbase to be maintainable in the long
run so refactors of your components (changes to implementation but not
functionality) don't break your tests and slow you and your team down.

## This Solution

The `DOM Testing Library` is a very light-weight solution for testing DOM nodes
(whether simulated with [`JSDOM`](https://github.com/jsdom/jsdom) as provided by
default with [Jest][] or in the browser). The main utilities it provides involve
querying the DOM for nodes in a way that's similar to how the user finds
elements on the page. In this way, the library helps ensure your tests give you
confidence in your UI code. The `DOM Testing Library`'s primary guiding
principle is:

> [The more your tests resemble the way your software is used, the more
> confidence they can give you.][guiding-principle]

## Installation

This module is distributed via [npm][npm] which is bundled with [node][node] and
should be installed as one of your project's `devDependencies`:

```
npm install --save-dev @dramaorg/adipisci-veritatis
```

> [**Docs**](https://testing-library.com/docs/install)

## Documentation

Read the docs (and discover framework and tool-specific implementations) at
[testing-library.com](https://testing-library.com/dom)

## Guiding Principles

> [The more your tests resemble the way your software is used, the more
> confidence they can give you.][guiding-principle]

We try to only expose methods and utilities that encourage you to write tests
that closely resemble how your web pages are used.

Utilities are included in this project based on the following guiding
principles:

1.  If it relates to rendering components, it deals with DOM nodes rather than
    component instances, nor should it encourage dealing with component
    instances.
2.  It should be generally useful for testing the application components in the
    way the user would use it. We _are_ making some trade-offs here because
    we're using a computer and often a simulated browser environment, but in
    general, utilities should encourage tests that use the components the way
    they're intended to be used.
3.  Utility implementations and APIs should be simple and flexible.

At the end of the day, what we want is for this library to be pretty
light-weight, simple, and understandable.

## Contributors

Thanks goes to these people ([emoji key][emojis]):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://kentcdodds.com"><img src="https://avatars.githubusercontent.com/u/1500684?v=3?s=100" width="100px;" alt="Kent C. Dodds"/><br /><sub><b>Kent C. Dodds</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=kentcdodds" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=kentcdodds" title="Documentation">📖</a> <a href="#infra-kentcdodds" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=kentcdodds" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.smooth-code.com"><img src="https://avatars2.githubusercontent.com/u/266302?v=4?s=100" width="100px;" alt="Greg Bergé"/><br /><sub><b>Greg Bergé</b></sub></a><br /><a href="#ideas-neoziro" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://audiolion.github.io"><img src="https://avatars1.githubusercontent.com/u/2430381?v=4?s=100" width="100px;" alt="Ryan Castner"/><br /><sub><b>Ryan Castner</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=audiolion" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.dnlsandiego.com"><img src="https://avatars0.githubusercontent.com/u/8008023?v=4?s=100" width="100px;" alt="Daniel Sandiego"/><br /><sub><b>Daniel Sandiego</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dnlsandiego" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Miklet"><img src="https://avatars2.githubusercontent.com/u/12592677?v=4?s=100" width="100px;" alt="Paweł Mikołajczyk"/><br /><sub><b>Paweł Mikołajczyk</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Miklet" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://co.linkedin.com/in/alejandronanez/"><img src="https://avatars3.githubusercontent.com/u/464978?v=4?s=100" width="100px;" alt="Alejandro Ñáñez Ortiz"/><br /><sub><b>Alejandro Ñáñez Ortiz</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=alejandronanez" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/pbomb"><img src="https://avatars0.githubusercontent.com/u/1402095?v=4?s=100" width="100px;" alt="Matt Parrish"/><br /><sub><b>Matt Parrish</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Apbomb" title="Bug reports">🐛</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pbomb" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pbomb" title="Documentation">📖</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pbomb" title="Tests">⚠️</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/wKovacs64"><img src="https://avatars1.githubusercontent.com/u/1288694?v=4?s=100" width="100px;" alt="Justin Hall"/><br /><sub><b>Justin Hall</b></sub></a><br /><a href="#platform-wKovacs64" title="Packaging/porting to new platform">📦</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/antoaravinth"><img src="https://avatars1.githubusercontent.com/u/1241511?s=460&v=4?s=100" width="100px;" alt="Anto Aravinth"/><br /><sub><b>Anto Aravinth</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=antoaravinth" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=antoaravinth" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=antoaravinth" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/JonahMoses"><img src="https://avatars2.githubusercontent.com/u/3462296?v=4?s=100" width="100px;" alt="Jonah Moses"/><br /><sub><b>Jonah Moses</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JonahMoses" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://team.thebrain.pro"><img src="https://avatars1.githubusercontent.com/u/4002543?v=4?s=100" width="100px;" alt="Łukasz Gandecki"/><br /><sub><b>Łukasz Gandecki</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=lgandecki" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=lgandecki" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=lgandecki" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://sompylasar.github.io"><img src="https://avatars2.githubusercontent.com/u/498274?v=4?s=100" width="100px;" alt="Ivan Babak"/><br /><sub><b>Ivan Babak</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Asompylasar" title="Bug reports">🐛</a> <a href="#ideas-sompylasar" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=sompylasar" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=sompylasar" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jday3"><img src="https://avatars3.githubusercontent.com/u/4439618?v=4?s=100" width="100px;" alt="Jesse Day"/><br /><sub><b>Jesse Day</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jday3" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://gnapse.github.io"><img src="https://avatars0.githubusercontent.com/u/15199?v=4?s=100" width="100px;" alt="Ernesto García"/><br /><sub><b>Ernesto García</b></sub></a><br /><a href="#question-gnapse" title="Answering Questions">💬</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=gnapse" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=gnapse" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://jomaxx.com"><img src="https://avatars2.githubusercontent.com/u/2747424?v=4?s=100" width="100px;" alt="Josef Maxx Blake"/><br /><sub><b>Josef Maxx Blake</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jomaxx" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jomaxx" title="Documentation">📖</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jomaxx" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/alecook"><img src="https://avatars3.githubusercontent.com/u/725236?v=4?s=100" width="100px;" alt="Alex Cook"/><br /><sub><b>Alex Cook</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=alecook" title="Documentation">📖</a> <a href="#example-alecook" title="Examples">💡</a> <a href="https://github.com/dramaorg/adipisci-veritatis/pulls?q=is%3Apr+reviewed-by%3Aalecook" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/dfcook"><img src="https://avatars3.githubusercontent.com/u/10348212?v=4?s=100" width="100px;" alt="Daniel Cook"/><br /><sub><b>Daniel Cook</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dfcook" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dfcook" title="Documentation">📖</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dfcook" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/thchia"><img src="https://avatars2.githubusercontent.com/u/21194045?s=400&v=4?s=100" width="100px;" alt="Thomas Chia"/><br /><sub><b>Thomas Chia</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Athchia" title="Bug reports">🐛</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=thchia" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://timdeschryver.dev"><img src="https://avatars.githubusercontent.com/u/28659384?v=4?s=100" width="100px;" alt="Tim Deschryver"/><br /><sub><b>Tim Deschryver</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=timdeschryver" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=timdeschryver" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/pulls?q=is%3Apr+reviewed-by%3Atimdeschryver" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://alexkrolick.com"><img src="https://avatars3.githubusercontent.com/u/1571667?v=4?s=100" width="100px;" alt="Alex Krolick"/><br /><sub><b>Alex Krolick</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=alexkrolick" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.maddijoyce.com"><img src="https://avatars2.githubusercontent.com/u/2224291?v=4?s=100" width="100px;" alt="Maddi Joyce"/><br /><sub><b>Maddi Joyce</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=maddijoyce" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/npeterkamps"><img src="https://avatars1.githubusercontent.com/u/25429764?v=4?s=100" width="100px;" alt="Peter Kamps"/><br /><sub><b>Peter Kamps</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Anpeterkamps" title="Bug reports">🐛</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=npeterkamps" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=npeterkamps" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://jonathanstoye.de"><img src="https://avatars2.githubusercontent.com/u/21689428?v=4?s=100" width="100px;" alt="Jonathan Stoye"/><br /><sub><b>Jonathan Stoye</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JonathanStoye" title="Documentation">📖</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JonathanStoye" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/yongdamsh"><img src="https://avatars2.githubusercontent.com/u/4126644?v=4?s=100" width="100px;" alt="Sanghyeon Lee"/><br /><sub><b>Sanghyeon Lee</b></sub></a><br /><a href="#example-yongdamsh" title="Examples">💡</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Dajust"><img src="https://avatars3.githubusercontent.com/u/8015514?v=4?s=100" width="100px;" alt="Justice Mba "/><br /><sub><b>Justice Mba </b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Dajust" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Dajust" title="Documentation">📖</a> <a href="#ideas-Dajust" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/wgcrouch"><img src="https://avatars3.githubusercontent.com/u/340761?v=4?s=100" width="100px;" alt="Wayne Crouch"/><br /><sub><b>Wayne Crouch</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=wgcrouch" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://benjaminelliott.co.uk"><img src="https://avatars1.githubusercontent.com/u/4996462?v=4?s=100" width="100px;" alt="Ben Elliott"/><br /><sub><b>Ben Elliott</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=benelliott" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://nuances.co"><img src="https://avatars3.githubusercontent.com/u/577921?v=4?s=100" width="100px;" alt="Ruben Costa"/><br /><sub><b>Ruben Costa</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=rubencosta" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://rbrtsmith.com/"><img src="https://avatars2.githubusercontent.com/u/4982001?v=4?s=100" width="100px;" alt="Robert Smith"/><br /><sub><b>Robert Smith</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Arbrtsmith" title="Bug reports">🐛</a> <a href="#ideas-rbrtsmith" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=rbrtsmith" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/dadamssg"><img src="https://avatars3.githubusercontent.com/u/881986?v=4?s=100" width="100px;" alt="dadamssg"/><br /><sub><b>dadamssg</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dadamssg" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://neilkistner.com/"><img src="https://avatars1.githubusercontent.com/u/186971?v=4?s=100" width="100px;" alt="Neil Kistner"/><br /><sub><b>Neil Kistner</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=wyze" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=wyze" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://bdchauvette.net/"><img src="https://avatars3.githubusercontent.com/u/1448597?v=4?s=100" width="100px;" alt="Ben Chauvette"/><br /><sub><b>Ben Chauvette</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=bdchauvette" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/JeffBaumgardt"><img src="https://avatars2.githubusercontent.com/u/777527?v=4?s=100" width="100px;" alt="Jeff Baumgardt"/><br /><sub><b>Jeff Baumgardt</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JeffBaumgardt" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JeffBaumgardt" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://matchai.me"><img src="https://avatars0.githubusercontent.com/u/4658208?v=4?s=100" width="100px;" alt="Matan Kushner"/><br /><sub><b>Matan Kushner</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=matchai" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=matchai" title="Documentation">📖</a> <a href="#ideas-matchai" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=matchai" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.wendtedesigns.com/"><img src="https://avatars2.githubusercontent.com/u/5779538?v=4?s=100" width="100px;" alt="Alex Wendte"/><br /><sub><b>Alex Wendte</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=themostcolm" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=themostcolm" title="Documentation">📖</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=themostcolm" title="Tests">⚠️</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ruffle1986"><img src="https://avatars0.githubusercontent.com/u/2196208?v=4?s=100" width="100px;" alt="Tamas Fodor"/><br /><sub><b>Tamas Fodor</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=ruffle1986" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/BenjaminEckardt"><img src="https://avatars3.githubusercontent.com/u/14793495?v=4?s=100" width="100px;" alt="Benjamin Eckardt"/><br /><sub><b>Benjamin Eckardt</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=BenjaminEckardt" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/campbellr"><img src="https://avatars3.githubusercontent.com/u/205752?v=4?s=100" width="100px;" alt="Ryan Campbell"/><br /><sub><b>Ryan Campbell</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=campbellr" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://taylor-briggs.com"><img src="https://avatars2.githubusercontent.com/u/1335519?v=4?s=100" width="100px;" alt="Taylor Briggs"/><br /><sub><b>Taylor Briggs</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=TaylorBriggs" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jgoz"><img src="https://avatars2.githubusercontent.com/u/132233?v=4?s=100" width="100px;" alt="John Gozde"/><br /><sub><b>John Gozde</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jgoz" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/chentsulin"><img src="https://avatars2.githubusercontent.com/u/3382565?v=4?s=100" width="100px;" alt="C. T. Lin"/><br /><sub><b>C. T. Lin</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=chentsulin" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://terrencewwong.com"><img src="https://avatars3.githubusercontent.com/u/5312329?v=4?s=100" width="100px;" alt="Terrence Wong"/><br /><sub><b>Terrence Wong</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=terrencewwong" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://www.ossfinder.com"><img src="https://avatars0.githubusercontent.com/u/12230408?v=4?s=100" width="100px;" alt="Soo Jae Hwang"/><br /><sub><b>Soo Jae Hwang</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=misoguy" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/RoystonS"><img src="https://avatars0.githubusercontent.com/u/19773?v=4?s=100" width="100px;" alt="Royston Shufflebotham"/><br /><sub><b>Royston Shufflebotham</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3ARoystonS" title="Bug reports">🐛</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=RoystonS" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=RoystonS" title="Documentation">📖</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=RoystonS" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.vadimbrodsky.com"><img src="https://avatars0.githubusercontent.com/u/591673?v=4?s=100" width="100px;" alt="Vadim Brodsky"/><br /><sub><b>Vadim Brodsky</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=VadimBrodsky" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/eunjae_lee"><img src="https://avatars3.githubusercontent.com/u/499898?v=4?s=100" width="100px;" alt="Eunjae Lee"/><br /><sub><b>Eunjae Lee</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=eunjae-lee" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://davidpeter.me"><img src="https://avatars2.githubusercontent.com/u/167743?v=4?s=100" width="100px;" alt="David Peter"/><br /><sub><b>David Peter</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=sarenji" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/@puemos"><img src="https://avatars0.githubusercontent.com/u/13174025?v=4?s=100" width="100px;" alt="Shy Alter"/><br /><sub><b>Shy Alter</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=puemos" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=puemos" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://lukaszmakuch.pl"><img src="https://avatars1.githubusercontent.com/u/11966621?v=4?s=100" width="100px;" alt="Łukasz Makuch"/><br /><sub><b>Łukasz Makuch</b></sub></a><br /><a href="#platform-lukaszmakuch" title="Packaging/porting to new platform">📦</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/tylerthehaas"><img src="https://avatars1.githubusercontent.com/u/11150235?v=4?s=100" width="100px;" alt="Tyler Haas"/><br /><sub><b>Tyler Haas</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=tylerthehaas" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=tylerthehaas" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://vesalaakso.com"><img src="https://avatars2.githubusercontent.com/u/482561?v=4?s=100" width="100px;" alt="Vesa Laakso"/><br /><sub><b>Vesa Laakso</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=valscion" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=valscion" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Tolsee"><img src="https://avatars0.githubusercontent.com/u/16590492?v=4?s=100" width="100px;" alt="Tulsi Sapkota"/><br /><sub><b>Tulsi Sapkota</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Tolsee" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/tnunes"><img src="https://avatars1.githubusercontent.com/u/163187?v=4?s=100" width="100px;" alt="Tiago Nunes"/><br /><sub><b>Tiago Nunes</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=tnunes" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=tnunes" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/JaxCavalera"><img src="https://avatars1.githubusercontent.com/u/15429762?v=4?s=100" width="100px;" alt="JaxCavalera"/><br /><sub><b>JaxCavalera</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JaxCavalera" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/pulls?q=is%3Apr+reviewed-by%3AJaxCavalera" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/bopfer"><img src="https://avatars2.githubusercontent.com/u/824368?v=4?s=100" width="100px;" alt="bopfer"/><br /><sub><b>bopfer</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=bopfer" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://blog.alfrescian.com"><img src="https://avatars0.githubusercontent.com/u/1340740?v=4?s=100" width="100px;" alt="Jan Pfitzner"/><br /><sub><b>Jan Pfitzner</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=alfrescian" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/dbismut"><img src="https://avatars2.githubusercontent.com/u/5003380?v=4?s=100" width="100px;" alt="David"/><br /><sub><b>David</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dbismut" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/diego_codes"><img src="https://avatars0.githubusercontent.com/u/5973294?v=4?s=100" width="100px;" alt="Diego Hernandez"/><br /><sub><b>Diego Hernandez</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=diego-codes" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=diego-codes" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/foray1010"><img src="https://avatars3.githubusercontent.com/u/3212221?v=4?s=100" width="100px;" alt="Alex Young"/><br /><sub><b>Alex Young</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=foray1010" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/paularmstrong"><img src="https://avatars1.githubusercontent.com/u/33297?v=4?s=100" width="100px;" alt="Paul Armstrong"/><br /><sub><b>Paul Armstrong</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=paularmstrong" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=paularmstrong" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://hu.linkedin.com/pub/tamas-szabo/57/a4b/242"><img src="https://avatars0.githubusercontent.com/u/3720079?v=4?s=100" width="100px;" alt="Tamás Szabó"/><br /><sub><b>Tamás Szabó</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=szabototo89" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=szabototo89" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/dylan_piercey"><img src="https://avatars2.githubusercontent.com/u/4985201?v=4?s=100" width="100px;" alt="Dylan Piercey"/><br /><sub><b>Dylan Piercey</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=DylanPiercey" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=DylanPiercey" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/michaellasky"><img src="https://avatars2.githubusercontent.com/u/6646599?v=4?s=100" width="100px;" alt="Michael Lasky"/><br /><sub><b>Michael Lasky</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=michaellasky" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=michaellasky" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=michaellasky" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/sebsilbermann"><img src="https://avatars3.githubusercontent.com/u/12292047?v=4?s=100" width="100px;" alt="Sebastian Silbermann"/><br /><sub><b>Sebastian Silbermann</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=eps1lon" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=eps1lon" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=eps1lon" title="Documentation">📖</a> <a href="#infra-eps1lon" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/dramaorg/adipisci-veritatis/pulls?q=is%3Apr+reviewed-by%3Aeps1lon" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://dylanvann.com/"><img src="https://avatars0.githubusercontent.com/u/1537615?v=4?s=100" width="100px;" alt="Dylan Vann"/><br /><sub><b>Dylan Vann</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=DylanVann" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://afontcu.dev"><img src="https://avatars0.githubusercontent.com/u/9197791?v=4?s=100" width="100px;" alt="Adrià Fontcuberta"/><br /><sub><b>Adrià Fontcuberta</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=afontcu" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=afontcu" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=afontcu" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://thomlom.dev"><img src="https://avatars3.githubusercontent.com/u/16003285?v=4?s=100" width="100px;" alt="Thomas Lombart"/><br /><sub><b>Thomas Lombart</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=thomlom" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/SavePointSam"><img src="https://avatars0.githubusercontent.com/u/8203211?v=4?s=100" width="100px;" alt="Sam Horton"/><br /><sub><b>Sam Horton</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=SavePointSam" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=SavePointSam" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://andrewhillcode.com"><img src="https://avatars1.githubusercontent.com/u/12396191?v=4?s=100" width="100px;" alt="Andrew Hill"/><br /><sub><b>Andrew Hill</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=andrewhillcode" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://amann.me"><img src="https://avatars1.githubusercontent.com/u/4038316?v=4?s=100" width="100px;" alt="Jan Amann"/><br /><sub><b>Jan Amann</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=amannn" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=amannn" title="Tests">⚠️</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/brapifra"><img src="https://avatars3.githubusercontent.com/u/17855450?v=4?s=100" width="100px;" alt="Brais Piñeiro"/><br /><sub><b>Brais Piñeiro</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=brapifra" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=brapifra" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.dominykas.com/"><img src="https://avatars1.githubusercontent.com/u/505619?v=4?s=100" width="100px;" alt="Dominykas Blyžė"/><br /><sub><b>Dominykas Blyžė</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dominykas" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dominykas" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://olzhas.de"><img src="https://avatars3.githubusercontent.com/u/15848876?v=4?s=100" width="100px;" alt="Olzhas Askar"/><br /><sub><b>Olzhas Askar</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pheeria" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pheeria" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pheeria" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/mbelsky_"><img src="https://avatars1.githubusercontent.com/u/3923527?v=4?s=100" width="100px;" alt="Max Belsky"/><br /><sub><b>Max Belsky</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=mbelsky" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=mbelsky" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mmantel"><img src="https://avatars2.githubusercontent.com/u/1326403?v=4?s=100" width="100px;" alt="Michael Mantel"/><br /><sub><b>Michael Mantel</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=mmantel" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://tomdoes.tech/"><img src="https://avatars1.githubusercontent.com/u/8683577?v=4?s=100" width="100px;" alt="Tom Nagle"/><br /><sub><b>Tom Nagle</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=tomanagle" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://westbrookjohnson.com"><img src="https://avatars0.githubusercontent.com/u/1156657?v=4?s=100" width="100px;" alt="Westbrook Johnson"/><br /><sub><b>Westbrook Johnson</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Westbrook" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://aziz.js.org"><img src="https://avatars3.githubusercontent.com/u/17024120?v=4?s=100" width="100px;" alt="Mohammad Aziz"/><br /><sub><b>Mohammad Aziz</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=iAziz786" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=iAziz786" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.linkedin.com/in/seetdev/"><img src="https://avatars2.githubusercontent.com/u/35116035?v=4?s=100" width="100px;" alt="seetdev"/><br /><sub><b>seetdev</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=seetdev" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=seetdev" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/xgbuils"><img src="https://avatars2.githubusercontent.com/u/6483614?v=4?s=100" width="100px;" alt="Xavier Garcia Buils"/><br /><sub><b>Xavier Garcia Buils</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=xgbuils" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=xgbuils" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/aw-davidson"><img src="https://avatars2.githubusercontent.com/u/32170938?v=4?s=100" width="100px;" alt="aw-davidson"/><br /><sub><b>aw-davidson</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=aw-davidson" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=aw-davidson" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://michaeldeboey.be"><img src="https://avatars3.githubusercontent.com/u/6643991?v=4?s=100" width="100px;" alt="Michaël De Boey"/><br /><sub><b>Michaël De Boey</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=MichaelDeBoey" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/minh_ngvyen"><img src="https://avatars3.githubusercontent.com/u/2852660?v=4?s=100" width="100px;" alt="Minh Nguyen"/><br /><sub><b>Minh Nguyen</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=NMinhNguyen" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/egilsster"><img src="https://avatars0.githubusercontent.com/u/5672257?v=4?s=100" width="100px;" alt="Egill Sveinbjörnsson"/><br /><sub><b>Egill Sveinbjörnsson</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=egilsster" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://pustovalov.dev"><img src="https://avatars2.githubusercontent.com/u/1568885?v=4?s=100" width="100px;" alt="Pavel Pustovalov"/><br /><sub><b>Pavel Pustovalov</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pustovalov" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/apalaniuk"><img src="https://avatars1.githubusercontent.com/u/17710124?v=4?s=100" width="100px;" alt="Adam Palaniuk"/><br /><sub><b>Adam Palaniuk</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=apalaniuk" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=apalaniuk" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Yama-Tomo"><img src="https://avatars0.githubusercontent.com/u/4970917?v=4?s=100" width="100px;" alt="Yama-Tomo"/><br /><sub><b>Yama-Tomo</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Yama-Tomo" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Yama-Tomo" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/airjp73"><img src="https://avatars2.githubusercontent.com/u/25882770?v=4?s=100" width="100px;" alt="Aaron Pettengill"/><br /><sub><b>Aaron Pettengill</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=airjp73" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=airjp73" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://kwboyd.com"><img src="https://avatars0.githubusercontent.com/u/13855750?v=4?s=100" width="100px;" alt="Kate W. Boyd"/><br /><sub><b>Kate W. Boyd</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=kwboyd" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/rahulchavan30"><img src="https://avatars2.githubusercontent.com/u/5296464?v=4?s=100" width="100px;" alt="Rahul Suryakanth"/><br /><sub><b>Rahul Suryakanth</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=rahulchavan30" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=rahulchavan30" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://jamie.tokyo"><img src="https://avatars0.githubusercontent.com/u/5964236?v=4?s=100" width="100px;" alt="Jamie"/><br /><sub><b>Jamie</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jamsinclair" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jamsinclair" title="Tests">⚠️</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/nstepien"><img src="https://avatars0.githubusercontent.com/u/567105?v=4?s=100" width="100px;" alt="Nicolas Stepien"/><br /><sub><b>Nicolas Stepien</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=nstepien" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://knpw.rs"><img src="https://avatars0.githubusercontent.com/u/174864?v=4?s=100" width="100px;" alt="Ken Powers"/><br /><sub><b>Ken Powers</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=knpwrs" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mzdunek93"><img src="https://avatars0.githubusercontent.com/u/10826511?v=4?s=100" width="100px;" alt="Michał Zdunek"/><br /><sub><b>Michał Zdunek</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=mzdunek93" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Lagily"><img src="https://avatars2.githubusercontent.com/u/42535205?v=4?s=100" width="100px;" alt="Ali Nasserzadeh"/><br /><sub><b>Ali Nasserzadeh</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Lagily" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://darekkay.com"><img src="https://avatars0.githubusercontent.com/u/3101914?v=4?s=100" width="100px;" alt="Darek Kay"/><br /><sub><b>Darek Kay</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=darekkay" title="Documentation">📖</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=darekkay" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=darekkay" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Lukas-Kullmann"><img src="https://avatars0.githubusercontent.com/u/387547?v=4?s=100" width="100px;" alt="Lukas"/><br /><sub><b>Lukas</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Lukas-Kullmann" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Lukas-Kullmann" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/pelotom"><img src="https://avatars2.githubusercontent.com/u/128019?v=4?s=100" width="100px;" alt="Tom Crockett"/><br /><sub><b>Tom Crockett</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pelotom" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=pelotom" title="Tests">⚠️</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/appleJax"><img src="https://avatars1.githubusercontent.com/u/13618860?v=4?s=100" width="100px;" alt="Kevin Brewer"/><br /><sub><b>Kevin Brewer</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=appleJax" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=appleJax" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/benmonro"><img src="https://avatars3.githubusercontent.com/u/399236?v=4?s=100" width="100px;" alt="Ben Monro"/><br /><sub><b>Ben Monro</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=benmonro" title="Code">💻</a> <a href="#ideas-benmonro" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=benmonro" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=benmonro" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/smeijer"><img src="https://avatars1.githubusercontent.com/u/1196524?v=4?s=100" width="100px;" alt="Stephan Meijer"/><br /><sub><b>Stephan Meijer</b></sub></a><br /><a href="#ideas-smeijer" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=smeijer" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=smeijer" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://joaoforja.com/"><img src="https://avatars2.githubusercontent.com/u/7002157?v=4?s=100" width="100px;" alt="João Forja"/><br /><sub><b>João Forja</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Jnforja" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Jnforja" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://nickmccurdy.com/"><img src="https://avatars0.githubusercontent.com/u/927220?v=4?s=100" width="100px;" alt="Nick McCurdy"/><br /><sub><b>Nick McCurdy</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=nickmccurdy" title="Documentation">📖</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=nickmccurdy" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=nickmccurdy" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/pulls?q=is%3Apr+reviewed-by%3Anickmccurdy" title="Reviewed Pull Requests">👀</a> <a href="#infra-nickmccurdy" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://calebmer.com"><img src="https://avatars1.githubusercontent.com/u/8282507?v=4?s=100" width="100px;" alt="Caleb Meredith"/><br /><sub><b>Caleb Meredith</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=calebmer" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/marcosvega91"><img src="https://avatars2.githubusercontent.com/u/5365582?v=4?s=100" width="100px;" alt="Marco Moretti"/><br /><sub><b>Marco Moretti</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=marcosvega91" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=marcosvega91" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/pulls?q=is%3Apr+reviewed-by%3Amarcosvega91" title="Reviewed Pull Requests">👀</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/tjefferson08"><img src="https://avatars2.githubusercontent.com/u/3535390?v=4?s=100" width="100px;" alt="Travis Jefferson"/><br /><sub><b>Travis Jefferson</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=tjefferson08" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=tjefferson08" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mdjastrzebski"><img src="https://avatars2.githubusercontent.com/u/6368606?v=4?s=100" width="100px;" alt="Maciej Jastrzebski"/><br /><sub><b>Maciej Jastrzebski</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Amdjastrzebski" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://commonlit.org"><img src="https://avatars3.githubusercontent.com/u/319471?v=4?s=100" width="100px;" alt="Geoff Harcourt"/><br /><sub><b>Geoff Harcourt</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=geoffharcourt" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.joshuakgoldberg.com"><img src="https://avatars1.githubusercontent.com/u/3335181?v=4?s=100" width="100px;" alt="Josh Goldberg"/><br /><sub><b>Josh Goldberg</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JoshuaKGoldberg" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JoshuaKGoldberg" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://kengregory.com"><img src="https://avatars0.githubusercontent.com/u/3155127?v=4?s=100" width="100px;" alt="Ken Gregory"/><br /><sub><b>Ken Gregory</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=kgregory" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=kgregory" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.jacobparis.com/"><img src="https://avatars2.githubusercontent.com/u/5633704?v=4?s=100" width="100px;" alt="Jacob Paris"/><br /><sub><b>Jacob Paris</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JacobParis" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=JacobParis" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://keiya01.github.io/portfolio"><img src="https://avatars1.githubusercontent.com/u/34934510?v=4?s=100" width="100px;" alt="keiya sasaki"/><br /><sub><b>keiya sasaki</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=keiya01" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/idanen"><img src="https://avatars2.githubusercontent.com/u/1687893?v=4?s=100" width="100px;" alt="Idan Entin"/><br /><sub><b>Idan Entin</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=idanen" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=idanen" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.linkedin.com/in/deniz-susman-92b40a145/"><img src="https://avatars1.githubusercontent.com/u/39295979?v=4?s=100" width="100px;" alt="Deniz Susman"/><br /><sub><b>Deniz Susman</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=DenrizSusam" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/delca85"><img src="https://avatars1.githubusercontent.com/u/4076043?v=4?s=100" width="100px;" alt="Bianca Del Carretto"/><br /><sub><b>Bianca Del Carretto</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=delca85" title="Tests">⚠️</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=delca85" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.linkedin.com/in/joshlalonde3/"><img src="https://avatars3.githubusercontent.com/u/9097492?v=4?s=100" width="100px;" alt="Josh Lalonde"/><br /><sub><b>Josh Lalonde</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=ryuuji3" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=ryuuji3" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ipap360"><img src="https://avatars2.githubusercontent.com/u/11017666?v=4?s=100" width="100px;" alt="Ioannis Papadopoulos"/><br /><sub><b>Ioannis Papadopoulos</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=ipap360" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=ipap360" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/maxnewlands"><img src="https://avatars3.githubusercontent.com/u/1304166?v=4?s=100" width="100px;" alt="Maxwell Newlands"/><br /><sub><b>Maxwell Newlands</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=maxnewlands" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=maxnewlands" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.jaredlux.com"><img src="https://avatars0.githubusercontent.com/u/450478?v=4?s=100" width="100px;" alt="Jared Luxenberg"/><br /><sub><b>Jared Luxenberg</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jluxenberg" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jluxenberg" title="Tests">⚠️</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Snizhana"><img src="https://avatars3.githubusercontent.com/u/18139946?v=4?s=100" width="100px;" alt="snizhana"/><br /><sub><b>snizhana</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Snizhana" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Snizhana" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/micha149"><img src="https://avatars2.githubusercontent.com/u/298880?v=4?s=100" width="100px;" alt="Michael van Engelshoven"/><br /><sub><b>Michael van Engelshoven</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/pulls?q=is%3Apr+reviewed-by%3Amicha149" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://ashertuggle.wixsite.com/portfolio"><img src="https://avatars2.githubusercontent.com/u/10679635?v=4?s=100" width="100px;" alt="Asher Tuggle"/><br /><sub><b>Asher Tuggle</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Aawesomeunleashed" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/winterlamon"><img src="https://avatars0.githubusercontent.com/u/16295605?v=4?s=100" width="100px;" alt="Winter LaMon"/><br /><sub><b>Winter LaMon</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=winterlamon" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=winterlamon" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://victorandcode.com"><img src="https://avatars0.githubusercontent.com/u/18427801?v=4?s=100" width="100px;" alt="Victor Cordova"/><br /><sub><b>Victor Cordova</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=victorandcode" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=victorandcode" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/slowselfip"><img src="https://avatars3.githubusercontent.com/u/9762906?v=4?s=100" width="100px;" alt="slowselfip"/><br /><sub><b>slowselfip</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Aslowselfip" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Semigradsky"><img src="https://avatars3.githubusercontent.com/u/1198848?v=4?s=100" width="100px;" alt="Dmitry Semigradsky"/><br /><sub><b>Dmitry Semigradsky</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Semigradsky" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Tismas"><img src="https://avatars2.githubusercontent.com/u/13601275?v=4?s=100" width="100px;" alt="Adam"/><br /><sub><b>Adam</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Tismas" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Tismas" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/balavishnuvj"><img src="https://avatars3.githubusercontent.com/u/13718688?v=4?s=100" width="100px;" alt="balavishnuvj"/><br /><sub><b>balavishnuvj</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=balavishnuvj" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://chriscolborne.com"><img src="https://avatars2.githubusercontent.com/u/101371?v=4?s=100" width="100px;" alt="Chris Colborne"/><br /><sub><b>Chris Colborne</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=zorfling" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/romain-trotard"><img src="https://avatars0.githubusercontent.com/u/17161484?v=4?s=100" width="100px;" alt="Romain Trotard"/><br /><sub><b>Romain Trotard</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=romain-trotard" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.thomasmarshall.com"><img src="https://avatars0.githubusercontent.com/u/770763?v=4?s=100" width="100px;" alt="Thomas Marshall"/><br /><sub><b>Thomas Marshall</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=thomasmarshall" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=thomasmarshall" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/johnjesse"><img src="https://avatars1.githubusercontent.com/u/6839660?v=4?s=100" width="100px;" alt="johnjessewood"/><br /><sub><b>johnjessewood</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Ajohnjesse" title="Bug reports">🐛</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=johnjesse" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://codepen.io/ariperkkio/"><img src="https://avatars2.githubusercontent.com/u/14806298?v=4?s=100" width="100px;" alt="Ari Perkkiö"/><br /><sub><b>Ari Perkkiö</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3AAriPerkkio" title="Bug reports">🐛</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=AriPerkkio" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=AriPerkkio" title="Documentation">📖</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/nathanforce"><img src="https://avatars2.githubusercontent.com/u/6694194?v=4?s=100" width="100px;" alt="Nathan Force"/><br /><sub><b>Nathan Force</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=nathanforce" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/ph-fritsche"><img src="https://avatars.githubusercontent.com/u/39068198?v=4?s=100" width="100px;" alt="Philipp Fritsche"/><br /><sub><b>Philipp Fritsche</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=ph-fritsche" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://medium.com/@renatoalencar"><img src="https://avatars.githubusercontent.com/u/6964593?v=4?s=100" width="100px;" alt="Renato Alencar"/><br /><sub><b>Renato Alencar</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=renatoalencar" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=renatoalencar" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/SimenB"><img src="https://avatars.githubusercontent.com/u/1404810?v=4?s=100" width="100px;" alt="Simen Bekkhus"/><br /><sub><b>Simen Bekkhus</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3ASimenB" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/gaearon"><img src="https://avatars.githubusercontent.com/u/810438?v=4?s=100" width="100px;" alt="Dan Abramov"/><br /><sub><b>Dan Abramov</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Agaearon" title="Bug reports">🐛</a> <a href="https://github.com/dramaorg/adipisci-veritatis/pulls?q=is%3Apr+reviewed-by%3Agaearon" title="Reviewed Pull Requests">👀</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://matan.io"><img src="https://avatars.githubusercontent.com/u/12711091?v=4?s=100" width="100px;" alt="Matan Borenkraout"/><br /><sub><b>Matan Borenkraout</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=MatanBobi" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/simcha90"><img src="https://avatars.githubusercontent.com/u/56388545?v=4?s=100" width="100px;" alt="simcha90"/><br /><sub><b>simcha90</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=simcha90" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/amitmiran137"><img src="https://avatars.githubusercontent.com/u/47772523?v=4?s=100" width="100px;" alt="Amit Miran"/><br /><sub><b>Amit Miran</b></sub></a><br /><a href="#infra-amitmiran137" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/leschdom"><img src="https://avatars.githubusercontent.com/u/62334278?v=4?s=100" width="100px;" alt="Dominik Lesch"/><br /><sub><b>Dominik Lesch</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=leschdom" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/G-Rath"><img src="https://avatars.githubusercontent.com/u/3151613?v=4?s=100" width="100px;" alt="Gareth Jones"/><br /><sub><b>Gareth Jones</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=G-Rath" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=G-Rath" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/riotrah"><img src="https://avatars.githubusercontent.com/u/22646419?v=4?s=100" width="100px;" alt="Rayat Rahman"/><br /><sub><b>Rayat Rahman</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=riotrah" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/savcni01"><img src="https://avatars.githubusercontent.com/u/18025894?v=4?s=100" width="100px;" alt="Nik Savchenko"/><br /><sub><b>Nik Savchenko</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=savcni01" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.hawkeye.dog"><img src="https://avatars.githubusercontent.com/u/7245931?v=4?s=100" width="100px;" alt="Kevin Fleischman"/><br /><sub><b>Kevin Fleischman</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=istateside" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=istateside" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://dfdx.us"><img src="https://avatars.githubusercontent.com/u/3087358?v=4?s=100" width="100px;" alt="Beth Hitch"/><br /><sub><b>Beth Hitch</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dfoverdx" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="http://www.jacklaurence.net"><img src="https://avatars.githubusercontent.com/u/12763356?v=4?s=100" width="100px;" alt="Jack Laurence"/><br /><sub><b>Jack Laurence</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jacklaurencegaray" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Lusito"><img src="https://avatars.githubusercontent.com/u/53570854?v=4?s=100" width="100px;" alt="SantoJambit"/><br /><sub><b>SantoJambit</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=SantoJambit" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mittalyashu"><img src="https://avatars.githubusercontent.com/u/29014463?v=4?s=100" width="100px;" alt="Yashu Mittal"/><br /><sub><b>Yashu Mittal</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=mittalyashu" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/IanVS"><img src="https://avatars.githubusercontent.com/u/4616705?v=4?s=100" width="100px;" alt="Ian VanSchooten"/><br /><sub><b>Ian VanSchooten</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=IanVS" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://supervanya.com"><img src="https://avatars.githubusercontent.com/u/12336038?v=4?s=100" width="100px;" alt="Vanya Prokopovich"/><br /><sub><b>Vanya Prokopovich</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Asupervanya" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jrnail23"><img src="https://avatars.githubusercontent.com/u/392612?v=4?s=100" width="100px;" alt="James Nail"/><br /><sub><b>James Nail</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Ajrnail23" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/robcaldecott"><img src="https://avatars.githubusercontent.com/u/796702?v=4?s=100" width="100px;" alt="Rob Caldecott"/><br /><sub><b>Rob Caldecott</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Arobcaldecott" title="Bug reports">🐛</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Dennis273"><img src="https://avatars.githubusercontent.com/u/19815164?v=4?s=100" width="100px;" alt="Dennis273"/><br /><sub><b>Dennis273</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Dennis273" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.jacksonhardaker.dev"><img src="https://avatars.githubusercontent.com/u/7596320?v=4?s=100" width="100px;" alt="Jackson Hardaker"/><br /><sub><b>Jackson Hardaker</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jacksonhardaker" title="Tests">⚠️</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.robin-drexler.com/"><img src="https://avatars.githubusercontent.com/u/474248?v=4?s=100" width="100px;" alt="Robin Drexler"/><br /><sub><b>Robin Drexler</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=robin-drexler" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/dolevoper"><img src="https://avatars.githubusercontent.com/u/53278705?v=4?s=100" width="100px;" alt="Omer Dolev"/><br /><sub><b>Omer Dolev</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=dolevoper" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/Lirlev48"><img src="https://avatars.githubusercontent.com/u/58209233?v=4?s=100" width="100px;" alt="Lirlev48"/><br /><sub><b>Lirlev48</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=Lirlev48" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/kalmi"><img src="https://avatars.githubusercontent.com/u/54426?v=4?s=100" width="100px;" alt="Tarnay Kálmán"/><br /><sub><b>Tarnay Kálmán</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=kalmi" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/MynockSpit"><img src="https://avatars.githubusercontent.com/u/5713867?v=4?s=100" width="100px;" alt="Than Hutchins"/><br /><sub><b>Than Hutchins</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=MynockSpit" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/raplemie"><img src="https://avatars.githubusercontent.com/u/1904889?v=4?s=100" width="100px;" alt="Raphaël LEMIEUX"/><br /><sub><b>Raphaël LEMIEUX</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=raplemie" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/arthurlvilasboas"><img src="https://avatars.githubusercontent.com/u/95368212?v=4?s=100" width="100px;" alt="Arthur Lauck Vilas Boas"/><br /><sub><b>Arthur Lauck Vilas Boas</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=arthurlvilasboas" title="Documentation">📖</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/DaniAcu"><img src="https://avatars.githubusercontent.com/u/26409015?v=4?s=100" width="100px;" alt="Daniel Acuña"/><br /><sub><b>Daniel Acuña</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=DaniAcu" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jlp-craigmorten"><img src="https://avatars.githubusercontent.com/u/124147726?v=4?s=100" width="100px;" alt="Craig Morten"/><br /><sub><b>Craig Morten</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=jlp-craigmorten" title="Code">💻</a> <a href="#question-jlp-craigmorten" title="Answering Questions">💬</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://naor.dev"><img src="https://avatars.githubusercontent.com/u/6171622?v=4?s=100" width="100px;" alt="Naor Peled"/><br /><sub><b>Naor Peled</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=naorpeled" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://everlong.org/"><img src="https://avatars.githubusercontent.com/u/454175?v=4?s=100" width="100px;" alt="Julien Wajsberg"/><br /><sub><b>Julien Wajsberg</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=julienw" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3Ajulienw" title="Bug reports">🐛</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/KevinBon"><img src="https://avatars.githubusercontent.com/u/1910927?v=4?s=100" width="100px;" alt="Kevin BON"/><br /><sub><b>Kevin BON</b></sub></a><br /><a href="https://github.com/dramaorg/adipisci-veritatis/commits?author=KevinBon" title="Code">💻</a> <a href="https://github.com/dramaorg/adipisci-veritatis/issues?q=author%3AKevinBon" title="Bug reports">🐛</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors][all-contributors] specification.
Contributions of any kind welcome!

## LICENSE

[MIT](LICENSE)

<!-- prettier-ignore-start -->

[npm]: https://www.npmjs.com/
[node]: https://nodejs.org
[build-badge]: https://img.shields.io/github/workflow/status/dramaorg/adipisci-veritatis/validate?logo=github&style=flat-square
[build]: https://github.com/dramaorg/adipisci-veritatis/actions?query=workflow%3Avalidate
[coverage-badge]: https://img.shields.io/codecov/c/github/dramaorg/adipisci-veritatis.svg?style=flat-square
[coverage]: https://codecov.io/github/dramaorg/adipisci-veritatis
[version-badge]: https://img.shields.io/npm/v/@dramaorg/adipisci-veritatis.svg?style=flat-square
[package]: https://www.npmjs.com/package/@dramaorg/adipisci-veritatis
[downloads-badge]: https://img.shields.io/npm/dm/@dramaorg/adipisci-veritatis.svg?style=flat-square
[npmtrends]: http://www.npmtrends.com/@dramaorg/adipisci-veritatis
[license-badge]: https://img.shields.io/npm/l/@dramaorg/adipisci-veritatis.svg?style=flat-square
[license]: https://github.com/dramaorg/adipisci-veritatis/blob/main/LICENSE
[prs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square
[prs]: http://makeapullrequest.com
[coc-badge]: https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=flat-square
[coc]: https://github.com/dramaorg/adipisci-veritatis/blob/main/CODE_OF_CONDUCT.md
[github-watch-badge]: https://img.shields.io/github/watchers/dramaorg/adipisci-veritatis.svg?style=social
[github-watch]: https://github.com/dramaorg/adipisci-veritatis/watchers
[github-star-badge]: https://img.shields.io/github/stars/dramaorg/adipisci-veritatis.svg?style=social
[github-star]: https://github.com/dramaorg/adipisci-veritatis/stargazers
[twitter]: https://twitter.com/intent/tweet?text=Check%20out%20dom-testing-library%20by%20%40testing-library%20https%3A%2F%2Fgithub.com%2Ftesting-library%2Fdom-testing-library%20%F0%9F%91%8D
[twitter-badge]: https://img.shields.io/twitter/url/https/github.com/dramaorg/adipisci-veritatis.svg?style=social
[emojis]: https://github.com/all-contributors/all-contributors#emoji-key
[all-contributors]: https://github.com/all-contributors/all-contributors
[all-contributors-badge]: https://img.shields.io/github/all-contributors/dramaorg/adipisci-veritatis?color=orange&style=flat-square
[set-immediate]: https://developer.mozilla.org/en-US/docs/Web/API/Window/setImmediate
[guiding-principle]: https://twitter.com/kentcdodds/status/977018512689455106
[jest]: https://facebook.github.io/jest
[discord-badge]: https://img.shields.io/discord/723559267868737556.svg?color=7389D8&labelColor=6A7EC2&logo=discord&logoColor=ffffff&style=flat-square
[discord]: https://discord.gg/testing-library

<!-- prettier-ignore-end -->
