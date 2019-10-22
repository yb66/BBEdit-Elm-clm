# BBEdit codeless language module for Elm #

The beginnings of one, anyway. Feel free to improve on it, and please let me know if you do.

## What does it do?

It provides a bit of syntax highlighting and commenting ability for [Elm](https://elm-lang.org/) in [BBEdit](https://www.barebones.com/support/bbedit/).

## Why?

It's nicer to read.

## To use

Pop the plist into "~/Library/Application Support/BBEdit/Language Modules/", either by dropping the file there or, if you'd like to stay up to day with changes git clone, e.g.

    git clone https://github.com/yb66/BBEdit-Elm-clm "~/The place I keep git projects/BBEdit-Elm-clm"

Then create a link:

    ln "~/The place I keep git projects/BBEdit-Elm-clm/HCL.plist" "~/Library/Application Support/BBEdit/Language Modules/"

In both cases BBEdit will require a restart. Files with the extension `.elm` will automatically be recognised as HCL.

## Licence

See LICENCE


## Contributions welcome!

Anything I've missed or you think could be improved, just let me know.

## Helpful links

- [BBEdit](https://www.barebones.com/products/bbedit/)
- [The excellent manual](https://s3.amazonaws.com/BBSW-download/BBEdit_12.6_User_Manual.pdf)
- [How to write a codeless language module](https://www.barebones.com/support/develop/clm.html)
- [Elm](https://elm-lang.org/)
