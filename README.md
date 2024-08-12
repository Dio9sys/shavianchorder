# shavianchorder
Shavian keyboard layout for the CharaChorder

# Intro
This is a Shavian alphabet keyboard layout that I made for my CharaChorder One keyboard.  I considered trying to learn to type with the existing layouts on the charachorder and just focus on memorizing which keys go where, but that didn't feel very intentional.  Then I decided I would try making charachorder profiles to match the existing keyboard layouts.  That turned out to be wildly inefficient, requiring loading a new charachorder backup file every time you wanted to switch from latin to shavian.  Then I slapped my forward and realized that I could just make my own keyboard layout to fit the default layout of the Charachorder.  That turned out to be a lot easier to figure out!

## Layout logic
My logic for this layout is as follows:

The right hand has the tall letters on the fingers and most easy to use parts of the thumb right and up).  Hold shift the type the flipped/deep version of each tall letter.

The weird parts of the right thumb (down, left) are for the compound letters "or" and "err," with their flipped counterparts (are and air) on shift, and the palm switch is "thigh/then" and the rest of the compound letters.

On the left hand is the short letters, again using a flipping scheme where possible ("loll" and "roar," "out" vs "oil" etc) and keeping most of the individual letters on lower parts of the hand, with the exception of "eat" on the left ring finger.

The other singleton characters are down the thumb and palm switch.  I'm not totally sure what I'll put on the shift-layer of the singletons, but I may add some punctuation marks that are normally kept on a separate layer on the charachorder.

For the sake of "I don't know what these are or how to use them," I'm avoiding use of the Shavian letters introduced later in the alphabet's life.  Given my target user audience for this is approximately one person (me), I figure I can just make a new and improved version of the keyboard layout if I learn how to use the extra characters and find them to be compelling enough to go into constant use :)


# Install instructions

## Requirements
The Shavian layout was made using [Kalamine](https://github.com/OneDeadKey/kalamine).

To install this layout in X11, run the following command (requires root):
```
sudo env "PATH=$PATH" xkalamine install shavianchorder.toml
```

You can install the layout temporarily to try it out by running that command but without `sudo env "PATH=$PATH"` on the front.

# Layout

![layout made in Krita](https://github.com/Dio9sys/shavianchorder/blob/main/CCShavian.png)

# FAQs

## What is the Shavian alphabet?
The Shavian Alphabet is an alphabet made to fulfill the last will and testament of George Bernard Shaw.  Being a playwright, he felt the Latin alphabet was insufficient for writing the English language, and wrote in his will that he wanted
a new alphabet made, with the execution of this task being overseen by the son of the man who invented Pittman shorthand.  You can find more infomation about it at [shavian.info](https://www.shavian.info/), and find a quick primer on how to read Shavian at [shavian.school](https://shavian.school/?l=0).

## What is the CharaChorder?
The CharaChorder is a [weird but kind of cool keyboard](https://www.charachorder.com/), where each key is actually a 4 directional switch, intended for faster/more comfortable typing.

## Why make a Shavian layout for the Charachorder?
It seemed fun!  Every time I practice typing on the charachorder I think about how interesting it would be to type in the shavian alphabet with it.  It just feels well suited to the task, but the only way to know that for sure was to make a layout and try it out!
