# Casio fx-9750GII Programming Guide
Docs on how to program the Casio fx-9750GII Calculator.

## Introduction

The Casio Casio fx-9750GII uses a form of BASIC to create simple programs.

It uses a 27x7 unit display (1 unit is 1 character), or a 63x127 pixel display when using the graphing mode.



## Creating a Program

Enter program menu with `MENU` -> `PRGM (9)`.

Create program with `F3 [NEW]`.

Enter name (`[A]-LOCK` will be on)

Press `F5` to add a password (Programs that require a password are displayed with a `*`).

Press `EXE` to create it.



## Editing a Program

Select the desired program with the arrow buttons and press `F2 [EDIT]`.

Press `SHIFT` + `VARS (^PRGM)` to open the programming menu.

Press `F6 [►]` to cycle through the menus.

Press `EXIT` to backtrack through the menus.

Press `SHIFT` + `4 (^CATALOG)` to access the catalogue of all commands, then press `F6 (CTGY)` + `5` to get the whole list of programming commands.

Press `F6 [CHAR]` to access the character menu.

The basic programming options are as follows.

**COM**
- `If`
- `Then`
- `Else`
- `I•End` (IfEnd)
- `[►]`
- `For`
- `To`
- `Step`
- `Next`
- `[►]`
- `Whle` (While)
- `WEnd` (WhileEnd)
- `Do`
- `Lp•W` (LpWhile)
- `[►]`

**CTL**
- `Prog` (Program)
- `Rtrn` (Return)
- `Brk` (Break)
- `Stop`

**JUMP**
- `Lbl` (Label)
- `Goto`
- `=>`
- `Isz`
- `Dsz`
- `Menu`

**?**

**▲**

**CLR**
- `Text` (CrlText)
- `Grph` (ClrGraph)
- `List` (ClrList)
- `Mat` (ClrMat)
- `Vct` (ClrVct)

**REL**
- `=` (==)
- `≠` (!=)
- `>`
- `<`
- `≥` (>=)
- `≤` (<=)

**I/O**
- `Lcte` (Locate)
- `Gtky` (Getkey)
- `Send`
- `Recv` (Recieve)
- `[►]`
- `S38k` (Send38k)
- `R38k` (Recieve38k)
- `Open` (OpenComport38k)
- `Close` (CloseComport38k)
- `[►]`

**:**

**STR**
- `Join` (StrJoin)
- `Len` (StrLen)
- `CmP` (StrCmP)
- `Src` (StrSrc)
- `[►]`
- `Left` (StrLeft)
- `Right` (StrRight)
- `Mid` (StrMid)
- `E►S` (Exp►Str)
- `Exp` (Exp)
- `[►]`
- `Upr` (StrUpr)
- `Lwr` (StrLwr)
- `Inv` (StrInv)
- `Shift` (StrShift)
- `Rot` (StrRotate)
- `[►]`



## Examples and Documentation

### Variables

Can only use `A` to `Z` to hold variables.

Sets the value of `A` to `1`
```c
1→A
```

Sets the value of `A` to `D` (`A`, `B`, `C`, `D`) to `1`
```c
1→A~D
```



### Loops and Conditionals

Using `If` and `Else`.
```c
3→A
If A=1
Then ...
...
Else
...
IfEnd
```

Using `While` and `WhileEnd`
```c
0→A
While A<5
A+1→A
EndWhile
```

Using `Do` and `LpWhile`
```c
Do
...
LpWhile
```

### Labels

Can use numbers to label and jump to certain sections of a program.

```c
3→A
Lbl 1


## Useful Links

- https://support.casio.com/pdf/004/fx-9750GII_Soft_E.pdf
- https://graphic-technologies.co.nz/doc/FX9750GII_Manual.pdf
- https://community.casiocalc.org/topic/2449-index-of-tutorials/
- https://community.casiocalc.org/topic/2448-casio-basic-tutorial/
