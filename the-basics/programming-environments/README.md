---
description: Where should you develop code?
---

# Programming Environments

To start programming, we need some sort of way to write our code and put it onto the robot. There are 3 different ways to do this: FTC Blocks, OnBot Java, and IntelliJ IDEA/Android Studio.

Each of these options does things very differently from the other and choosing which one is best for you can be difficult. Here is a quick explanation of each environment, as well as the pros and cons of each.

## Blocks

FTC Blocks is a software that allows users to build code using "blocks" similar to Scratch or Blockly. Blocks are simple and easy to understand and can be picked up and used by almost anyone pretty easily. The FTC Blocks program contains all the needed tools to perform tasks with your robot and is a great way to learn about the FTC control systems. To code with FTC Blocks, connect to your robot controller, and then select the "blocks" coding option. This process will be explained in more detail in the blocks section.

### Pros

* _FIRST_ officially recommends that new programmers start with blocks.
* Easy to read and debug code.
* Basically plug-and-play - just requires a device and a connection to the robot controller's Wi-Fi.

### Cons

* Prioritizes simplicity instead of functionality.
* Does not allow for the use of external libraries, which can be a disadvantage.
* Mostly intended to be used as a stepping stone to OnBot or Android Studio.

## OnBot Java

OnBot Java allows you to write your robot code in the Java language. It, like blocks, is run in a browser while connected to the robot controller's Wi-Fi.&#x20;

### Pros

* Allows you to write code in Java.&#x20;
* Good for people with existing experience with programming.&#x20;
* Better flexibility than blocks; more organized.
* Since Java is so widely used, there are TONS of available resources and videos if help is needed.

### Cons

* Does not allow for the use of external libraries. (Technically, it is possible, but only barely)
* Harder to learn for those without experience.

##

## IntelliJ IDEA/Android Studio

The IntelliJ IDEA and Android Studio integrated development environments (IDE) are amazing tools for developing code for your robot in Java. These 2 IDEs allow for high customization and are great for managing workflow with their built-in GIT tools. They both come preinstalled with everything you'll need to develop your code and are somewhat trivial to set up.&#x20;

{% hint style="info" %}
IntelliJ IDEA is an IDE created by the JetBrains company. The "Ultimate" edition is paid, while the "Community" edition is free. The "Community" edition lacks some of the features present in the "Ultimate" version. Android Studio is basically just a version of the "Community" edition with a few extra plugins and features preinstalled.
{% endhint %}

### Pros

* Allows you to code in Java, which allows for greater flexibility than blocks. This is great for people with some existing programming experience.
* High level of customization, with different themes and plugins available to tailor the user experience.
* Multiple ways to build code onto the robot controller.
* Support for external tools and libraries like FTCLib and Roadrunner. This is can be a huge advantage.
* Tons of resources exist for both Java and the IDEs.

### Cons

* Can be complex and difficult to understand for new users.
* If you are concerned about computer storage, then these heavy environments may cause issues.
* It can be harder to debug Java code, as it is more complex and arguably less readable than blocks.

## Alternative Programming Languages

If blocks or Java are not sufficient, other options do exist!

### Kotlin

Kotlin is essentially just better Java. It includes many additional functions that Java lacks, and is also completely compatible with existing Java code! Unfortunately, not many resources exist for Kotlin in FTC.&#x20;

{% hint style="info" %}
Kotlin is not supported in the OnBot Java system.
{% endhint %}

### C/C++

C and C++ are two of the most popular coding languages and are compatible with the IntelliJ IDEA and Android Studio environments. They are very fast, but very hard to set up and are rarely needed. There are an extremely small number of resources for the use of C/C++ in FTC.
