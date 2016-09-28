# CSS: Inheritance, Cascade, and Specificity

Several factors interactively impact what css styles are displayed on a user's screen.  The factors leading to a specific *weight* include:

* the ordering of css file imports
* the ordering of the actual declaration statements
* whether the declaration statement is in an import, a meta tag, or inline
* whether the element inherits styles
* the selector types
* the specificity of actual declarations

****
**NOTE: `!important`**
Adding `!important` after an assigned property's value (e.g. `body { font-weight: bold !important }`) is an easy way to add weight to a specific property's assignment.
For many reasons you should never deploy css with an `!important` property.  Since it's easy to forget about it if you already have it in your css it's better to simply to never put it in your code in the first place.
****




## References

* [CSS Cheat Sheet: Inheritance, Cascade, Specificity](http://srjcstaff.santarosa.edu/~tfleming/htmlb/CSS_Cheat_Sheet_Inheritance_Cascade_Specificity.pdf)


### Inheritance
"The summary of every CSS property definition says whether that property is inherited by default ("Inherited: Yes") or not inherited by default ("Inherited: no"). This controls what happens when no value is specified for a property on an element."
* [MDN: inheritance](https://developer.mozilla.org/en-US/docs/Web/CSS/inheritance)

### Cascade
* [MDN: CSS Cascade](https://developer.mozilla.org/en-US/docs/Web/CSS/Cascade)


### Specificity
- [CSS Tricks: Specifics on CSS Specificity](https://css-tricks.com/specifics-on-css-specificity/)
- [Smashing Mag: CSS Specificity and Inheritance](https://www.smashingmagazine.com/2010/04/css-specificity-and-inheritance/)
- [Specificity Calculator](http://specificity.keegan.st/)
- Visual References:
  - [CSS Specificity - The Shining'](http://cssspecificity.com)
  - [Specificity - Star Wars](https://stuffandnonsense.co.uk/archives/images/specificitywars-05v2.jpg)


### Styling Anchor Elements

* [Link Specificity](http://meyerweb.com/eric/css/link-specificity.html)
* [Who Ordered the Link States](http://meyerweb.com/eric/thoughts/2007/06/11/who-ordered-the-link-states/)

#### Order of Link States Pneumonics

| Link | Visited | Hover | Focus | Active |
| ---- | ------- | ----- | ----- | ------ |
| Lord | Vador | Hates | Furry | Animals |
| Luther | Vandross | Hits | Fabulous | Arpeggios |
| Lord | Voldemort | Has | Foul | Ambitions |
