# Hello World in :one::zero::zero: programming languages

## :computer: Table of Contents
- [Ada](#ada)
- [ALGOL](#algol)
- [Ante](#ante)
- [APL](#apl)
- [AWK](#awk)
- [bc](#bc)
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
- [Elixir](#elixir)
- [Emoticon](#emoticon)
- [Erlang](#erlang)
- [Factor](#factor)
- [Fantom](#fantom)
- [Falcon](#falcon)
- [Forth](#forth)
- [Fortran](#fortran)
- [Free basic](#free-basic)
- [F#](#f)
- [Go](#go)
- [Gosu](#gosu)
- [Groovy](#groovy)
- [Haskell](#haskell)
- [Haxe](#haxe)
- [Icon](#icon)
- [Intercal](#intercal)
- [Java](#java)
- [Javascript](#javascript)
- [Julia](#julia)
- [Kotlin](#kotlin)
- [Lisp](#lisp)
- [LOLCODE](#lolcode)
- [LÖVE](#lÖve)
- [Lua](lua)
- [Malbolge](#malbolge)
- [Mozart-Oz](#mozart-oz)
- [Nemerle](#nemerle)
- [Nice](#nice)
- [Nimrod](#nimrod)
- [OCaml](#ocaml)
- [Pascal](#pascal)
- [Pawn](#pawn)
- [Perl](#perl)
- [PHP](#php)
- [Pike](#pike)
- [Python](#python)
- [QBasic](#qbasic)
- [REXX](#rexx)
- [Ruby](#ruby)
- [Rust](#rust)
- [Scala](#scala)
- [Scheme](#scheme)
- [Simula](#simula)
- [Smalltalk](#smalltalk)
- [Swift](#swift)
- [Tcl](#tcl)
- [Typescript](#typescript)
- [Unlambda](#unlambda)
- [VB.NET](#vbnet)
- [Verilog](#verilog)
- [White Space](#white-space)
- [Ya Basic](#ya-basic)

### Ada
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.adb

```ada
with Ada.Text_IO; use Ada.Text_IO;
procedure Hello is
begin
  Put_Line("Hello World!");
end Hello;
```

### ALGOL
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.alg

```algol
print("Hello World!")
```

### Ante
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.ante

```ante
9♦8♥J♦A♦2♣3♥7♠J♦A♦7♦J♦J♦A♦3♦J♦5♥6♦4♥J♥A♥6♠6♠J♥A♦8♦J♦A♦8♠J♦A♦3♦J♦A♦6♠J♦A♦8♠J♦A♥3♦2♠J♥A♥2♣6♠J♥
```

### APL
[*Back to top*](#computer-table-of-contents)<br />

```apl
'Hello World!'
```

### AWK
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.awk

```awk
BEGIN {
   print "Hello World!"
}
```

### bc
[*Back to top*](#computer-table-of-contents)<br />

```bc
print "Hello World!\n"
```

### Befunge
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.be

```befunge
0"!dlroW olleH">:#,_@
```

### BrainFuck
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.bf

```brainfuck
++++++++++[>+++++++>++++++++++>+++<<<-]>++.>+.+++++++
..+++.>++.<<+++++++++++++++.>.+++.------.--------.>+.
```

### C
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.c

```c
#include<stdio.h>

main()
{   
  printf("Hello World!");
}
```

### C\#
[*Back to top*](#computer-table-of-contents)<br />
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
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.cc

```c++
#include <iostream>

int main()
{
    std::cout << "Hello world!\n";
}
```

### Clojure
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.clj

```clojure
(defn hello []
  (println "Hello world!"))
(hello)
```

### COBOL
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.cobc

```cobol
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO-WORLD.
PROCEDURE DIVISION.
DISPLAY 'Hello World!'.
STOP RUN.
```

### CoffeeScript
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.coffee

```coffeescript
alert "Hello World!"
```

### ColdFusion
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.cfm

```coldfusion
<cfset message = "Hello World!">
<cfoutput> #message#</cfoutput>
```

### D
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.d

```d
import std.stdio;
void main(string[ ] args)
{
   writeln("Hello World!");
}
```

### Dart
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.dart

```dart
void main(){
   print("Hello World!");
}
```

### Elixir
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.exs

```elixir
IO.puts "Hello World!"
```

### Emoticon
[*Back to top*](#computer-table-of-contents)<br />

```emoticon
Hello World! :-Q S:-P :-Q
```

### Erlang
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.erl

```erlang
-module(helloworld).
-export([start/0]).

start() ->
    io:fwrite("Hello World!\n").
```

### Factor
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.factor

```factor
USE: io
"Hello World!" print
```

### Fantom
[*Back to top*](#computer-table-of-contents)<br />
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
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.fl

```falcon
> "Hello World!"
```

### Forth
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.fth

```forth
.( Hello World!) CR
```

### Fortran
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.for

```fortran
PROGRAM HELLO
WRITE (*,100)
STOP
100 FORMAT (' Hello World! ' /)
END
```

### Free Basic
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.bas

```freebasic
Print "Hello World!"
```

### F\#
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.fs

```fsharp
printf "Hello World!\n"
```

### Go
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.go

```go
package main
import "fmt"
func main() {
 fmt.Printf("Hello World\n")
}
```

### Gosu
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.gs

```gosu
print("Hello World!")
```

### Groovy
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.groovy

```groovy
println("Hello World!")
```

### Haskell
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.hs

```haskell
main = putStrLn "Hello World"
```

### Haxe
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.hx

```haxe
class HelloWorld {
  static public function main():Void {
    trace("Hello World!");
  }
}
```

### Icon
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.icn

```icon
procedure main()
   write ("Hello World!");
end
```

### Intercal
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.i

```intercal
DO ,1 <- #13
PLEASE DO ,1 SUB #1 <- #238
DO ,1 SUB #2 <- #108
DO ,1 SUB #3 <- #112
DO ,1 SUB #4 <- #0
DO ,1 SUB #5 <- #64
DO ,1 SUB #6 <- #194
PLEASE DO ,1 SUB #7 <- #48
DO ,1 SUB #8 <- #26
DO ,1 SUB #9 <- #244
PLEASE DO ,1 SUB #10 <- #168
DO ,1 SUB #11 <- #24
DO ,1 SUB #12 <- #16
DO ,1 SUB #13 <- #162
PLEASE READ OUT ,1
PLEASE GIVE UP
```

### Java
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.java

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

### Javascript
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.js

```javascript
console.log("Hello world!");
```

### Julia
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.jl

```julia
println("Hello World!")
```

### Kotlin
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.kt

```kotlin
fun main(args : Array<String>) {
    println("Hello World!")
}
```

### Lisp
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.lisp

```lisp
(write-line "Hello World!")
```

### LOLCODE
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.lol

```lolcode
HAI
  CAN HAS STDIO?
  VISIBLE "HAI WORLD!!!1!"
KTHXBYE
```

### LÖVE
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.love

```love
function love.draw()
    love.graphics.print('Hello World!', 400, 300)
end
```

### Lua
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.lua

```lua
print("Hello World!")
```

### Malbolge
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.mal

```malbolge
('&%:9]!~}|z2Vxwv-,POqponl$Hjig%eB@@>}=<M:9wv6WsU2T|nm-,jcL(I&%$#"
`CB]V?Tx<uVtT`Rpo3NlF.Jh++FdbCBA@?]!~|4XzyTT43Qsqq(Lnmkj"Fhg${z@>
```

### Mozart-Oz
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.oz

```mozart-oz
functor
import
   Application
   System
define
   {System.showInfo 'Hello World!'}
   {Application.exit 0}
end
```

### Nemerle
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.n

```nemerle
class Hello
{
  static Main () : void
  {
    System.Console.WriteLine ("Hello World!");
  }
}
```

### Nice
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.nice

```nice
void main (String[] args)
{
	println("Hello World!");
}
```
### Nimrod
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.nim

```nim
echo  "Hello World!"
```

### OCaml
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.ml

```ocaml
print_string "Hello World!\n";;
```

### Pascal
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.pas

```pascal
Program HelloWorld(output);
begin
  writeln('Hello World!');
end.
```

### Pawn
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.p

```pawn
main()
{
   printf("Hello World!\n")
}
```

### Perl
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.pl

```perl
print "Hello World!\n";
```

### PHP
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.php

```php
<?php
  echo 'Hello World!';
?>
```

### Pike
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.pike

```pike
int main() {
    write("Hello World!\n");
    return 0;
}
```

### Python
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.py

```python
print("Hello World!")
```

### QBasic
[*Back to top*](#computer-table-of-contents)<br />

```qbasic
"Hello World!"
```

### REXX
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.rex

```rexx
say 'Hello World!'
exit
```

### Ruby
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.rb

```ruby
puts 'Hello world!'
```

### Rust
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.rs

```rust
fn main() {
    println!("Hello World!");
}
```

### Scala
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.scala

```scala
object HelloWorld {
   def main(args: Array[String]) {
      println("Hello World!")
   }
}
```

### Scheme
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.scm

```scheme
(display "Hello World!")
(newline)
```

### Simula
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.sim

```simula
Begin
   OutText ("Hello World!");
   Outimage;
End;
```

### Smalltalk
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.gst

```smalltalk
Transcript show: 'Hello World!'.
```

### Swift
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.swift

```swift
print("Hello World!")
```

### Tcl
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.tcl

```tcl
puts "Hello World!"
```

### Typescript
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.ts

```typescript
alert('Hello World!');
```

### Unlambda
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.unlambda

```unlambda
`r```````````.H.e.l.l.o. .W.o.r.l.di
```

### VB.NET
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.vb

```vb.net
Module VBModule

    Sub Main()
        Console.WriteLine("Hello World!")
    End Sub

End Module
```

### Verilog
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.v

```verilog
module main;
  initial
    begin
      $display("Hello World!");
      $finish ;
    end
endmodule
```

### White Space
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.ws

```whitespace
S S S T	S S T	S S S L
T	L
S S S S S T	T	S S T	S T	L
T	L
S S S S S T	T	S T	T	S S L
T	L
S S S S S T	T	S T	T	S S L
T	L
S S S S S T	T	S T	T	T	T	L
T	L
S S S S S T	S T	T	S S L
T	L
S S S S S T	S S S S S L
T	L
S S S S S T	T	T	S T	T	T	L
T	L
S S S S S T	T	S T	T	T	T	L
T	L
S S S S S T	T	T	S S T	S L
T	L
S S S S S T	T	S T	T	S S L
T	L
S S S S S T	T	S S T	S S L
T	L
S S S S S T	S S S S T	L
T	L
S S L
L
L
```

### Ya Basic
[*Back to top*](#computer-table-of-contents)<br />
HelloWorld.bas

```yabasic
Print "Hello World!"
```
