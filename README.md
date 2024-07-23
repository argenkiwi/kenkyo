# Kenkyo

A layered keyboard layout for standard ANSI keyboards

> Kenkyo (謙虚) is the Japanese term for humility or modesty.

**TL;DR;** Install one of the supported keyboard customisation applications, place the
configuration file we provide in the recommended location and use as follows:

- Hold a, s, d, f and v for meta, shift, control, alt and altgr respectively.
- Hold m, j, k, l and semicolon for altgr, alt, control, shift and meta respectively.
- Hold caps-lock to activate the extend (navigation/editing) layer.
- Hold space-bar (anchor key) and immediately tap:
  - caps-lock to anchor the extend layer
  - left-shift to anchor the shift layer
  - 'b' to anchor your custom (macros, shortcuts, etc.) layer
  - any other key to anchor the fumbol (function/number/symbol) layer

## Goal

In this repository I intend to share configuration files, for a range of free and
open-source keyboard customisation applications, which implement a keyboard layout I
developed, following a series of principles, aiming at providing a starting point
for those seeking to increase their productivity and/or improve the ergonomy of their
workflows without having to spend too much money on expensive hardware, or too much time
doing research, in order to experience the benefits of keyboard customisation.

## Principles

- Seamlessness: A user that is unaware or the presence of this layout should not be able to
 tell it is there. 
- Progressiveness: A new user of the layout should be able to adopt the layout gradually and
 always have the option to fall-back to pre-existing habits if necessary.
- Composability: The layout should be built on well known patterns that can be applied 
 together or individually.
- Efficiency: The layout should endeavour to strike a balance between the effort required
 for its use (i.e. hand motion) and that required to learn it (i.e., complexity).

## Patterns

- [Home row modifiers](https://precondition.github.io/home-row-mods)
- [Impermanent (momentary) layers](https://jonny-wamsley.gitbook.io/the-ultimate-guide-to-keyboard-layers/ch-3-layer-activators/3.3-shift-layers)
- [Layer anchoring](https://argenkiwi.medium.com/keyboard-layer-pinning-20aafede96e5)

## Components:

- [Main layer](http://www.keyboard-layout-editor.com/##@_name=Main%3B&@_w:1.5%3B&=Tab&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&=%7B%0A%5B&=%7D%0A%5D&_w:1.5%3B&=%7C%0A%5C%3B&@_w:1.75%3B&=Caps%20Lock%0A%0A%0A%0A%0A%0A%0A%0A%0AExtend&=A%0A%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=S%0A%0A%0A%0A%0A%0A%0A%0A%0AShift&=D%0A%0A%0A%0A%0A%0A%0A%0A%0AWin&=F%0A%0A%0A%0A%0A%0A%0A%0A%0AAlt&=G&=H&=J%0A%0A%0A%0A%0A%0A%0A%0A%0AAlt&=K%0A%0A%0A%0A%0A%0A%0A%0A%0AWin&=L%0A%0A%0A%0A%0A%0A%0A%0A%0AShift&=%2F:%0A%2F%3B%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=%22%0A'&_w:2.25%3B&=Enter%3B&@_w:2.25%3B&=Shift&=Z&=X&=C&=V%0A%0A%0A%0A%0A%0A%0A%0A%0AAltGr&=B&=N&=M%0A%0A%0A%0A%0A%0A%0A%0A%0AAltGr&=%3C%0A,&=%3E%0A.&=%3F%0A%2F%2F&_w:2.75%3B&=Shift%3B&@_w:1.25%3B&=Ctrl&_w:1.25%3B&=Win&_w:1.25%3B&=Alt&_a:7&w:6.25%3B&=Fumbol&_a:4&w:1.25%3B&=Alt&_w:1.25%3B&=Win&_w:1.25%3B&=Menu&_w:1.25%3B&=Ctrl)
- Shift layer (shift-bar)
- [Extend layer](http://www.keyboard-layout-editor.com/##@_name=Extend&notes=See%20https%2F:%2F%2F%2F%2Fcolemakmods.github.io%2F%2Fergonomic-mods%2F%2Fextend.html%3B&@_a:7&w:1.5%3B&=&_a:4%3B&=Esc%0AAlt&_a:7%3B&=&=&=&=&_a:4%3B&=PgUp&=Home&=Up&=End&=Ins&_a:7%3B&=&=&_w:1.5%3B&=%3B&@_c=%23ffe5b4&w:1.75%3B&=Extend&_c=%23cccccc&a:4%3B&=Ctrl&=Shift&=Win&=Alt&_a:7%3B&=&_a:4%3B&=PgDn&=Left&=Down&=Right&=Del&_a:7%3B&=&_w:2.25%3B&=%3B&@_w:2.25%3B&=&=&=&=&=&=&_a:4%3B&=Menu&=Bspc&=Spc&=Tab&=Enter&_a:7&w:2.75%3B&=%3B&@_w:1.25%3B&=&_w:1.25%3B&=&_w:1.25%3B&=&_w:6.25%3B&=Extend&_w:1.25%3B&=&_w:1.25%3B&=&_w:1.25%3B&=&_w:1.25%3B&=)
- [Fumbol layer](http://www.keyboard-layout-editor.com/##@_name=Fumbol%3B&@_a:7&w:1.5%3B&=&_a:4%3B&=F1&=F2&=F3&=F4&=F5&=F6&=F7&=F8&=F9&=F10&=F11&=F12&_a:7&w:1.5%3B&=%3B&@_w:1.75%3B&=Extend&_a:4%3B&=1%0A!%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=2%0A%2F@%0A%0A%0A%0A%0A%0A%0A%0AShift&=3%0A%23%0A%0A%0A%0A%0A%0A%0A%0AWin&=4%0A$%0A%0A%0A%0A%0A%0A%0A%0AAlt&=5%0A%25&=6%0A%5E&=7%0A%2F&%0A%0A%0A%0A%0A%0A%0A%0AAlt&=8%0A*%0A%0A%0A%0A%0A%0A%0A%0AWin&=9%0A(%0A%0A%0A%0A%0A%0A%0A%0AShift&=0%0A)%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=%5C%0A%7C&_a:7&w:2.25%3B&=%3B&@_w:2.25%3B&=&_a:4%3B&=Mute&=VolDn&=VolUp&=Play&_a:7%3B&=Cstm&_a:4%3B&=%60%0A~&=-%0A%2F_&=+%0A+&=%5B%0A%7B&=%7D%0A%7D&_a:7&w:2.75%3B&=%3B&@_w:1.25%3B&=&_w:1.25%3B&=&_w:1.25%3B&=&_c=%23ffe5b4&w:6.25%3B&=Fumbol&_c=%23cccccc&w:1.25%3B&=&_w:1.25%3B&=&_w:1.25%3B&=&_w:1.25%3B&=)
 (function, number, symbol)
- Custom (or personal) layer
 
## Keyboard customisation software

- [Kanata](https://github.com/jtroo/kanata)
- [Keyd](https://github.com/rvaiya/keyd)
- [Karabiner](https://github.com/pqrs-org/Karabiner-Elements) + [Goku](https://github.com/yqrashawn/GokuRakuJoudo) (partial implementation)
