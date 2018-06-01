# [PREVIEW]

# FAQ

## "How can I use it"?
- install conky with *lua-cairo* support (if you use [Gentoo-like] distro it will be [USE_FLAG]="lua-cairo")
- if your conky version is older than 1.10 use files from [pre-1.10] branch
- copy *.conkyrc* into your home dir (eg. '/home/mrl5/')
- copy *draw_bg.lua* into your '~/.config/' dir (eg. '/home/mrl5/.config/')
- run 'conky' in your console

## "I don't want to run conky in my console everytime I boot"
- I recommend adding conky to the autostart of your graphical environment (eg. LXDE, KDE, GNOME, XFCE)
- For more info search for "conky autostart **<your graphical env>**"

## "I don't want to keep *draw_bg.lua* in '~/.config/'"
- you can keep it wherever you want, but make sure to change *lua_load* parameter in *.conkyrc* (line 40)

## "Why you have two branches"
- conky config [syntax changed] since *1.10* version


[USE_FLAG]: https://wiki.gentoo.org/wiki/USE_flag
[Gentoo-like]: https://wiki.gentoo.org/wiki/Distributions_based_on_Gentoo
[syntax changed]: https://github.com/brndnmtthws/conky/wiki/Convert-to-new-1.10-syntax
[PREVIEW]: https://raw.githubusercontent.com/mrl5/conky-config/master/mrl5-conky.png
[pre-1.10]: https://github.com/mrl5/conky-config/tree/pre-1.10
