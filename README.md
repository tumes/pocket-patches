# pocket-patches

## A short intro

I know almost nothing about what I'm doing -- I am a programmer, however, I am
definitely not familiar with programming for the Gameboy. As such, I decided to
take a swing at patching ROMs I'm interested in to play on the Analogue Pocket.
Any and all help and suggestions are welcome, since I am learning the ropes as I
go.

## Kaeru no Tame ni Kane wa Naru (English patch)

Update: I've somewhat resolved these issues. I think title screen is good or
very close. Sprite no longer messes up the info bar, but it is z-indexed wrong
(shows up over the bar instead of being hidden by it). And the pause transition
is _almost_ right (some sprites get messed up on part of the intro).

This converts `Kaeru no Tame ni Kane wa Naru (English v1.0)` to the `.pocket`
format.

The following is broken, I will continue to work on it but will gladly welcome
any suggestions from people more experienced in the scene than I am, because I
have no idea what I'm doing.

- Top and bottom of main menu are cut off.
- Character info bar shows incorrect tiles when a sprite crosses it.
- Pause menu screen transition is janky.

Rom MD5: `4ebe14c4c51555908c0e4cabb66dc813`

You can [download the Analogue Pocket IPS patch here](https://github.com/tumes/pocket-patches/blob/main/KaerunoTameniKanewaNaru.ips).
