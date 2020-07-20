# Froggy for Game

## Descriptions

このキー配列は タクマ ([@humid](https://twitter.com/humid)) さんがデザインした [froggy](https://hum-id.jp/blog/gadget/597) にゲーム用のレイヤーを追加したものです．

また，一部オリジナルの froggy とは配置が異なるキーもあります．

[GitHub - qmk/qmk_firmware: Open-source keyboard firmware for Atmel AVR and Arm USB families](https://github.com/qmk/qmk_firmware)

## Layout

### Base

```txt
,-----------------------------------------.
|  Esc |   ;  |   (  |   [  |   <  |   {  |
|------+------+------+------+------+------|
|Conv  |   P  |   K  |   R  |   A  |   F  |
|------+------+------+------+------+------|
|  BS  |   D  |   T  |   H  |   E  |   O  |
|------+------+------+------+------+------+------.
| Shift|   Y  |   S  |   N  |   I  |   U  | FPS  |
|------+------+------+------+------+------+------|
| Ctrl | Win |  Alt |  Sym |  Num |  OPT |  Ent |
`------------------------------------------------'
```

Conv = Ctrl + Space

mac では *Win → Option, Alt → Command*

### Opt

```txt
,-----------------------------------------.
|      |   :  |   )  |   ]  |   >  |   }  |
|------+------+------+------+------+------|
| Tab  |   J  |   M  |   B  |   '  |  Tab |
|------+------+------+------+------+------|
|   .  |   V  |   C  |   L  |   Z  |   Q  |
|------+------+------+------+------+------+------.
|      |   X  |   G  |   W  |   -  |  Del |      |
|------+------+------+------+------+------+------|
|      |      |      |   ,  | SPC  |      |      |
`------------------------------------------------'
```

### Num

```txt
,-----------------------------------------.
|      |      | Func | home |  End |      |
|------+------+------+------+------+------|
|      |   *  |   7  |   8  |   9  |   -  |
|------+------+------+------+------+------|
|   .  |   /  |   4  |   5  |   6  |   +  |
|------+------+------+------+------+------+------.
|  LN  |   0  |   1  |   2  |   3  |C+S+F1|      |
|------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |
`------------------------------------------------'
```

### Sym

```txt
,-----------------------------------------.
|      |  GRV |   ~  |  PU  |  PD  |   ^  |
|------+------+------+------+------+------|
| PSCR |   \  |   #  |   =  |   ?  |   %  |
|------+------+------+------+------+------|
|      |   $  |  upA |   @  |   !  |   |  |
|------+------+------+------+------+------+------.
|  CL  |  <-  |  dwA |  ->  |   _  |   &  |      |
|------+------+------+------+------+------+------|
|      |      |      |      |      |      |      |
 `-----------------------------------------------'
```

### Func

```txt
,-----------------------------------------.
|RGBRST|  Hue |      |  RST |  Mac |  Win |
|------+------+------+------+------+------|
| RGB1 | VAL+ |  F7  |  F8  |  F9  |      |
|------+------+------+------+------+------|
| RGB2 | VAL- |  F4  |  F5  |  F6  |  F12 |
|------+------+------+------+------+------+------.
| RGB3 |  F10 |  F1  |  F2  |  F3  |  F11 |      |
|------+------+------+------+------+------+------|
|RGBOFF|      |      |      |      |      |      |
`------------------------------------------------'
```

### FPS

```txt
,-----------------------------------------.
| ESC  |  1   |  2   |  3   |  4   |  5   |
|------+------+------+------+------+------|
| Tab  |  Q   |  W   |  E   |  E   |  T   |
|------+------+------+------+------+------|
|      |  A   |  S   |  D   |  F   |  G   |
|------+------+------+------+------+------+------.
| Shift|  Z   |  X   |  C   |  V   |  B   | Base |
|------+------+------+------+------+------+------|
| Ctrl |      | ENT  | Alt  |  J   |  J   |  M   |
 `-----------------------------------------------'
```

Space が割り振られそうなところに J が配置されている理由は，なぜか FPS レイヤーで `KC_SPC` や `KC_SPACE` を割り当てても動作しないというバグがあるため
