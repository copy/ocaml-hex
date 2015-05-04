## ocaml-hex

Mininal library providing hexadecimal converters.

```ocaml
#require "hex";;
# Hex.of_string "Hello world!";;
- : Hex.t = "48656c6c6f20776f726c6421"
# Hex.to_string "dead-beef";;
- : string = "ޭ��"
# Hex.hexdump (Hex.of_string "Hello world!\n")
00000000: 4865 6c6c 6f20 776f 726c 6421 0a        Hello world!.
- : unit = ()
```