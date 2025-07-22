# Gist Color Theme
[![Marketplace](https://img.shields.io/visual-studio-marketplace/v/gist.gist-theme)](https://marketplace.visualstudio.com/items/gist.gist-theme)
[![Installs](https://img.shields.io/visual-studio-marketplace/i/gist.gist-theme)](https://marketplace.visualstudio.com/items/gist.gist-theme)

Dark color theme designed to focus on the most important code entities<br />
Syntax highlighting follows the concept of temperature/stability:<br />
- Functions - hot but fairly stable, since most of what happens in the code is calling them, and it's known what they are and what they do, so their color is red-orange, the color of red giants
- Parameters - hot because they are passed along with function calls and will definitely be used, unstable because they are changeable by nature and their possible values cannot be seen from the function scope, so their color is very hot yellow
- Variables and properties of objects - the most common entities, they can be of various natures, including being quite stable or controlled by the parent object, and not always used. This makes them regular and often slightly cold, so their color is bluish white
- Local variables - quite hot by usage, volatility and temporariness, similar to parameters, but more stable, as their possible values often can be tracked in the current scope, so their color is a warm, slightly yellowish white
- Constants - coldest and most stable, as they are unchangeable, have a cold blue color
- Keywords, control keywords, types - have standard colors from VS Code Dark theme
- Punctuation and operators are darkened
- Tested on TypeScript. Post an issue for your language, if any

<br />

[![](https://raw.githubusercontent.com/n-gist/n-gist.github.io/master/images/VsCodeTheme_1.png)](https://raw.githubusercontent.com/n-gist/n-gist.github.io/master/images/VsCodeTheme_1.png)

<br/>

[![](https://raw.githubusercontent.com/n-gist/n-gist.github.io/master/images/VsCodeTheme_2.png)](https://raw.githubusercontent.com/n-gist/n-gist.github.io/master/images/VsCodeTheme_2.png)

<br/>

[![](https://raw.githubusercontent.com/n-gist/n-gist.github.io/master/images/VsCodeTheme_3.png)](https://raw.githubusercontent.com/n-gist/n-gist.github.io/master/images/VsCodeTheme_3.png)