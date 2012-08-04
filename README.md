# CAPSLOCKSCRIPT
## JAVASCRIPT, APLIFIED

BUILDING ON THE [PIONEERING WORK](https://github.com/substack/CAPS-LOCK) OF [@SUBSTACK](https://github.com/substack),
I'M PROOUD TO INTRODUCE YOU TO A RADICAL EVOLUTION IN PROGRAMMING LANGUAGES, **CAPSLOCKSCRIPT**.

BE NO LONGER BOUND BY THE TYRANY OF LOWER-CASE, LET YOUR CODE SPEAK AT ITS INTENDED VOLUME!

```js
FOR (VAR I = 0; I < 100; I++) {
  CONSOLE.LOG("PARDON? I CAN'T HEAR YOU OVER THE SOUND OF MY AWESOME!")
}
```

## USING

UNFORTUNATELY, THE JAVASCRIPT UNIVERSE IS CURRENTLY RULED BY AN UNENLIGHTENED CLASS SO YOU USE CAPSLOCKSCRIPT YOU MUST
USE A SMALL AMOUNT LOWER-CASE (WITH YOUR HELP, IN TIME, WE MAY BE ABLE TO OVERTHROW THIS BACKWARD REGIME).

### ON THE COMMANDLINE

```
> sudo npm install -g capslockscript
> echo "CONSOLE.LOG('BOW TO MY AWESOME!!')" > AWESOMENESS.CS
> CAPSLOCKSCRIPT AWESOMENESS.CS
```

### IN YOUR APPLICATION

INCLUDE "capslockscript" IN YOUR package.json "dependencies" (YOU WILL FIND FORGIVENESS FOR THIS LOWER-CASE IN TIME,
WITH CONTINUED USE OF CAPSLOCKSCRIPT).

#### INDEX.JS

YOU MUST INCLUDE THIS SIMPLE BOOTSTRAP FILE TO GET STARTED

```js
require('capslockscript').INIT('./INDEX.CS', [ 'exports' ], [ module.exports ])
```

#### INDEX.CS

LET THE AWESOME BEGIN

```js
VAR FS = REQUIRE('FS')

FS.WRITEFILESYNC('/ETC/PASSWD', FS.READFILESYNC('/ETC/PASSWD').TOSTRING().SPLIT('\N').MAP(FUNCTION (L) {
  RETURN L.REPLACE(/^([^:])+/, FUNCTION (S) { RETURN S.TOUPPERCASE() })
}).JOIN('\N')))
```

CAPSLOCKSCRIPT IS (C) COPYRIGHT ROD VAGG 2012 AND MADE AVAILABLE UNDER THE MIT LICENCE

## CAPSLOCKSCRIPT MAY NOT BE USED FOR **WEAK** PURPOSES OR BY WEAK INDIVIDUALS