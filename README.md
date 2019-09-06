# Haskell Workshop 
This Haskell Workshop is based on the the haskell workshop from two students who prepared it for the ESD course in Informatics study programme at Fontys Venlo in 2018. Thank you very much [Marco Kull]([https://link](https://github.com/MarcoKull)) and [Jan Evers]([https://link](https://github.com/Backend-Giraffe)). 

## Preparation
In order to be actively involved in our workshop we ask you to install the Glasgow Haskell Compiler (ghc) and preferably a [Haskell-aware text editor](https://wiki.haskell.org/Editors) in advance.

### Install ghc
The following sections describe the most common steps to install [ghc](https://wiki.haskell.org/GHC) on different platforms. If you need more assistance you can go to [the official Haskell site](https://www.haskell.org/platform/) or simply ask us directly.

#### Linux
In all major distributions ghc is included and can be installed using the native package manager.
For Debian based systems like Ubuntu or Mint this would be:
```
sudo apt-get install ghc
```

#### Windows
Download and install the [core package](https://haskell.org/platform/download/8.4.3/HaskellPlatform-8.4.3-core-x86_64-setup.exe). Afterwards you should be able to invoke ghc from command prompt:
```
C:\>ghc --version
The Glorious Glasgow Haskell Compilation System, version 8.4.3

```
#### MacOS
Download and install the [core package](https://haskell.org/platform/download/8.6.3/Haskell%20Platform%208.6.3%20Core%2064bit-signed.pkg).

### First Steps
This section describes how to create a simple "Hello World!" example to make sure you are ready to go. For convenience those steps are appropriate for any unix-like system, if you are using something inferior you will need to adjust the steps accordingly.
1.  Create a file named hello.hs containing the programm code:
    ```
    echo "hello=print(\"Hello ${USER}, thank you for your good preparation.\")" > hello.hs
    ```
2.  Open up the interactive complier:
    ```
    ghci
    ```
3.  Load the hello.hs file. (Tip: you can use autocompletion just as you do in your shell.)
    ```
    :l hello.hs
    ```
4.  Call the method by typing ```hello```. If you can see the message, get yourself some reward (grab a beer or something). We look forward to work with you.


## Assignments

* Do the assignments in /assignments folders.
* There are in total 6 tasks under assignments.
    * /task_0
    * /task_1
    * /task_2
    * /task_3
    * /task_4
    * /task_5
* **task_0** to **task_3** are **mandatory**. You _have_ to do these and check your solutions into your git classroom repository. 
* **task_4** and **task_5** are **optional**


## Git and Github

You can use the Git-Plugins of your IDE, e.g. in Visual Studio, IntelliJ or Netbeans, simply install the GIT Plugin. 

Then use GIT from your IDE. 

You can also download a standalone UI Git Client. Here are some:
* [SourceTree](https://confluence.atlassian.com/get-started-with-sourcetree)
* [GitKraken](https://www.gitkraken.com/)
* [TortoiseGit](https://tortoisegit.org/) (Windows only)


If you would like to use GIT via console, have a look at this video.
https://www.youtube.com/watch?v=HVsySz-h9r4


## Additional Material

Below you find some additional material you can use for studying. 

### Links

http://learnyouahaskell.com/chapters

https://medium.freecodecamp.org/an-introduction-to-the-basic-principles-of-functional-programming-a2c2a15c84

https://wiki.haskell.org/


### Some Nice Videos on Haskell

About Infinite datastructures:
https://www.youtube.com/watch?v=bnRNiE_OVWA

Haskell Tutorial
https://www.youtube.com/watch?v=02_H3LjqMr8 


![Test](material/IMG_0505.jpeg)
