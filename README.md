# <img src="https://media.discordapp.net/attachments/916226674071339010/1033365399485562950/Bookish.png?width=30&height=30" alt="#"> Bookish
Bookish is a very simple cross-platform programming language that can be considered as an **OOP language**, however Bookish **does not depend on OOP**. This page is for the documentation, introduction of Bookish.

You are also able to ask for help via discussions, submit any issues you encounter or any requests. This can also be considered the help/issues/feature request page of the **Bookish IDE**. If you're wondering why we only have an `.exe` for Windows in our IDE Releases, that's because the **IDE is supported on Windows only**, however you can probably use **Wine** on Linux to run the IDE.

But for the programming language, we will implement a **cross-platform virtual machine** for Bookish to run on **Windows, Mac, Linux**. The `runtime` and `compilation time` are promised to be the same, unless your computer has **harsh issues**.

What we currently support (IDE):
```
∞ Compilation of apps without the dependency of system hardware
∞ Encryption of apps created in the IDE
∞ Custom Compiler (Like JIT, but quicker; it compiles in 0-2 seconds)
∞ IntelliSense
∞ Code autocomplete/autosuggestions
∞ Resize mode, fullscreen mode
∞ IDE Settings
```

What we currently support (Language):
```
∞ Object oriented programming/Non-object oriented programming
∞ Quoted strings
∞ Definitions
∞ Classes (no inheritence)
∞ Type inferance
∞ Nil support
∞ Functions (partial, non-partial)
∞ Conditions (if/else/else if/while)
∞ Definition types: int, float, string, bool
∞ Operations: ^ / * + - & || == !=
∞ init Constructor for classes
```

Arrays are currently not supported, but are being worked on.
We are also adding in **GUI to Bookish IDE**, therefore people are able to create professional forms/pages with **Bookish**.

**∞ Usual Compilation & Run Timings:**
```
24ms - 24 milliseconds to compile & run
23ms - 23 milliseconds to compile & run
72ms - 72 milliseconds to compile & run
48ms - 48 milliseconds to compile & run
17ms - 17 milliseconds to compile & run
87ms - 87 milliseconds to compile & run
```

These are the **usual timings** people will get once they compile an app programmed in **Bookish**. It's very rare to get over **0 seconds** when compiling & running a Bookish application. The cause of the compiler **taking over 0-1 seconds to compile** may be:

```
- Errors in the code which were undetected
- Harsh hardware (Which the IDE depends on, so if it's bad, it will be slower)
- Code in the length of 100,000 —— 1,000,000 lines (runtime will be extremely slow if the code is a repeated process)
```

## Code Samples

Sample (OOP):
```cs

class bookish { 
    int x = 1;
    bool isTrue = false;

    func Example() {
        
        if (x == 1) {
            isTrue = true;
            print "True";
        }
        else {
            isTrue = false;
            print "False";
        }
        
    }
}        

bookish bksh = new bookish();

bksh.Example(); 
```

Sample (Non-OOP):
```cs
int x = 1;
bool isTrue = false;

if (x == 1) {
    isTrue = true;
    print "True";
}
else {
    isTrue = false;
    print "False";
}
```

We provide **encryption** to projects using your own **Bookish Key**.

## What's a Bookish key?

A **Bookish key** is a key generated by bookish via the IDE for application encryption, using a **Bookish key**, an algorithm is generated to protect your code. There are 3 different layers, making Bookish IDE a **very secure** software development platform. Unfortunately, we do not support **decryption**, as it will cause vulnerabilities.

# Documentation

If you would like to learn more about how to programme with **Bookish**, or if you're a beginner and want to use our docs to programme with **Bookish**, [click here](https://github.com/Pronner/Bookish).

# License

Make sure to read our [LICENSE](https://github.com/Pronner/Bookish/blob/main/LICENSE.md) before using **Bookish** or using our open-source code. Whatever is not mentioned in the license is **NOT ALLOWED** without permission from the **Bookish Developer** and **Founder** (Pronner).
