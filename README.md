# bfbf - Brainfuck interpreter written in brainfuck

Writing this interpreter took me about 2 hours.
The interpreter supports nested loops.
It cannot run itself, because the source code is too big compared to an acceptable quantity of code.
The maximum code size is 128 bytes and memory size is also 128 bytes.

**Important!** The file from which the interpreter reads the code must contain newline at the end.
Or if reading from stdin press enter after entering the code
Everything after newline will be sent to stdin.

```ruby
$ bfi bfbf.b < hello.b
Hello World!
```
