# Reference

Start


DEF AND
 PORT IN A
 PORT IN B
 PORT OUT Z
 NET C
 INST NAND1 NAND A B C
 INST NOT1 NOT C Z
ENDDEF

DEF TOP
  NET A
  NET B
  NET Z
  INST AND1 AND A B Z
  INST TEST AND_TEST A B Z
  INST OUTA IO_OUT A
  INST OUTB IO_OUT B
  INST OUTZ IO_OUT Z
ENDDEF

https://medium.com/curiouscaloo/macos-to-ubuntu-part1-alfred-replacement-7864b4d26397
