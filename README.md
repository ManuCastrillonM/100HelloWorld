# Hello World in :one::zero::zero: programming languages

## :computer: Table of Contents
- [Ada](#ada)
- [ALGOL](#algol)
- [APL](#apl)
- [AWK](#awk)
- [Befunge](#befunge)
- [BrainFuck](#brainfuck)
- [C](#c)
- [C#](#c-1)
- [C++](#c-2)
- [Clojure](#clojure)
- [COBOL](#cobol)
- [CoffeeScript](#coffeescript)
- [ColdFusion](#coldfusion)
- [D](#d)
- [Dart](#dart)
- [Emoticon](#emoticon)
- [Erlang](#erlang)
- [Elixir](#elixir)
- [Factor](#factor)
- [Fantom](#fantom)
- [Falcon](#falcon)
- [Forth](#forth)
- [Free basic](#free-basic)
- [F#](#f)
- [Go](#go)
- [Haskell](#haskell)
- [Java](#java)
- [Javascript](#javascript)
- [Kotlin](#kotlin)
- [LOLCODE](#lolcode)
- [LÖVE](#lÖve)
- [Malbolge](#malbolge)
- [Perl](#perl)
- [PHP](#php)
- [Python](#python)
- [QBasic](#qbasic)
- [Ruby](#ruby)
- [Rust](#rust)
- [Scheme](#scheme)
- [Swift](#swift)
- [Typescript](#typescript)
- [Unlambda](#unlambda)

### Ada
[*Back to top*](#table-of-contents)<br />
HelloWorld.adb

```ada
with Ada.Text_IO; use Ada.Text_IO;
procedure Hello is
begin
  Put_Line("Hello World!");
end Hello;
```

### ALGOL
[*Back to top*](#table-of-contents)<br />
HelloWorld.alg

```algol
print("Hello World!")
```

### APL
[*Back to top*](#table-of-contents)<br />

```apl
'Hello World!'
```

### AWK
[*Back to top*](#table-of-contents)<br />
HelloWorld.awk

```awk
BEGIN {
   print "Hello World!"
}
```

### Befunge
[*Back to top*](#table-of-contents)<br />
HelloWorld.be

```befunge
0"!dlroW olleH">:#,_@
```

### BrainFuck
[*Back to top*](#table-of-contents)<br />
HelloWorld.b

```brainfuck
++++++++++[>+++++++>++++++++++>+++<<<-]>++.>+.+++++++
..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.
```

### C
[*Back to top*](#table-of-contents)<br />
HelloWorld.c

```c
#include<stdio.h>

main()
{   
  printf("Hello World!");
}
```

### C\#
[*Back to top*](#table-of-contents)<br />
HelloWorld.cs

```csharp
public class HelloWorld
{
   public static void Main()
   {
      System.Console.WriteLine("Hello World!");
   }
}
```

### C++
[*Back to top*](#table-of-contents)<br />
HelloWorld.cc

```c++
#include <iostream>

int main()
{
    std::cout << "Hello world!\n";
}
```

### Clojure
[*Back to top*](#table-of-contents)<br />
HelloWorld.clj

```clojure
(defn hello []
  (println "Hello world!"))
(hello)
```

### COBOL
[*Back to top*](#table-of-contents)<br />
HelloWorld.cobc

```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.
PROCEDURE DIVISION.
DISPLAY 'Hello World!'.
STOP RUN.
```

### CoffeeScript
[*Back to top*](#table-of-contents)<br />
HelloWorld.coffee

```coffeescript
alert "Hello World!"
```

### ColdFusion
[*Back to top*](#table-of-contents)<br />
HelloWorld.cfm

```coldfusion
<cfset message = "Hello World!">
<cfoutput> #message#</cfoutput>
```

### D
[*Back to top*](#table-of-contents)<br />
HelloWorld.d

```d
import std.stdio;
void main(string[ ] args)
{
   writeln("Hello World!");
}
```

### Dart
[*Back to top*](#table-of-contents)<br />
HelloWorld.dart

```dart
void main(){
   print("Hello World!");
}
```

### Emoticon
[*Back to top*](#table-of-contents)<br />

```emoticon
Hello World! :-Q S:-P :-Q
```

### Erlang
[*Back to top*](#table-of-contents)<br />
HelloWorld.erl

```erlang
-module(helloworld).
-export([start/0]).

start() ->
    io:fwrite("Hello World!\n").
```

### Elixir
[*Back to top*](#table-of-contents)<br />
HelloWorld.exs

```elixir
IO.puts "Hello World!"
```

### Factor
[*Back to top*](#table-of-contents)<br />
HelloWorld.factor

```factor
USE: io
"Hello World!" print
```

### Fantom
[*Back to top*](#table-of-contents)<br />
HelloWorld.fan

```fantom
class HelloWorld
{
  static Void main()
  {
    echo("Hello World!")
  }
}
```

### Falcon
[*Back to top*](#table-of-contents)<br />
HelloWorld.fl

```falcon
> "Hello World!"
```

### Forth
[*Back to top*](#table-of-contents)<br />
HelloWorld.fth

```forth
.( Hello World!) CR
```

### Free Basic
[*Back to top*](#table-of-contents)<br />
HelloWorld.bas

```freebasic
Print "Hello World!"
```

### F\#
[*Back to top*](#table-of-contents)<br />
HelloWorld.fs

```fsharp
printf "Hello World!\n"
```

### Go
[*Back to top*](#table-of-contents)<br />
HelloWorld.go

```go
package main
import "fmt"
func main() {
 fmt.Printf("Hello World\n")
}
```

### Haskell
[*Back to top*](#table-of-contents)<br />
HelloWorld.hs

```haskell
main = putStrLn "Hello World"
```

### Java
[*Back to top*](#table-of-contents)<br />
HelloWorld.java

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

### Javascript
[*Back to top*](#table-of-contents)<br />
HelloWorld.js

```javascript
console.log("Hello world!");
```

### Kotlin
[*Back to top*](#table-of-contents)<br />
HelloWorld.kt

```kotlin
fun main(args : Array<String>) {
    println("Hello World!")
}
```

### LOLCODE
[*Back to top*](#table-of-contents)<br />
HelloWorld.lol

```lolcode
HAI
  CAN HAS STDIO?
  VISIBLE "HAI WORLD!!!1!"
KTHXBYE
```

### LÖVE
[*Back to top*](#table-of-contents)<br />
HelloWorld.love

```love
function love.draw()
    love.graphics.print('Hello World!', 400, 300)
end
```

### Malbolge
[*Back to top*](#table-of-contents)<br />
HelloWorld.mal

```malbolge
('&%:9]!~}|z2Vxwv-,POqponl$Hjig%eB@@>}=<M:9wv6WsU2T|nm-,jcL(I&%$#"
`CB]V?Tx<uVtT`Rpo3NlF.Jh++FdbCBA@?]!~|4XzyTT43Qsqq(Lnmkj"Fhg${z@>
```

### Perl
[*Back to top*](#table-of-contents)<br />
HelloWorld.pl

```perl
print "Hello World!\n";
```

### PHP
[*Back to top*](#table-of-contents)<br />
HelloWorld.php

```php
<?php
  echo 'Hello World!';
?>
```

### Python
[*Back to top*](#table-of-contents)<br />
HelloWorld.py

```python
print("Hello World!")
```

### QBasic
[*Back to top*](#table-of-contents)<br />

```qbasic
"Hello World!"
```

### Ruby
[*Back to top*](#table-of-contents)<br />
HelloWorld.rb

```ruby
puts 'Hello world!'
```

### Rust
[*Back to top*](#table-of-contents)<br />
HelloWorld.rs

```rust
fn main() {
    println!("Hello World!");
}
```

### Scheme
[*Back to top*](#table-of-contents)<br />
HelloWorld.scm

```scheme
(display "Hello World!")
(newline)
```

### Swift
[*Back to top*](#table-of-contents)<br />
HelloWorld.swift

```swift
print("Hello World!")
```

### Typescript
[*Back to top*](#table-of-contents)<br />
HelloWorld.ts

```typescript
alert('Hello World!');
```

### Unlambda
[*Back to top*](#table-of-contents)<br />
HelloWorld.unlambda

```unlambda
`r```````````.H.e.l.l.o. .W.o.r.l.di
```
