# Awesome Twine
_An unofficial list of the best of the twine ecosystem with a focus on small community projects._

Looking for a much longer way more official list with a lot more details? Check out the extensive [resourcelist at twinelab](https://resources.twinelab.net/)!

## Compilers

Compilers turn your story into a usable, shareable game. Almost every compiler supports every engine, through the use of "formats".

+ [Twine 2](https://twinery.org/) - The official graphical client and easiest way to build a Twine story.
+ [Tweego](https://www.motoslave.net/tweego/) - A command line based tool for building Twine stories from text files. It's written in go and is easy to install with proper piping support for use in toolchain like flows.
+ [ExTwee](https://github.com/videlais/extwee) - "Extwee is a Twee compiler supporting Twine 2-style formats using the Twee 3 specification."

## Official Engines

These are the engines which Twine and Tweego ship with default support for, and what most games will start with.

+ [Harlowe](https://twine2.neocities.org/) - The default engine for both Twine and Tweego, Harlowe is relatively powerful with strong macro support. Harlowe offers "hooks" as easy way to style passages.
+ [SugarCube](https://www.motoslave.net/sugarcube/2/) - A more powerful, libre engine that exposes more macros and functionality. 
+ [Snowman](https://github.com/videlais/snowman) - An engine built for developers focused on pure JS and CSS. Exposes minimal direct features.

<!-- ## Unofficial Engines -->
<!-- ## Macros  -->
<!-- ## Game Styles -->

## Tools

These are utilities for doing unusual things with Twine, from exporting stories to JSON to pulling them into Unity.

+ [Cradle](https://github.com/daterre/Cradle) - A tool for importing and parsing Twine stories in Unity
+ [Jailbird](https://github.com/vorpalhex/jailbird/) - A format and parser to get Twine stories into JSON.

## Integrations

These are utilities to help integrate Twine with non-Twine things. 

+ [Bitsy in Twine](https://gist.github.com/mathphreak/04e35a4a21902e5e5f8a5c283f6a8795) - A python script for getting [Bitsy](https://ledoux.itch.io/bitsy) to play nicely with Twine.
+ [Dynamic Avatar Drawer](http://perplexedpeach.gitlab.io/dynamic-avatar-drawer/twine_guide.html) - A system for dynamic avatar creation within your Twine game.

## Specifications

These are specification documents to help you write your own Twine/Twee compatible tooling.

+ [Twee 3 Spec](https://github.com/iftechfoundation/twine-specs/blob/master/twee-3-specification.md) - Spec for underlying Twee v3 format.
+ [Treaty of Babel](https://babel.ifarchive.org/babel_rev9.txt) - Where the IFID originates from and some background information on it.