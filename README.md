# GameMath

GameMath is a small, free open-source math library for games.

We aim to provide to most useful common math routines you need in games, without over-engineering or trying to be overly scientific.

If you're missing anything, we'd love to see it - please refer to the [Contributing](https://github.com/npruehs/game-math/blob/develop/CONTRIBUTING.md) file!

## Features

* Extensive vector structs for ints and floats (e.g. Vector2I, Vector3F)
* Basic geometric shapes (e.g. RectangleF, LineF)
* Intersection tests (e.g. line-line, line-circle)
* Utility methods (e.g. rounding and casting to int)
* Pseudo-random number generators

## Getting GameMath

You can either

* download BINARIES from the [Releases](https://github.com/npruehs/game-math/releases) page
* checkout SOURCES from this repository

## Usage

Just import the `GameMath` namespace and you're good to go!

    using GameMath;

## Development Cycle

We know that using a library like GameMath in production requires you to be completely sure about stability and compatibility. Thus, new releases of GameMath are created using [Semantic Versioning](http://semver.org/). In short:

* Version numbers are specified as MAJOR.MINOR.PATCH.
* MAJOR version increases indicate incompatible changes with respect to the public GameMath API.
* MINOR version increases indicate new functionality that are backwards-compatible.
* PATCH version increases indicate backwards-compatible bug fixes.

## Bugs & Feature Requests

We are sorry that you've experienced issues or are missing a feature! After verifying that you are using the [latest version](https://github.com/npruehs/game-math/releases) of GameMath and having checked whether a [similar issue](https://github.com/npruehs/game-math/issues) has already been reported, feel free to [open a new issue](https://github.com/npruehs/game-math/issues/new). In order to help us resolving your problem as fast as possible, please include the following details in your report:

* Steps to reproduce
* What happened?
* What did you expect to happen?

After being able to reproduce the issue, we'll look into fixing it immediately.

## Contributors

(in no particular order)

* [Nick Prühs](https://github.com/npruehs) (Maintainer)
* [Christian Oeing](https://github.com/coeing)
* [Heiner Schmidt]

## License

GameMath is released under the [MIT license](https://github.com/npruehs/game-math/blob/develop/LICENSE).