<p align="center">
  <img src="logo.png" title="JuNe CSS" width="274" height="194">
</p>

# [JuNe CSS](https://github.com/EduardoRuizM/june-css "JuNe CSS")
JuNe CSS is a complete and minified Cascading Style Sheets with everything you need to format the layout of a responsive webpage, in just 14 Kb (Bootstrap with 262 Kb).

✔ Responsive for mobile / tablets / desktop.

✔ Dark and Light mode.

✔ Responsive tables.

✔ Desktop menu.

✔ Hamburger menu.

✔ ToolTipTexts, Badges.

✔ Switches with unicode characters.

✔ Loaders.

✔ Designed for users with presbyopia.

✔ Version with [Font Awesome](https://fontawesome.com "Font Awesome")

![14 Kb](https://img.shields.io/github/size/EduardoRuizM/june-css/june-css.css)

### 👉 Try JavaScript framework for frontend [JuNe PaulaJS](https://github.com/EduardoRuizM/june-paulajs "JuNe PaulaJS")

# Author
[Eduardo Ruiz](https://github.com/EduardoRuizM) <<eruiz@dataclick.es>>

# JuNe / JUst NEeded Philosophy
1. **Source code using less code as possible**
  So you can understand code and find bugs easier.
2. **Few and optimized lines is better**
  Elegant design.
3. **Avoid external dependencies abuse/bloated, and possible third-party bugs**
  Less files size, better and faster to the interpreter.
4. **Clear and useful documentation with examples and without verbose**
  Get to the point.
5. **Avoid showing unsolicited popups, notifications or messages in frontend**
  For better User eXperience.
6. **Simple UI**, without many menus/options and with few clicks to get to sites.
7. Consequences of having a lot of code (and for simple things): Having to work and search through many files and folders with a lot of wasted time, successive errors due to missing unknown files, madness to move a code to another project, errors due to recursive dependencies difficult to locate, complexity or impossibility to migrate to new versions, unfeasibility to follow the trace with so much code, risk of new errors if the functionality is extended, problems not seen at the first sight, general slowness in the whole development due to excessive and unnecessary code.

# Variables
Prefixed custom properties / variables with **--jc** (JuNe CSS).
You can change your corporative (dark) color **jcbtheme**, and your custom font.
- **Light**: means a bright color.
- **Dark**: means a darker color.
- Combination of foreground/background with light/dark or dark/light must be readable/legible.

| Name | ☀️Light/🌑Dark | Default | Definition | With text |
| --- | :---: | --- | --- | :---: |
| **jcfnt** | - | sansserif | Font family used | - |
| **jcfntsize** | - | .9em | Font size | - |
| **jcfntszes** | - | .7em | Font size small | - |
| **jcclr** | 🌑Dark | ![#333](https://placehold.co/15x15/333/333.png) `#333` | Color for foreground | ![](https://placehold.co/50x20/fff/333.png) |
| **jcbg** | ☀️Light | ![#fff](https://placehold.co/15x15/fff/fff.png) `#fff` | Color for background | ![](https://placehold.co/50x20/fff/333.png) |
| **jcclight** | ☀️Light | ![#fff](https://placehold.co/15x15/fff/fff.png) `#fff` | Color for foreground | ![](https://placehold.co/50x20/222/fff.png) |
| **jcbglight** | 🌑Dark | ![#222](https://placehold.co/15x15/222/222.png) `#222` | Color for background | ![](https://placehold.co/50x20/222/fff.png) |
| **jcbbclr** | 🌑Dark | ![#fff](https://placehold.co/15x15/fff/fff.png) `#fff` | Color for button/foreground | - |
| **jcbtheme** | ☀️Light | ![#fea700](https://placehold.co/15x15/fea700/fea700.png) `#fea700` | Corporative color for button/background | ![](https://placehold.co/50x20/fea700/fff.png) |
| **jcbblue** | ☀️Light | ![#07c](https://placehold.co/15x15/07c/07c.png) `#07c` | Blue color for button/background | ![](https://placehold.co/50x20/07c/fff.png) |
| **jcbred** | ☀️Light | ![#d33](https://placehold.co/15x15/d33/d33.png) `#d33` | Red color for button/background | ![](https://placehold.co/50x20/d33/fff.png) |
| **jcbgreen** | ☀️Light | ![#490](https://placehold.co/15x15/490/490.png) `#490` | Green color for button/background | ![](https://placehold.co/50x20/490/fff.png) |
| **jcbgray** | ☀️Light | ![#777](https://placehold.co/15x15/777/777.png) `#777` | Gray color for button/background | ![](https://placehold.co/50x20/777/fff.png) |
| **jcbblack** | ☀️Light | ![#000](https://placehold.co/15x15/000/000.png) `#000` | Black color for button/background | ![](https://placehold.co/50x20/000/fff.png) |
| **jcbglighto** | 🌑Dark | ![#ccc](https://placehold.co/15x15/ccc/ccc.png) `#00000008` | Black color button/background with opacity | ![](https://placehold.co/50x20/ccc/fff.png) |

- **jcclr + jcbg**: are used to main color and backgrounds (light).
- **jcclight + jcbglight**: are used as reversed main color and backgrounds (dark) for headers/footers.
- **jcbbclr + (jcbtheme, jcbblue, jcbgreen...)**: are used for buttons and backgrounds (dark).

## 🌑 Dark mode
Main color and background are reversed, and the (visuality) meaning changes: light is dark and dark is light.

| Name | 🌑Light/☀️Dark | Default | Definition | With text |
| --- | :---: | --- | --- | :---: |
| **jcclr** | ☀️Dark | ![#fff](https://placehold.co/15x15/fff/fff.png) `#fff` | Color for foreground | ![](https://placehold.co/50x20/222/fff.png) |
| **jcbg** | 🌑Light | ![#222](https://placehold.co/15x15/222/222.png) `#222` | Color for background | ![](https://placehold.co/50x20/222/fff.png) |
| **jcclight** | 🌑Light | ![#333](https://placehold.co/15x15/333/333.png) `#333` | Color for foreground | ![](https://placehold.co/50x20/fff/333.png) |
| **jcbglight** | ☀️Dark | ![#fff](https://placehold.co/15x15/fff/fff.png) `#fff` | Color for background | ![](https://placehold.co/50x20/fff/333.png) |

# 🎨 Styles
For HTMLElements or to use as a class.

| Class | Element | Definition | Used | Sample |
| --- | --- | --- | --- | :---: |
| - | body | Background ☀️light | jcbg | ![](https://placehold.co/50x20/fff/fff.png) |
| **.bgd** | - | Text and background 🌑dark | jcbbclr, #333 | ![](https://placehold.co/50x20/333/fff.png) |
| - | img | Ready for responsive, so don´t specify width/height | - | - |
| - | header | Top header position | - | - |
| **.fg** | body, div, td, input, button, textarea, select, option | Color, font and size | jcclr, jcfnt, jcfntsize | ![](https://placehold.co/50x20/fff/333.png) |
| **.lnk** | a | Links for ☀️light backgrounds, brighter on hover | jcbtheme | ![](https://placehold.co/50x20/fff/fea700.png) |
| **.dlnk** | - | Links for 🌑dark backgrounds, darker on hover | jcbtheme, jcbtheme+#fff | ![](https://placehold.co/50x20/ffc720/fea700.png) |
| **.tlnk** | - | Links for theme backgrounds | jcbglight, jcclight | ![](https://placehold.co/50x20/fea700/fff.png) |
| **.txt** | select | For inputs and selects, theme on hover | - | ![](https://placehold.co/50x20/fff/333.png) |
| - | option | For options | jcclr, jcbg | - |
| - | textarea | *resize: none* | - | - |
| **.ib** | - | *display: inline-block* | - | - |
| **.cp** | - | *cursor: pointer* | - | - |
| **.fw** | - | Full width *width: 100%* | - | - |
| **.lh** | - | Line height (font-size + 6px) | - | - |
| **.sm** | - | Small font | jcfntszes | - |
| **.fb** | - | Font Bold | - | - |
| **.fi** | - | Font Italic | - | - |
| **.tl** | - | *text-align: left* | - | - |
| **.tc** | - | *text-align: center* | - | - |
| **.tj** | - | *text-align: justify* | - | - |
| **.tr** | - | *text-align: right* | - | - |
| **.vt** | - | *vertical-align: top* | - | - |
| **.vm** | - | *vertical-align: middle* | - | - |
| **.vb** | - | *vertical-align: bottom* | - | - |
| **.ov** | - | Oval | - | - |
| **.oscr** | - | Allow scroll on touch | - | - |
| **.ellp** | - | Show ellipsis on text overflow | - | - |
| **.selelm:hover** | ::selection | Text selection | jcclight, jcbtheme | ![](https://placehold.co/50x20/fea700/fff.png) |
| **.main** | - | Page content for bottom | - | - |
| **.button** | - | Buttons (standard) | jcbtheme | ![](https://placehold.co/50x20/fea700/fff.png) |
| **.disabled<br>.button/txt:disabled** | (select/textarea/:disabled) | Disabled elements | - | - |
| **.readonly<br>.txt:read-only** | (select/textarea/:read-only) | Readonly elements | - | - |
| **.theme** | - | Theme background | jcbbclr, jcbtheme | ![](https://placehold.co/50x20/fea700/fff.png) |
| **.blue** | - | Blue background | jcbbclr, jcbblue | ![](https://placehold.co/50x20/07c/fff.png) |
| **.red** | - | Red background | jcbbclr, jcbred | ![](https://placehold.co/50x20/d33/fff.png) |
| **.green** | - | Green background | jcbbclr, jcbgreen | ![](https://placehold.co/50x20/490/fff.png) |
| **.gray** | - | Gray background | jcbbclr, jcbgray | ![](https://placehold.co/50x20/777/fff.png) |
| **.black** | - | Black background | jcbbclr, jcbblack | ![](https://placehold.co/50x20/000/fff.png) |
| **.req** | - | Required field label | jcbred | - |
| **.txtgrp** | - | Group for inputs | - | - |
| **.switch** | - | Swich for checkboxes | jcbtheme | - |
| **.nosel** | - | No selectable | - | - |
| **.noprint** | - | No visible on print | - | - |
| **.rtbl** | - | Responsive tables | - | - |
| **.box** | - | Boxes | - | - |
| **.boxlnk** | - | Boxes scale | jcbtheme | - |
| **.shake** | - | Shake effect | - | - |
| **.loader1** | - | Loader1 | - | - |
| **.loader2** | - | Loader2 | - | - |
| **.menu** | - | Desktop menu | jcbbclr, jcbtheme | - |
| **#menuToggle** | - | Hamburger menu | jcbbclr, jcbtheme | - |

# ⋯ Menu
Navigation desktop menu, have a look to HTML code in `sample.html`
You could add `class="mobn"` to the div to show it only on desktops.

# ≡ Hamburger menu
Navigation hamburger menu, have a look to HTML code in `sample.html`
You could add `class="moby"` to the div to show it only on mobiles/tablets.

# ⊞ Responsive tables
Using `data-cn` to show column name on the left in small portrait orientation.
```
<table class="rtbl">
  <thead>
    <tr>
      <th>Title1</th>
      <th>Title2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td data-cn="Title1">Value1</td>
      <td data-cn="Title2">Value2</td>
    </tr>
  </tbody>
</table>
```

# 🏷 ToolTipTexts
Just add dataset `data-tooltip` with text, sample `<span data-tooltip="Hello">I have tip</span>`

# ❶ Badges
Just add dataset `data-badge` with text, optional colors in style, *badgefg* for foregroud (default *jcclight*), and *badgebg* for background (default *jcbtheme*).
`<span data-badge="2">Badge sample</span>`
`<span data-badge="88" style="--badgefg: var(--jcclr); --badgebg: var(--jcbgray)>Badge change colors</span>`

# ↺ Loaders
Default size `40px` change with `<i style="--size: 60px" class="loader1"></i>`

# 🌓 Manual change Dark/Light mode
Use `colorScheme()` and `window.onload` functions, value in localStorage to remember decission.
`sample.html` includes JavaScript functions to enable system default dark mode, or force dark mode, decission is stored and if user selects current mode then default mode will be system default, so checked status will change on system colors changes with matchMedia listener.

# Switches
Use `--checked` and `--unchecked` styles to add an unicoche character, `--top` for relative top unicode position.
Sample with ✔️❌ `<input type="checkbox" class="switch" checked style="--checked: '\2714\FE0F'; --unchecked: '\274C'">`

# ↭ Shake (to notify troubles)
Use and export function `shake(o)` where `o` is the object to shake, sample `<div onclick="shake(this)">Click here</div>`

# Styles for responsive
Visible for 🖥️Desktop or 📱Mobile/Tablets.

**.mob[y(es)|n(o)][|b(lock)]** to show or hide, treated as block or inline and according if mobile/tablets or desktop.

| Class | Definition | 🖥️ | 📱 |
| --- | --- | :---: | :---: |
| **.moby** | Display inline only on mobiles/tablets | ❌ | ✅ |
| **.mobyb** | Display block only on mobiles/tablets | ❌ | ✅ |
| **.mobn** | Display inline-block only on desktop | ✅ | ❌ |
| **.mobnb** | Display block only on desktop | ✅ | ❌ |
| **.cards** | Individual line | 100% | 100% |
| **.card10** | Column 10% | 10% | 100% |
| **.card20** | Column 20% | 20% | 100% |
| **.card25** | Column 25% | 25% | 100% |
| **.card33** | Column 33% | 33% | 100% |
| **.card40** | Column 40% | 40% | 100% |
| **.card50** | Column 50% | 50% | 100% |
| **.card60** | Column 60% | 60% | 100% |
| **.card75** | Column 75% | 75% | 100% |
| **.card80** | Column 80% | 80% | 100% |
| **.card90** | Column 90% | 90% | 100% |
| **.card100** | Column 100% | 100% | 100% |

- Easy to build a responsive design, just fill up to 100% by adding columns.
- ‼️Don´t space between divs or fail.
- Sample line with 3 columns (50% + 25% + 25%):

```
<!-- No spaces between cards </div><div...> -->
<div class="cards">
	<div class="cards50">Half screen</div><div class="cards25">
		First quarter</div><div class="cards25">
		Second quarter</div>
</div>
```

# Icons from [Font Awesome](https://fontawesome.com "Font Awesome")
- Add this icon library and it´s dependencies (suchs as fonts/fa-\*.woff2).
- Only for **Solid and Brands** family/styles.

# CSS for [JuNe PaulaJS](https://github.com/EduardoRuizM/june-paulajs "JuNe PaulaJS")
- Customize your own styles for modal windows and toast notifications adding:
- **wincssbg**: Modal windows background.
- **wincssfg**: Modal windows foreground.
- **toastcss**: Toast notifications.

```
.wincssbg {
	background: rgba(255, 255, 255, 0.83);
	backdrop-filter: blur(2px);
	transition: .5s ease;
}
.wincssfg {
	margin: auto;
	padding: 8px;
	text-align: center;
	border-radius: 6px;
	background: var(--jcbg);
	box-shadow: 1px 1px 10px #444;
	transform: scale(1.4);
	transition: .3s ease;
	div {
		color: var(--jcclr);
		line-height: 1.7em;
	}
}
.toastcss {
	width: 80%;
	left: 10%;
	right: 10%;
	padding: 7px 9px 20px;
	text-align: center;
	border-radius: 6px;
	box-shadow: 1px 1px 10px #CCC;
	color: #FFF;
	background: rgba(0,0,0,0.83);
	backdrop-filter: blur(2px);
	transition: .3s ease;
}
```
- Add class names to **JuNe PaulaJS** `main.js` in `data` array objects:
  - `winCSSbg: 'wincssbg'`
  - `winCSSfg: 'wincssfg'`
  - `toastCSS: 'toastcss'`

## Inline Styles
**There is no problem in using inline styles.**
It is not a bad practice even if you read wrong about it.
In many occasions it´s the best option for small styles.
That way they are located in their HTMLElement, and so the style file does not grow, nor is it necessary to create a class for individual single-use styles.
It also improves the visualization since the style is applied instantly without having to wait for the CSS to load.
**Really the bad practice is to create a large and unoptimized style file, with unused classes, that is difficult to manage, hard to find anything and takes longer to load.**

For best image/iframe loading performance when it´s possible to show in a visible window area, add loading tag `<img src="..." loading="lazy">`

## Minimum changes
In most cases you may only need to change the theme color, so just add it after the CSS:
```
<style>
:root {
	--jcbtheme:	#FEA700;
}
</style>

```
Or using JS on window load:
```
document.documentElement.style.setProperty('--jcbtheme', '#FEA700');

```

## 👓 Clear and legible styles and easy to click on them
### Presbyopia
Do not use small styles and keep in mind that **presbyopia** begins at age 40, that is 26% of world´s population (1.8 billion) and more than 80% in adults. 👥Think of everyone.
JuNe CSS is designed for presbyopia people, avoiding small designs and using high contrast.
Also spacing of elements for easy clicking on touch devices and to facilitate people with disabilities.

# Installation
- Choose the CSS file you need and fonts files required (and create `fonts/` folder in your project).
- Add to your HTML head project with `<link rel="stylesheet" href="/june-css.min.css">`
- Remember to change `fonts/` path if you prefer another location (recommended absolute paths / ).
- Change your corporative/main color in `jcbtheme` (default orange #fea700).
- Change `sansserif` font if you prefer other font and adjust `--jcfnt` name, and `@font-face family / src` path.
- Only **woff2** (Web Open Font Format) is needed by browsers nowadays.
  TTF (or OTF) to WOFF2 converters: [cloudconvert](https://cloudconvert.com/ttf-to-woff2 "cloudconvert"), [Everything Fonts](https://everythingfonts.com/ttf-to-woff2 "Everything Fonts") or [fontConverter](https://www.fontconverter.io/en/ttf-to-woff2 "fontConverter").
- Keep in mind to choose a font that includes accents or characters for other languages.
- You can download this repository to see sample/template in file `sample.html`

| File | Size | Font(s) to include | Definition |
| --- | ---: | --- | --- | --- |
| june-css.css | 15 Kb | fonts/sansserif.woff2 | Version without Font Awesome |
| june-css.min.css | 11 Kb | fonts/sansserif.woff2 | Minified version without Font Awesome |
| june-cssfa.css | 85 Kb | fonts/\* | Version with Font Awesome (minified) |
| june-cssfa.min.css | 82 Kb | fonts/\* | Minified version with Font Awesome |

# JuNe Development Ecosystem
Everything you need to develop your project:
### Backend
- [JuNe BackServer](https://github.com/EduardoRuizM/june-backserver "JuNe BackServer") With request routing, tokens, file upload, send Emails, WebSockets, SSE and captcha.
- [JuNe WebServer](https://github.com/EduardoRuizM/june-webserver "JuNe WebServer") Web server with HMR.

### Frontend
- [JuNe PaulaJS](https://github.com/EduardoRuizM/june-paulajs "JuNe PaulaJS") Powerful JavaScript framework
- [JuNe CSS](https://github.com/EduardoRuizM/june-css "JuNe CSS") Full responsive CSS library with icons.
