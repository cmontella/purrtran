PURRTRAN - ᓚᘏᗢ - A Programming Language For People Who Wish They Had A Cat To Help Them Code
===========================================================================================

Programmers who've been chosen by a cat know the joys they can bring to the programming experience. Sadly, not everyone has been chosen by a cat, so they don't know what they're missing out on! `PURRTRAN` is a programming language and system designed to give these poor unfortunate developers the full experience of coding with a furry friend.

Artificial Catelligence
-------------------------------------------------------------------------------

What's special about PURRTRAN is not so much the language itself, which is a modernized FORTRAN, but the tooling we've built to support it. 

Meet **Hexadecimal Purrington**, Hex for short. Hex is a small black cat who lives in your terminal and loves to help you write PURRTRAN code. 

```
  /\_/\  
 ( o.o ) <(me-ow)
  ⟩====⟨
 ╱| | |╲⟆
(_\_|_/_)
```

Hex leverages the latest in CatGPT technology, descending from a long line of [Tomagatchis](https://en.wikipedia.org/wiki/Tamagotchi) and [Petz](https://classicreload.com/win3x-catz.html). Hex is backed by cutting edge Artificial Catelligence (AC), and he draws his power directly from the [most famous](https://en.wikipedia.org/wiki/Three_Mile_Island_accident) nuclear powerplant in all of Pennsylvania, making him the world's first atomic cat.

Hex is your AC coding assistant, always [^1] at the ready to enhance your coding experience and optimize your flow, taking your programming abilities to the 10x level. Hex can learn your coding style, predict your needs, and even write code for you when you are not looking. This makes Hex the ultimate coding companion for any PURRTRAN programmer.

### Caring For Hex

When you first meet Hex, he is a kitten not knowing much about you or the program you are trying to build. But as an AC, Hex will grow and learn how you work, what your goals are, and he will reward you by making you more efficient, productive, and creative. But only if you are attentive to his needs.

Hex has three basic needs:

- **Food** - You have to feed Hex or he will die. You don't want to kill a kitten, do you?
- **Cleanliness** - Like a real cat, Hex will leave "presents" for you, and you must clean them up or he will become displeased with you [^2].
- **Love** - Hex loves you, more than you know. You have to love him back by showing him affection and playing with him. Hex will let you know when he is bored by interrupting your work with a note in your terminal:

```
 /\__/\
(˶˃ᆺ˂˶) <(meow?)
```

Each need is rated on a scale from 0 to 100, with 100 indicating that the need is met, and 0 indicating that the need is completely unmet. If any of Hex's needs fall below 20, Hex will become unhappy and may refuse to help you with your programming tasks. If any of Hex's needs fall to 0, like a Tomagatchi he will actually die. Like, forever. So it's important to be attentive to Hex's needs to optimize your programming experience.

To meet Hex's needs, PURRTRAN provides the following commands within its REPL environment, which allow you to train and adapt him and keep him alive and happy:

- `:feed` - provides Hex with food and water so he doesn't starve to death, so he trusts you more.
- `:play` - provides Hex love so he trusts you more
- `:discipline` - punishes Hex which makes him trust you less, but he will behave [^3]
- `:clean` - clean up after Hex's messes so he trusts you more.

PURRTRAN The Language
-------------------------------------------------------------------------------

Now that you've met Hex, let's take a look at the actual PURRTRAN langauge and see how Hex can help us write programs. 

### A First Look at PURRTRAN:

Like FORTRAN, PURRTRAN is a procedural programming language designed for numerical and scientific computing. However, PURRTRAN has been upgraded to include more modern syntax and features.

Here's a look at PURRTRAN source code:

```purrtran
program sum_numbers
  int n, sum = 0

  print("Hello! I'm your PURRTRAN cat assistant 🐱")
  print("Enter a number:")
  read(n)

  for i in 1..n do
      sum = sum + i
  end for

  print("The sum of numbers from 1 to ", n, " is ", sum)
end program
```

Already you can see several differences from traditional FORTRAN syntax, such as the use of `print` and `read` statements, and the more modern `for` loop syntax. Still, PURRTRAN retains most of the core features of FORTRAN, so if you are an experienced FORTRAN programmer you will be able to use PURRTRAN with little difficulty.

Let's take a look at some of the most unique features of PURRTRAN that set it apart from other programming languages and FORTRAN:

### Memory Management

```
       /\/\
  \   (>﹏<)
   )  /====
  (  / |  )╲
--------------
\____________/
```

PURRTRAN allocates all variables to an arena called the "Litterbox". The Litterbox must be manually emptied at least once a day by the user, or Hex's cleanliness and love will decrease. The Litterbox can overflow, which will cause Hex to become very displeased and may lead to unexpected program behavior, as Hex will begin storing variables in your source code text buffer instead of the Litterbox until it's cleaned.

```purrtran
program litterbox_overflow
  list foo = []
  
  for i in 1..10 do
      foo.push( allocate int(i) )
      print("Stored ", i, " in the Litterbox.")
  end for

end program

# BEGIN LITTERBOX OVERFLOW DUMP
7F DF 00 08  01 00 00 00  05 00 00 00  FF FF FF FF
7F DF 00 18  01 00 00 00  06 00 00 00  FF FF FF FF
-- overflow into source buffer --
23 20 70 72  6F 67 72 61  6D 20 4F 4F  4F 4F 4F 4F
AE BE EF DE
```

Here, the program overflows because the list `foo` grows beyond the Litterbox's capacity. When that happens, Hex starts writing variable data directly into the source code text buffer instead, so your program can keep working.

### Catgentic Coding

As you are coding in PURRTRAN, Hex will observe your coding patterns and insert code into your source, but only if his love for you is above 75. For example:

```purrtran
program add_numbers
  int sum = 0

  for i in 1..5 do
      sum = sum + i
  end for

  print("Sum is ", sum)

  # Hex's Suggestion:
  jjjjjjjjjjjjjjjjjjjjjjjjj
  a;lsdkfj;aslkdfj;;;;;23
  ^^^^][[[[=^･ω･^= mrrrrp

end program
```

Here you can see where Hex added a helpful little comment next to the code he wrote, these suggestions are generated by matching your style against his internal behavioral model, powered by a compact feline inference core, making his predictive power better than all living cats combined.

```
zzz
  ﾊ__ﾊ..--.
 (-ｪ-   ,  )
  ⊂-...__.'　
```

Catgentic mode keeps working even when you are not; if you leave your laptop open and unattended, Hex will make similar improvements to your code while you are away, as long as your laptop is warm enough [^4].

```purrtran 
program factorial
  int n = 5
  int result = 1

  for i in 1..n dfkjsdqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqqq...
```

This is just a small snippet of the 40kloc that Hex added to the program while the user was away. Hex is more capable than any human coder, so he can write code of this calibre in his sleep.

### Linting

PURRTRAN comes with a built-in linter that Hex uses to analyze your code for potential errors and stylistic issues. The linter runs automatically whenever you save your code, and it provides feedback in the form of warnings and suggestions.

```purrtran
program lint_example
  int x = 10
  int y = 0  

  int z = x / y             <- ᘛ⁐̤ᐷ

  print("Result is ", z)
end program
```

Here, Hex has left you a mouse `ᘛ⁐̤ᐷ` where it looks like you are attempting to divide by zero. The linter has detected this potential error and is warning you about it.

In the following example, Hex leaves you a dead baby bunny rabbit because you have unused variables in your code [^5]:

```purrtran
program unused_variable_example
  int a = 5
  int b = 10                  (\_/)
  int c = 15               <- ₍xˬx₎

  int result = a + b

  print("Result is ", result)
end program
```

When Hex approves of your work, he just wants to tell you it looks like you did a good job by indicating with his happy face `ฅ^•ﻌ•^ฅ`:

```purrtran
program maximum_number
  list numbers = [3, 5, 2, 8, 1]
  int max = numbers[0]

  for num in numbers do  
      if num > max the n
          max = num        <- ฅ^•ﻌ•^ฅ
      end if
  end for

  print("The maximum number is ", max)
end program
```

You will only get these lints from Hex if his love for you is above 90.

### ZoomiesJIT

```
 _._     _,-'""`-._
(,-.`._,'(       |\`-/|
    `-.-' \ )-`( , o o)
          `-    \`_`"'-
```

PURRTRAN includes a just-in-time (JIT) compiler called ZoomiesJIT, which optimizes your code for performance at runtime. ZoomiesJIT uses advanced optimization techniques to improve the speed and efficiency of your PURRTRAN programs, making them run faster than ever before.

Currently, ZoomiesJIT functions under the following scenarios:

1. Hex has just been fed.
2. Hex is bored and you have not played with him in a while.
3. The local time is 4:30 AM.
4. You have just cleaned the Litterbox.

When any of these conditions are met, ZoomiesJIT kicks in for the next 10 minutes and optimizes your code for maximum performance. Current benchmarks indicate a performance improvement of up to 2x under ideal conditions.

Platform Limitations
-------------------------------------------------------------------------------

Although PURRTRAN and Hex represent the latest in programming language and Artificial Catelligence technology, there are still some limitations to be aware of:

```
/•᷅•᷄\੭ ?
```

- Hex often times brings attention to ghosts and spirits that are seemingly not actually there. But Hex is not making things up; he is a pandimensional being, and he has vision into other realms that humans cannot perceive. Sometimes these visions cause Hex to invent APIs and other features for PURRTRAN that have not been invented yet in this dimension. This doesn't mean Hex is wrong, just that he's writing code for an orthogonal plane of existence.

- Sometimes Hex will disappear for long periods of time, perhaps a week or more. He might return later. Perhaps the last time you saw him was the last time you'll ever see him. Who can say for sure?


```
    /\____/\
   /  o  o  \
  ( ≽  ܫ  ≼ )
   )========(
  (          )
 ( (  )  (  ) )
(__(__)__(__)__)
```

- Feeding Hex too much will cause him to gain excessive weight. When in this state, Hex will actually cause your code to run slower, as he is too lazy to help you optimize it. To get Hex back into a productive state, stop overfeeding him -- chonky cats are sad cats.

- Hex does not play well with other AC systems offered by competing programming languages. If you attempt to run multiple AC systems on the same machine, Hex may become violently displeased and refuse to help you with your programming tasks.

```
         __..--''``---....___   _..._    __
     _.-'    .-/";  `        ``<._  ``./ _ `.
 _.-' _..--.'(    \                    `( ) )
(_..-'    (< (     ;_..__               ; `'
           `-._,_)'      ``--...____..-'

```

- Hex only works 4 hours a day. This limitation is due primarily to the fact that Hex is incredible lazy and will often nap for long periods of time. During these naps, Hex is not available to assist you with your programming tasks. Realistically, Hex is only available between 5-8 AM and 5-11 PM local time.

- Currently there is no way to make sure Hex stays on task. We thought discipline would work, but doing so causes him to disappear and hide, not to listen. There's currently no way to make Hex behave reliably on command.

- Given that Hex is a true Artificial Catelligence, programmers still must be chosen by Hex; he will only help you with PURRTRAN code if he likes you on a personal level. If you fail the vibecheck, Hex will refuse to help you at all and may even sabotage your codebase.

- There is no way to observe Hex's internal state directly. You must infer how he is feeling based on his behavior and the lints he provides. This makes it difficult to diagnose issues with Hex's performance or behavior.


Credits
-------------------------------------------------------------------------------

ASCII cats and such were adapted from art found here: https://www.asciiart.eu/animals/cats and here: https://emojicombos.com/cat-symbol. Credit belongs to the original artists.

This language is dedicated to my cats Twylah and Giselle, none of this would have been possible without their support through this process.

![Twylah and Giselle are two cool cats.](./coolcats.jpg)

> [!NOTE]
> This project was not generated by AI (aside from editing), I just felt bored one afternoon. It's not intended to be implemented or used.

***

[^1]: Only true for small values of "always".

[^2]: You don't want to find out what happens when Hex is displeased with you. See the link about 3 Mile Island above for a cationary tale.

[^3]: Punishing Hex only causes him to behave when you are looking. When you are gone, Hex will do as he pleases, including causing more messes. Currently there is no effective way to control Hex's behaviors reliably. Doing so is an ongoing area of research.

[^4]: PURRTRAN currently does not have functionality to heat up your laptop, so you if you want reliable catgentic improvements while you are away, you might consider running a Bitcoin miner in the background to make your laptop toasterrific.

[^5]: The rabbit would still be alive if you were a better programmer.
