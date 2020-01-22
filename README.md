**Yet Another NARS**

![YAN](https://user-images.githubusercontent.com/8284677/71787964-c96c8400-3015-11ea-91ac-2b98d621be33.png)

Will become a complete NARS implementation in C, built on top of Minimal Sensorimotor Component (a stripped down ANSNA with Compound Terms instead of SDR's, see https://github.com/patham9/MSC, in particular v0.6.0)

***How to clone and compile (tested with GCC and Clang for x64, x86 and ARM):***

```
git clone https://github.com/patham9/YAN
cd YAN
./build.sh
```

***How to run the interactive Narsese shell:***

```
./YAN shell
```

***How to run the tests and then receive instructions how to run the current example programs:***

```
./YAN
```

**How to run an example file:**

Narsese:

```
cat ./examples/nal/example1.nal | ./YAN shell
```

English:

```
cat ./examples/english/story1.english | python english_shell.py
```

**Other**

Usage from IRC is also possible, see https://gist.github.com/patham9/75b53ea120f140fce6538271e217dfac
