
How to install:

Download the .lang file:
```
wget https://raw.githubusercontent.com/Dieg0x17/syntax-highlighting-for-asm-mc88110/master/asm-88110.lang
```

Then copy to the language-specs directory

```
sudo cp asm-88110.lang /usr/share/gtksourceview-3.0/language-specs/
```

or

```
sudo cp asm-88110.lang /usr/share/gtksourceview-2.0/language-specs/
```

You can also use the External Tools for gedit to compile and run the emulator.

First enable the pluging
```
Gedit > Preferences > Complements > External Tools
```

Download the sh files for compile and run/compile:
```
wget https://raw.githubusercontent.com/Dieg0x17/syntax-highlighting-for-asm-mc88110/master/compile-asm

wget https://raw.githubusercontent.com/Dieg0x17/syntax-highlighting-for-asm-mc88110/master/run-emulator
```

And copy to:
```
cp compile-asm run-emulator ~/.config/gedit/tools
```

I recomend enabling line numbers for debugging.
```
Gedit > Preferences > Show Line Numbers
```
