# Kenkyo

A layered keyboard layout designed to augment your keyboard's capabilities without changing its expected behaviour, so you can remain productive as you learn to use it.

> Kenkyo (謙虚) is the Japanese term for humility or modesty.

## At a glance:

### [Main layer](https://www.keyboard-layout-editor.com/##@_name=Main;&@_w:1.5;&=Tab&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&=%7B%0A%5B&=%7D%0A%5D&_w:1.5;&=%7C%0A%5C;&@_c=#90D5FF&w:1.75;&=Caps%20Lock%0A%0A%0A%0A%0A%0A%0A%0A%0AExtend&=A%0A%0A%0A%0A%0A%0A%0A%0A%0AMeta&=S%0A%0A%0A%0A%0A%0A%0A%0A%0AShift&=D%0A%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=F%0A%0A%0A%0A%0A%0A%0A%0A%0AAlt&_c=#cccccc;&=G&=H&_c=#90D5FF;&=J%0A%0A%0A%0A%0A%0A%0A%0A%0AAlt&=K%0A%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=L%0A%0A%0A%0A%0A%0A%0A%0A%0AShift&=/:%0A/;%0A%0A%0A%0A%0A%0A%0A%0AAlt&_c=#cccccc;&=%22%0A'&_w:2.25;&=Enter;&@_w:2.25;&=Shift&=Z&=X&=C&_c=#90D5FF;&=V%0A%0A%0A%0A%0A%0A%0A%0A%0AAltGr&_c=#cccccc;&=B&=N&_c=#90D5FF;&=M%0A%0A%0A%0A%0A%0A%0A%0A%0AAltGr&_c=#cccccc;&=%3C%0A,&=%3E%0A.&=?%0A//&_w:2.75;&=Shift;&@_w:1.25;&=Ctrl&_w:1.25;&=Meta&_w:1.25;&=Alt&_c=#90D5FF&a:7&w:6.25;&=Fumbol&_c=#cccccc&a:4&w:1.25;&=Alt&_w:1.25;&=Meta&_w:1.25;&=Menu&_w:1.25;&=Ctrl)
  
![Main layer image](images/main.png)

The default layer of this layout makes use of _Home Row Modifiers_ (see [patterns](#patterns)):
- Hold `A`, `S`, `D`, `F` and `V` for `Meta` (Win/Command), `Shift`, `Control`, `Alt` and `AltGr` respectively.
- Hold `M`, `J`, `K`, `L` and `;` for `AltGr`, `Alt`, `Control`, `Shift` and `Meta` respectively.

It is also an entry point to the following layers.
  
### [Extend layer](https://www.keyboard-layout-editor.com/##@_name=Extend;&@_w:1.5;&=Tab&_c=#90D5FF;&=Esc&=Meta&_c=#cccccc;&=E&=R&=T&_c=#90D5FF;&=PgUp&=Home&=%E2%86%91&=End&=Insert&_c=#cccccc;&=%7B%0A%5B&=%7D%0A%5D&_w:1.5;&=%7C%0A%5C;&@_c=#FFA500&w:1.75;&=Caps%20Lock&_c=#90D5FF;&=Shift&=Ctrl&=Alt&_c=#cccccc;&=F&=G&_c=#90D5FF;&=PgDn&=%E2%86%90&=%E2%86%93&=%E2%86%92&=Delete&_c=#cccccc;&=%22%0A'&_w:2.25;&=Enter;&@_w:2.25;&=Shift&=Z&=X&=C&=V&=B&_c=#90D5FF;&=Menu&=Bspc&=Spc&=Tab&=Enter&_c=#cccccc&w:2.75;&=Shift;&@_w:1.25;&=Ctrl&_w:1.25;&=Meta&_w:1.25;&=Alt&_a:7&w:6.25;&=&_a:4&w:1.25;&=Alt&_w:1.25;&=Meta&_w:1.25;&=Menu&_w:1.25;&=Ctrl)
  
![Extend layer image](images/extend.png)

While holding the `CapsLock` key, with you left hand's little finger, the navigation and editing keys will become accessible under the fingers of your right hand. 
> Notice your left hand will be displaced to the left by one key. Therefore, to preserve motor memory, the modifiers will shift to the left by one key as well, except for `Meta` which is re-assigned to `W` instead.
  
### [Fumbol layer](https://www.keyboard-layout-editor.com/##@_name=Fumbol%3B&@_w:1.5%3B&=Tab&_c=%2390D5FF%3B&=F1&=F2&=F3&=F4&=F5&=F6&=F7&=F8&=F9&=F10&=F11&=F12&_w:1.5%3B&=F13%3B&@_w:1.75%3B&=Caps%20Lock%0A%0A%0A%0A%0A%0A%0A%0A%0AExtend&=!%0A1%0A%0A%0A%0A%0A%0A%0A%0AMeta&=%2F@%0A2%0A%0A%0A%0A%0A%0A%0A%0AShift&=%23%0A3%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=$%0A4%0A%0A%0A%0A%0A%0A%0A%0AAlt&=%25%0A5&=%5E%0A6&=%2F&%0A7%0A%0A%0A%0A%0A%0A%0A%0AAlt&=*%0A8%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=(%0A9%0A%0A%0A%0A%0A%0A%0A%0AShift&=)%0A0%0A%0A%0A%0A%0A%0A%0A%0AMeta&=%7C%0A%5C&_c=%23cccccc&w:2.25%3B&=Enter%3B&@_w:2.25%3B&=Shift&_c=%2390D5FF%3B&=Mute&=VolDn&=VolUp&=Play%0APause&=Cstm&=~%0A%60&=%2F_%0A-&=+%0A%2F=&=%7B%0A%5B&=%7D%0A%5D&_c=%23cccccc&w:2.75%3B&=Shift%3B&@_w:1.25%3B&=Ctrl&_w:1.25%3B&=Meta&_w:1.25%3B&=Alt&_c=%23FFA500&a:7&w:6.25%3B&=&_c=%23cccccc&a:4&w:1.25%3B&=Alt&_w:1.25%3B&=Meta&_w:1.25%3B&=Menu&_w:1.25%3B&=Ctrl)
  
![Fumbol layer image](images/fumbol.png)

To access the function/number/symbol layer, hold `Space` and immediately press any of the keys highlighted above.

The function and number keys have been distributed along the top and home (middle) rows so they match the positioning they would have on a physical keyboard (no cheat-sheet required, just look at your keyboard).

The bottom row contains symbols that would otherwise require you to move your hand away from the center of the keyboard to reach them. The order in which they appear on your physical keyboard has been preserved. The remaining 4 keys at the center of the bottom row are used for media playback and volume control.

While on the _fumbol_ layer you can tap one of the `shift` keys to anchor the _shift_ layer or the apostrophe (`'`) to anchor the optional custom layer described below.
  
### [Custom (or personal) layer](https://www.keyboard-layout-editor.com/##@_name=Custom;&@_w:1.5;&=Tab&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&=%7B%0A%5B&=%7D%0A%5D&_w:1.5;&=%7C%0A%5C;&@_c=#90D5FF&w:1.75;&=Caps%20Lock%0A%0A%0A%0A%0A%0A%0A%0A%0AExtend&=F14%0A%0A%0A%0A%0A%0A%0A%0A%0AMeta&=F15%0A%0A%0A%0A%0A%0A%0A%0A%0AShift&=F16%0A%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=F17%0A%0A%0A%0A%0A%0A%0A%0A%0AAlt&=F18&=F19&=F20%0A%0A%0A%0A%0A%0A%0A%0A%0AAlt&=F21%0A%0A%0A%0A%0A%0A%0A%0A%0ACtrl&=F22%0A%0A%0A%0A%0A%0A%0A%0A%0AShift&=F23%0A%0A%0A%0A%0A%0A%0A%0A%0AMeta&=F24&_c=#cccccc&w:2.25;&=Enter;&@_w:2.25;&=Shift&=Z&=X&=C&=V&=B&=N&=M&=%3C%0A,&=%3E%0A.&=?%0A//&_w:2.75;&=Shift;&@_w:1.25;&=Ctrl&_w:1.25;&=Meta&_w:1.25;&=Alt&_c=#FFA500&a:7&w:6.25;&=&_c=#cccccc&a:4&w:1.25;&=Alt&_w:1.25;&=Meta&_w:1.25;&=Menu&_w:1.25;&=Ctrl)
  
![Custom layer image](images/custom.png)

Finally, this layer is intended to provide a place for shortcuts, macros, etc., that you may find useful in your own workflow.

As an example, function keys that are rarely physically present on a keyboard but generally recognized by most operating systems where distributed along the home row. Many applications will allow you to assign particular behaviours to them which can open up opportunities to simplify and speed up repetitive or frequent tasks.

## Instructions

Install one of the [supported keyboard customisation applications](#keyboard-customisation-software) and place the corresponding configuration file provided by this repository in the recommended location.

## Goal

To provide a starting point for the keyboard customization journey of those who seek to increase their productivity, and/or improve the ergonomy of their workflows, without having to spend too much money on expensive hardware or too much time doing research.

## Principles

- Seamlessness: A user that is unaware or the presence of this layout should not be able to tell it is there. 
- Progressiveness: A new user of the layout should be able to adopt the layout gradually and always have the option to fall-back to pre-existing habits if necessary.
- Composability: The layout should be built on well known patterns that can be applied together or individually.
- Efficiency: The layout should endeavour to strike a balance between the effort required for its use (i.e. hand motion) and that required to learn it (i.e., complexity).
  
## Patterns

- [Home row modifiers](https://precondition.github.io/home-row-mods)
- [Impermanent (momentary) layers](https://jonny-wamsley.gitbook.io/the-ultimate-guide-to-keyboard-layers/ch-3-layer-activators/3.3-shift-layers)
- [Layer anchoring](https://argenkiwi.medium.com/keyboard-layer-pinning-20aafede96e5)
 
## Keyboard customisation software

- [Kanata](https://github.com/jtroo/kanata)
- [Keyd](https://github.com/rvaiya/keyd)
