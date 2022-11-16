# Khand: FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Khand](https://fonts.google.com/specimen/Khand/about).

Khand is a family of compact mono-linear fonts with very open counter forms. Developed for display typography, the family is primarily intended for headline usage. Its letterforms are dynamic, and everything is designed according to a modular system. All of its shapes bear a strong commonality to one another, but the typeface strikes a good balancing act and avoids too much repetitiveness. The lighter styles are suitable for short paragraphs of running text, while the heavier styles have been optimized for headlines or single word settings.

The base character height in the Khand fonts is ‘big on the body.’ Across a line of text, the consonantal forms take up the majority of vertical space. Vowel marks above and below have been shortened – keeping these to a minimum allows for lines of text to be set more closely together vertically. The reduction of interlinear space is paramount for successful headline typesetting, and Khand performs much better in display applications than similar fonts with more elongated vowel marks. Because of their reduced height, the typeface’s vowel mark forms have been simplified somewhat out of necessity, but this stylistic reduction is in-keeping with the modular feeling of the typeface’s overall design. Dot-shaped marks appear rounded in order to help maintain their differentiation from other marks.

Khand’s Devanagari component was designed by Sanchit Sawaria and Jyotish Sonowal. The Latin component was designed by Satya Rajpurohit. To contribute, see https://github.com/itfoundry/khand

Designers: Indian Type Foundry, Principal design

[Indian Type Foundry](http://www.indiantypefoundry.com/) (ITF) creates retail and custom multilingual fonts for print and digital media. Started in 2009 by Satya Rajpurohit and Peter Bil’ak, ITF works with designers from across the world. ITF fonts are used by clients ranging from tech giants like Apple, Google, and Sony, to various international brands.

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/khand-font).

TLRD:

Include fifthtry.github.io/khand-font package into `FPM.ftd` file:

```ftd
;-- fpm.dependency: fifthtry.github.io/khand-font
```

Inside your `FPM/config.ftd` use the font:

```ftd
;-- import: fifthtry.github.io/khand-font/assets as khand

;-- fpm.type.headline-small.font: $khand.fonts.Khand
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `khand-font` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Khand Font is under [Open Font Licence](https://fonts.google.com/specimen/Khand/about), this FPM wrapper is also
under [Open Font License](LICENSE).




