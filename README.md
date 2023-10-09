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

// Returns SVG Code:
var HouseIconSVG := GetFontAwesomeIcon('house');
var ValveSteamIconSVG := GetFontAwesomeIcon('steam');
var BrushIconSVG := GetFontAwesomeIcon('brush');

// Returns SVG Code with Width/Height set to 24:
var HouseIconSVG := GetFontAwesomeIcon('house', 24); 
var ValveSteamIconSVG := GetFontAwesomeIcon('steam', 24);
var BrushIconSVG := GetFontAwesomeIcon('brush', 24);

// Returns SVG Code with Width/Height set to 24 and color set to purple (#800080):
var HouseIconSVG := GetFontAwesomeIcon('house', 24, 'purple'); 
var ValveSteamIconSVG := GetFontAwesomeIcon('steam', 24, '#800080');
var BrushIconSVG := GetFontAwesomeIcon('brush', 24, 'purple');
```

### SVG Path Data

```pascal
uses uFontAwesomeIcons

...

// Returns SVG Code:
var HouseIconSVG := GetFontAwesomeIconPathData('house');
var ValveSteamIconSVG := GetFontAwesomeIconPathData('steam');
var BrushIconSVG := GetFontAwesomeIconPathData('brush');

// Returns SVG Code with Width/Height set to 24:
var HouseIconSVG := GetFontAwesomeIconPathData('house', 24); 
var ValveSteamIconSVG := GetFontAwesomeIconPathData('steam', 24);
var BrushIconSVG := GetFontAwesomeIconPathData('brush', 24);

// Returns SVG Code with Width/Height set to 24 and color set to purple (#800080):
var HouseIconSVG := GetFontAwesomeIconPathData('house', 24, 'purple'); 
var ValveSteamIconSVG := GetFontAwesomeIconPathData('steam', 24, '#800080');
var BrushIconSVG := GetFontAwesomeIconPathData('brush', 24, 'purple');
```

### SVG Base64 Image

```pascal
uses uFontAwesomeIcons

...

// Returns SVG Base64 Image:
var HouseIconSVGBase64 := GetFontAwesomeIconBase64('house');
var ValveSteamIconSVGBase64 := GetFontAwesomeIconBase64('steam');
var BrushIconSVGBase64 := GetFontAwesomeIconBase64('brush');

// Returns SVG Base64 Image with Width/Height set to 24:
var HouseIconSVGBase64 := GetFontAwesomeIconBase64('house', 24); 
var ValveSteamIconSVGBase64 := GetFontAwesomeIconBase64('steam', 24);
var BrushIconSVGBase64 := GetFontAwesomeIconBase64('brush', 24);

// Returns SVG Base64 Image with Width/Height set to 24 and color set to purple (#800080):
var HouseIconSVGBase64 := GetFontAwesomeIconBase64('house', 24, 'purple'); 
var ValveSteamIconSVGBase64 := GetFontAwesomeIconBase64('steam', 24, '#800080');
var BrushIconSVGBase64 := GetFontAwesomeIconBase64('brush', 24, 'purple');
```

Other ways to use Font Awesome Icons: [https://fontawesome.com/docs](https://fontawesome.com/docs)

## License

- Font Awesome Icons are free and open source ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).

---

## Other Delphi Icon Libraries
- [Bootstrap Icons](https://github.com/shaunroselt/Delphi-Bootstrap-Icons)
