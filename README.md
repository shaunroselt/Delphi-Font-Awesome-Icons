# Delphi Font Awesome Icons (.SVG)

The [Font Awesome Icons library](https://fontawesome.com/icons) to use within Delphi.

<p align="center">
  <a href="https://fontawesome.com/icons">
    <img src="https://img.fortawesome.com/349cfdf6/fa-free-logo.svg" alt="Font Awesome Free" width="50%">
  </a>
</p>
<p align="center">
  Open source SVG icon library with over 2,000 icons.
</p>


[![Font Awesome Icons preview](https://github.com/shaunroselt/Delphi-Font-Awesome-Icons/assets/5418178/ba662b7d-c309-4e65-ac44-8b24a0a55bbc)](https://fontawesome.com/icons)


## Usage

### SVG Code

```pascal
uses uFontAwesomeIcons

...


var HouseIconSVG := GetFontAwesomeIcon('house'); // Returns SVG Code
var ValveSteamIconSVG := GetFontAwesomeIcon('steam'); // Returns SVG Code
var BrushIconSVG := GetFontAwesomeIcon('brush'); // Returns SVG Code

var HouseIconSVG := GetFontAwesomeIcon('house', 24); // Returns SVG Code with Width/Height set to 24
var ValveSteamIconSVG := GetFontAwesomeIcon('steam', 24); // Returns SVG Code with Width/Height set to 24
var BrushIconSVG := GetFontAwesomeIcon('brush', 24); // Returns SVG Code with Width/Height set to 24
```

### SVG Path Data

```pascal
uses uFontAwesomeIcons

...


var HouseIconSVGPathData := GetFontAwesomeIconPathData('house'); // Returns SVG Path Data Text
var ValveSteamIconSVGPathData := GetFontAwesomeIconPathData('steam'); // Returns SVG Path Data Text
var BrushIconSVGPathData := GetFontAwesomeIconPathData('brush'); // Returns SVG Path Data Text

var HouseIconSVGPathData := GetFontAwesomeIconPathData('house', 24); // Returns SVG Path Data Text with Width/Height set to 24
var ValveSteamIconSVGPathData := GetFontAwesomeIconPathData('steam', 24); // Returns SVG Path Data Text with Width/Height set to 24
var BrushIconSVGPathData := GetFontAwesomeIconPathData('brush', 24); // Returns SVG Path Data Text with Width/Height set to 24
```
Other ways to use Font Awesome Icons: [https://fontawesome.com/docs](https://fontawesome.com/docs)

## License

- Font Awesome Icons are free and open source ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).

---

## Other Delphi Icon Libraries
- [Bootstrap Icons](https://github.com/shaunroselt/Delphi-Bootstrap-Icons)
