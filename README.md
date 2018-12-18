# Greek English Combination Hunspell Dictionary

## Description

This is the first iteration of an Greek *and* English combination dictionary for
hunspell. There is still a lot to be desired but it works enough to be installed
and used.

## Installation

Copy or better symlink the en_GR.{aff,dic} files to the hunspell directory
(/usr/share/hunspell in most systems).

## Script

This repository also contains a small python script (numflag) that makes this kind
of merging possible for other languages as well. It is hacky and should be carefully
adjusted for each specific case.