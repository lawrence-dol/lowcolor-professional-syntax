# Just-right Latte Syntax Theme

A minimal, subdued syntax theme -- brown/gold on a black background. It is designed to focus attention on the code while pushing the secondary elements like comments & punctuation into the background without being too busy.

This theme takes the approach that less (color) is more (effective), seeking to distinguish only the most significant, high-level elements of a program. The reasoning applied is that reading and comprehension of the code is paramount -- which means colors should be used sparingly and that the palette should consist of complimentary shades & colors.

Examples of elements which are differentiated are:

  - **Code:**   primary text, literal values, comments, operators/brackets, compiler/preprocessor directives.
  - **CSS:**    tag selectors, class selectors, id selectors, pseudo-elements, keywords, literal values.
  - **Markup:** tags, attributes & values, content text.

The primary coloring of the theme is governed by just a few color settings in `syntax-variables.less`. I've chosen a soft, warm color, but a cool blue base works really well too. If you fork this theme just to alter the basic palette I suggest you also name your theme `justright-xxx-syntax` -- the intention is that the "justright" refers to the amount of coloring (or lack thereof) and it would be helpful to group themes based on this framework together.

````
@syntax-text-color                      : lighten(@brown,33%);                                                          // The primary pallette color (default text color).
@syntax-text-color-high                 : lighten(@syntax-text-color,15%);                                              // non-standard
@syntax-text-color-low1                 : darken( @syntax-text-color,17%);                                              // non-standard
@syntax-text-color-low2                 : darken( @syntax-text-color,33%);                                              // non-standard
@syntax-background-color                : @black;
````

When I am confident that the theme is stable, it will be updated to 1.0.0 and published to Atom's repository.

## Screenshots

#### HTML

![HTML Screenshot](https://raw.githubusercontent.com/lawrence-dol/justright-latte-syntax/develop/img/AtomTheme-HTML.png)

#### CSS

![CSS Screenshot](https://raw.githubusercontent.com/lawrence-dol/justright-latte-syntax/develop/img/AtomTheme-CSS.png)

#### JavaScript

![JavaScript Screenshot](https://raw.githubusercontent.com/lawrence-dol/justright-latte-syntax/develop/img/AtomTheme-JS.png)

#### Java

![Java Screenshot](https://raw.githubusercontent.com/lawrence-dol/justright-latte-syntax/develop/img/AtomTheme-Java.png)
