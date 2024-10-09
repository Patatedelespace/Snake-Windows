# Snake (kind of)

## /!\ Still in alpha, please be patient /!\

### Let me introduce you to Snake (kind of)

This is my first game using [raylib](https://raylib.com/), if you ave hany feedback or if you're experiencing any issue, let me know ;).



To compile it, you will need :
- [w64devkit](https://github.com/skeeto/w64devkit)
- [cmake](https://cmake.org/)
- and, obviously, [git](https://git-scm.com/)

First, you will have to enter into ```w64devkit.exe``` :

```cmd
cd path/to/w64devkit/w64devkit.exe
```

Then just follow thoses commands :

```cmd
git clone https://github.com/Patatedelespace/Snake.git
cd ./Snake/
cmake -B [build path]
cmake --build [build path]
```

Where [build path] is the path were you want to build it, for exemple `./build/`, or, if you to be more precise, `./build/[debug/release/alpha/beta/v1.0.0]`

Then, to run it, symply use this command (you can leave w64devkit, it's not needed anymore) :

```cmd
[build path]/Snake.exe
```

## It's the end
Hope you'll enjoy :).
