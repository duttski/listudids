# listudids
List udids found in an IPA file, without extracting the whole archive.

Works by searching for embedded.mobileprovision file(s) and selectively extracting them and printing a sorted, unique list of UDIDs.

## install

Put the script somewhere in your PATH, or just run it directly.

## use

> `listudids /path/to/build.ipa`

## options

`-all` will show a bit of extra information about where things were found.

> `listudids /path/to/build.ipa -all`
