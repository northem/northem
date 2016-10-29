<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-logo-banner.svg"/></p>

<p align="center"><img src="https://cdn.travis-ci.org/images/favicon-c566132d45ab1a9bcae64d8d90e4378a.svg" width=24 height=24/> <a href="https://travis-ci.org/arcticicestudio/northem"><img src="https://img.shields.io/travis/arcticicestudio/northem/develop.svg"/></a> <img src="https://circleci.com/favicon.ico" width=24 height=24/> <a href="https://circleci.com/gh/arcticicestudio/northem"><img src="https://circleci.com/gh/arcticicestudio/northem.svg?style=shield&circle-token=92271cf2d75a645cca8fc551387b4f775c41438a"/></a> <img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/northem/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/northem.svg"/></a> <a href="https://github.com/arcticicestudio/northem/releases/latest"><img src="https://img.shields.io/badge/pre--release---_-blue.svg"/></a></p>

<p align="center">A north-bluish, dark color palette.</p>

<p align="center">Created for the clean- and minimal flat design pattern to achieve a optimal focus and readability for code syntax highlighting and UI.
It consists of a total of sixteen, carefully selected, dimmed pastel colors for a eye-comfortable, but yet colorful ambiance.</p>

---

The color palette it divided into four named components to represent the different color effects.

![Northem Palette Overview](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-overview.svg)

Northem colors are numbered from `northem0` to `northem15` where each component contains a different amount of colors:  
  1. **Dark Water** `northem0` - `northem3`  
  2. **Light Wind** `northem4` - `northem6`  
  3. **Ice** `northem7` - `northem10`  
  4. **Rainbow** `northem11` - `northem15`  

This naming convention allows an uncomplicated use for terminals and preserves the compatibility to similar projects like [base16](http://chriskempson.com/projects/base16).

## Usage
To show a list of all available [Gulp][gulp] tasks run `gulp` or `gulp help`.

### CSS
The [CSS specification](https://www.w3.org/TR/css-variables) supports the usage of primitive value types to define custom properties which can be used to create e.g. color variables.  
Northem provides the `template-css.scss` template file to compile a `northem.css` stylesheet.

The generated file contains all Northem color variables prefixed with `--` inside the `:root` pseudo-class.  
The `:root` pseudo-class represents an element that is the root of the document.  
This is always the HTML (`<html>`) element which allows to use the Northem color variables for the whole document.

The `northem.css` stylesheet can be compiled via [Gulp][gulp]:  
```sh
npm install
gulp compile-css-template
```

### <img src="http://sass-lang.com/favicon.ico" width=16 height=16 /> Sass
Copy the `northem.scss` file into your project and import it in your [Sass](http://sass-lang.com) files:
```css
@import "northem";
```
The `.scss` file extension is optional.

#### <img src="http://sassdoc.com/favicon.png" width=16 height=16 /> SassDoc
Northem Sass sources are documented using the [SassDoc](http://sassdoc.com) documentation syntax which can be compiled to a HTML documentation via [Gulp][gulp]:  
```sh
npm install
gulp sassdoc
```
The Sassdoc theme can be changed by editing the `.sassdocrc` configuration file.

### <img src="http://lesscss.org/public/ico/favicon.ico" width=16 height=16/> LESSCSS
Copy the `northem.less` file into your project and import it in your [LESSCSS](http://lesscss.org) files:  
```css
@import "northem";
```
Information about how the `@import` statement handles imports with different file extensions can be found in the [official LESSCSS documentation](http://lesscss.org/features/#import-directives-feature).

#### KSS
Northem LESSCSS sources are documented using the [KSS](http://warpspire.com/kss) documentation syntax.  
Information about the generation of a styleguide can be found in the [official KSS documentation](http://warpspire.com/kss/styleguides).

### <img src="https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/icon-color-swatch.svg"/> Color Swatches
Northem is available in various native formats:
  - `.aco` Adobe Photoshop Palette
  - `.ase` Adobe Swatch Exchange
  - `.gpa` Gpick Palette
  - `.gpl` GIMP/Inkscape/CinePaint/Krita Palette
  - `.mtl` Alias/WaveFront Material

A list of detailed information about each file format can be found [here](http://www.selapa.net/swatches/colors/fileformats.php).

## Projects
[![Northem Atom Syntax](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-atom-syntax-banner.svg)](https://atom.io/themes/northem-atom-syntax)  
[![Northem Atom UI](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-atom-ui-banner.svg)](https://atom.io/themes/northem-atom-ui)  
[![Northem Eclipse Syntax](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-eclipse-syntax-banner.svg)](https://github.com/arcticicestudio/northem-eclipse-syntax)  
[![Northem IntelliJ IDEA Syntax](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-intellij-idea-syntax-banner.svg)](https://github.com/arcticicestudio/northem-intellij-idea-syntax)  
[![Northem Java](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-java-banner.svg)](https://github.com/arcticicestudio/northem-java)  
[![Northem Notepad++](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-notepadplusplus-banner.svg)](https://github.com/arcticicestudio/northem-notepadplusplus)  
[![Northem Terminix](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-terminix-banner.svg)](https://github.com/arcticicestudio/northem-terminix)  
[![Northem Vim](https://cdn.rawgit.com/arcticicestudio/northem/develop/src/assets/northem-vim-banner.svg)](https://github.com/arcticicestudio/northem-vim)  

## Development
[![](https://img.shields.io/badge/Changelog-2.0.0-blue.svg)](https://github.com/arcticicestudio/northem/blob/v2.0.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow_Branching_Model-blue.svg)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-blue.svg)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/northem/issues).

<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/banner-footer-mountains.svg" /></p>

<p align="center"> <img src="http://arcticicestudio.com/favicon.ico" width=16 height=16/> Copyright &copy; 2016 Arctic Ice Studio</p>

<p align="center"><a href="http://www.apache.org/licenses/LICENSE-2.0"><img src="https://img.shields.io/badge/License-Apache_2.0-blue.svg"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-blue.svg"/></a></p>

[gulp]: http://gulpjs.com
