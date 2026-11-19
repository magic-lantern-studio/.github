Magic Lantern is a suite of applications with which professional title creators
can author interactive entertainment titles. The core of this collection of
tools is a title specification format called the Digital Workprint. Magic
Lantern includes authoring tools to create, edit, and run Digital Workprints.
Additionally, it has tools to translate workprints into forms that can be
efficiently played on a target platform. Magic Lantern intends to support
multiple target platforms (multi-mastering).

# Resources

The **mle-documentation** repository contains most of the documentation for
the Magic Lantern Studio organization. Please refer to that location for
the most currect information on how to build and use the Magic Lantern
SDK and toolchain.

* [Organization Wiki](https://github.com/magic-lantern-studio/mle-documentation/wiki)

# Repositories

The Magic Lantern Studio is comprised of the following repositories

* **mle-core-env** - Core build environment tools
* **mle-core-util** - Core Magic Lantern utility library
* **mle-core-math** - Core Magic Lantern math libraries
* **mle-core-dwp** - Core Magic Lantern Digital Workprint libraries
* **mle-core-dpp** - Core Magic Lantern Digital Playprint libraries
* **mle-core-mlert** - Core Magic Lantern Runtime Engine library
* **mle-parts** - Magic Lantern parts (Actor/Role/MediaRef/Set/Stage components)
* **mle-atk** - Magic Lantern Authoring Toolkit library
* **mle-players** - Magic Lantern Rehearsal Player
* **mle-studio** - Magic Lantern Studio IDE

# Magic Lantern SDK

The Magic Lantern Software Development Kit (SDK) is used to build titles
that don't rely on additional parts provided by the Magic Lantern Studio.
The SDK is constructed from the following repositories:

* **mle-core-env** - Core build environment tools
* **mle-core-util** - Core Magic Lantern utility library
* **mle-core-math** - Core Magic Lantern math libraries
* **mle-core-dwp** - Core Magic Lantern Digital Workprint libraries
* **mle-core-dpp** - Core Magic Lantern Digital Playprint libraries
* **mle-core-mlert** - Core Magic Lantern Runtime Engine library

In addition to the Core libraries, the SDK provides the tools for mastering
a title.

# Magic Lantern Rehearsal Platform

The Magic Lantern Rehearsal Platform includes the SDK as well as additional
parts for creating and playing titles. The additional repositories included
in this platform are:

* **mle-parts** - Magic Lantern parts (Actor/Role/MediaRef/Set/Stage components)
* **mle-atk** - Magic Lantern Authoring Toolkit library
* **mle-players** - Magic Lantern Rehearsal Player

# Magic Lantern Studio

The full Magic Lantern Studio includes the SDK, Rehearsal Platform and the
IDE components provided in:

* **mle-studio** - Magic Lantern Studio IDE
