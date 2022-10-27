# <img src="https://media.discordapp.net/attachments/916226674071339010/1033365399485562950/Bookish.png?width=30&height=30" alt="#"> Bookish
Bookish is a very simple cross-platform programming language that can be considered as an **OOP language**, however Bookish **does not depend on OOP**. This page is for the documentation, introduction of Bookish.

You are also able to ask for help via discussions, submit any issues you encounter or any requests. This can also be considered the help/issues/feature request page of the **Bookish IDE**.

What we currently support (IDE):
```
∞ Compilation of apps
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
∞ Operations: ^ / * + - & || == 
∞ init Constructor for classes
```

Arrays are currently not supported, but are being worked on.
We are also adding in **GUI to Bookish IDE**, therefore people are able to create professional forms/pages with **Bookish**.

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
