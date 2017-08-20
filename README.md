# Animate.css Development Toolkit

**Now Updated for 3.5.21 release**

This extension for Visual Studio Code adds snippets for Animate.css. More Snippets will be coming soon just release.

![Use Extension](https://github.com/hridoy/animate.css-vscode/raw/master/img/preview.gif)


## Contributors

<!-- Contributors table start -->
[![Hridoy](https://avatars.githubusercontent.com/hridoy?s=100)<br /><sub>Hridoy</sub>](http://github.com/hridoy)<br />

<!-- Contributors table END -->
See the [CHANGELOG](https://github.com/hridoy/r-development-vscode/master/CHANGELOG.md) for the latest changes



## Usage
`animatecss-` followed by an animation name as listed on  [Animate.css](https://daneden.github.io/animate.css/ "Animate.css"). 


```
animatecss-bounceOutDown
```
Will generate: 
```css
@-webkit-keyframes bounceOutDown {
  0% {
    -webkit-transform: translateY(0);
    transform: translateY(0);
  }

  20% {
    opacity: 1;
    -webkit-transform: translateY(-20px);
    transform: translateY(-20px);
  }

  100% {
    opacity: 0;
    -webkit-transform: translateY(2000px);
    transform: translateY(2000px);
  }
}

...

.bounceOutDown {
  -webkit-animation-name: bounceOutDown;
  animation-name: bounceOutDown;
}
```



## Installation

1. Install Visual Studio Code 1.10.0 or higher
2. Launch Code
3. From the command palette `Ctrl`-`Shift`-`P` (Windows, Linux) or `Cmd`-`Shift`-`P` (OSX)
4. Select `Install Extension`
5. Choose the extension
6. Reload Visual Studio Code
