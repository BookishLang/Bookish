### <img src="https://media.discordapp.net/attachments/916226674071339010/1033365399485562950/Bookish.png?width=20&height=20" alt="#"> Bookish
# The `if` statement on Bookish

Document published on: **17/11/2022** - takes a few seconds to a minute to read.

With if statements, you are able to decide what happens if something is true or false or if something has the property or the value you that expect.

## Example 1

```csharp
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

## Example 2

```csharp

if ("x" == "x") {
    
    print("X is X!");
    
}
else {
    
    print("X is not X!");
    
}
```

## Example 3

```csharp

if (9 == 9) {
    
    print("9 is 9!");
    
}
else {
    
    print("9 is not 9!");
    
}
```

## Example 4 [IF NOT]

```csharp

if (9 != 9) {
    
    print("9 is not 9!");
    
}
else {
    
    print("9 is 9!");
    
}
```

## Example 4 [IF NOT & ELSE IF]

```csharp

if (9 != 9) {
    
    print("9 is not 9!");
    
}
else if (9 == 8) {
    
    print("9 is 8!");
    
}
else if (9 == 9) {
    
    print("9 is 9!");
    
}
else {
    
    print("None of the above.");
    
}
```

It's a very common way to make create conditional statements depending on a value that your app may expect to return. However, you're also able to use `while` on Bookish.
