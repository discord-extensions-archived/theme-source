# v2
working on v2 if anyone is reading this yes it should be better big pogs

# Theme Source (dev)
This is a WIP, don't expect everything to be themed perfectly yet (or ever). Some things may **intentionally** themed differently than the way Discord themes it, either because I thought it "looked better", I got lazy, or there was no better way I could figure out how to theme it. The main purpose of Theme Source is for new theme devs (like myself) to have easy access to changing all of Discord's base colors, since just using the :root themes part of it. I don't really recommend using this, cause there's probably better ways to do this (and this is my first attempt at themeing Discord like this), and it's better if you use your own work. You *can* use this still, I don't really reccommend it cause you're better off learning how to do it yourself. You can look at the source for help if needed. If you do use this, no need to credit.


## Issues and Pull Requests
Since this is a VIP, there are going to be issues with it. Some things may be unthemed, something may not be themed correctly (read above first), or a Discord update broke some element, who knows? If you find something along these lines, you can make an issue that points it out (screenshots if you can), or make your are welcom to make a pull request fixing said issue yourself.


## Varibles for Noobs™️
**Anything that is shown in red is what the variable changes.**


<details>
  <summary>--header-primary</summary>
Primary header text (basically most visible header text).

![](https://media.discordapp.net/attachments/761659752446689280/767957753674203146/unknown.png?width=1120&height=630)
![](https://media.discordapp.net/attachments/761659752446689280/767957832342437918/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--header-secondary</summary>
Text that is usually under --header-primary.

![](https://media.discordapp.net/attachments/761659752446689280/767958009032212500/unknown.png?width=1120&height=630)
![](https://media.discordapp.net/attachments/761659752446689280/767958062215987200/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--text-normal</summary>
Basic text elements, such as messages as well as other things.

![](https://media.discordapp.net/attachments/761659752446689280/767958461110550528/unknown.png?width=1120&height=630)
![](https://media.discordapp.net/attachments/761659752446689280/767958568627732490/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--text-muted</summary>
Text areas that are defaulted to a "muted color", usually appears in text fields.

![](https://media.discordapp.net/attachments/761659752446689280/767958862174355466/unknown.png?width=1121&height=629)
</details>


<details>
  <summary>--text-link</summary>
Links and hyperlinks.

![](https://media.discordapp.net/attachments/761659752446689280/767959535691235409/unknown.png?width=1121&height=629)
</details>


<details>
  <summary>--channels-default</summary>
Category headers.

![](https://media.discordapp.net/attachments/761659752446689280/767959748514414632/unknown.png?width=1120&height=630)
![](https://media.discordapp.net/attachments/761659752446689280/767959815418675220/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--interactive-normal</summary>
Items that can be active (that aren't already active)

![](https://media.discordapp.net/attachments/761659752446689280/767960326868041728/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--interactive-hover</summary>
Anything that is currently being hovered over.

![](https://media.discordapp.net/attachments/761659752446689280/767960844050497576/unknown.png?width=215&height=630)
</details>


<details>
  <summary>--interactive-active</summary>
Anything that is currently active (selected/clicked on).

![](https://media.discordapp.net/attachments/761659752446689280/767961120072925205/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--interactive-muted</summary>
Anything that is muted and can be interacted with.

![](https://media.discordapp.net/attachments/761659752446689280/767962218033184768/unknown.png?width=1124&height=630)
</details>


<details>
  <summary>--background-primary</summary>
ned fixies
</details>


<details>
  <summary>--background-secondary</summary>
Anything that uses --background-secondary (refer to image for best example).

![](https://media.discordapp.net/attachments/761659752446689280/767963085079314462/unknown.png?width=1105&height=630)
</details>


<details>
  <summary>--background-tertiary</summary>
Anything that uses --background-tertiary (refer to image for best example).

![](https://media.discordapp.net/attachments/761659752446689280/767963402889854976/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--background-accent</summary>
Accent color, idk how to explain this one.

![](https://media.discordapp.net/attachments/761659752446689280/767963971864887306/unknown.png)
</details>


<details>
  <summary>--background-floating</summary>
The color for all floating related elements.

![](https://media.discordapp.net/attachments/761659752446689280/767964336995303424/unknown.png)
![](https://media.discordapp.net/attachments/761659752446689280/767964458470866954/unknown.png)
</details>


<details>
  <summary>--background-modifier-hover</summary>
Hovering on something selectable.

![](https://snapper.is-a-virg.in/3g23q1.gif)
</details>


<details>
  <summary>--background-modifier-active</summary>
Items that are hovered but differnet.

![](https://media.discordapp.net/attachments/761659752446689280/767965907581927434/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--background-modifier-selected</summary>
Items that are selected/active but differnet.

![](https://media.discordapp.net/attachments/761659752446689280/767966285694369792/unknown.png?width=1121&height=629)
</details>


<details>
  <summary>--background-modifier-accent</summary>
Separators (aka the lines that appear separating things).

![](https://media.discordapp.net/attachments/761659752446689280/767966654046011443/unknown.png?width=1120&height=630)
![](https://media.discordapp.net/attachments/761659752446689280/767966707087835186/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--elevation-low</summary>
Changes **this** line, supposed to be coded as 

```css
--elevation-low: 0 1px 0 rgba(4, 4, 5, 0.2), 0 1.5px 0 rgba(6, 6, 7, 0.05), 0 2px 0 rgba(4, 4, 5, 0.05); /* replace colors */
```

![](https://media.discordapp.net/attachments/761659752446689280/767967924379320331/unknown.png?width=1120&height=630)
</details>


<details>
  <summary>--elevation-high</summary>
The drop shadow that appears behind certain modals.

![](https://media.discordapp.net/attachments/761659752446689280/767968776049393704/unknown.png?width=1120&height=630)
</details>

# Credits
ty Snapperito for making the varaibles information thing
