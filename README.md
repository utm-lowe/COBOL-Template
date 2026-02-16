# COBOL Template
This repository is meant to be a codespace template for writing programs in GnuCOBOL. 
I've included a few example programs to help you out. In general, the way to invoke the
compiler is as follows:

```
cobc -X <filename>
```

The programs in the examples folder are standalone, except for `roll-test.cob` and `roll.cob`.
`roll.cob` is a subroutine which simulates a die roll. `roll-test.cob` is a program which
runs this routine. To compile this example, use:

```
cobc -X roll-test.cob roll.cob
```

For more information on COBOL programming in general and GnuCOBOL in particular, please see:
* [The GnuCOBOL Home Page](https://gnucobol.sourceforge.io)
* [Learn COBOL in Y Minutes](https://learnxinyminutes.com/cobol/)
