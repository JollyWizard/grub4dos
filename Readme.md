# grub4dos cleanup

## Overview

This is my attempt to cleanup grub4dos into something I can hopefully improve.

## Cleanup Goals

* Standardize the build process inside a reproducible docker container.
* Remove all traces of automake (or at least the autogenerated junk).
* Remove any cygwin specific content.
* Remove chinese specific content.
* Remove default boot tools

## Learning Goals

* Understand how the graphical client is built.
* Figure out how to build grub extension modules.

## Extension Goals

* Components abstracted into a structure that is more elucidating.
* A for each directive that can generate menu areas
* A template system for mounting images
* A modular system for internationalization.
