# CSS3 RoadMap

## Resources to follow
1. [Frontend Roadmap](https://bibekdhkl.github.io/CSS-RoadMap/Resources/2021-Frontend-Roadmap-Dark.pdf)
2. [CSS Cheatsheet](https://devhints.io/css)
3. [Repository you can take reference](https://github.com/Roopaish/CSS-RoadMap)
4. [Additional Cheatsheets](https://github.com/Bibekdhkl/CSS-RoadMap/tree/master/Resources)

## CSS3
1. [Selectors](https://bibekdhkl.github.io/CSS-RoadMap/Resources/CSS-Selector-Cheat-Sheet-Light.pdf)
<br>
It represents how the html elements can be selected in a css file<br>

```
Examples
* {

} Universal Selector: It selects all the elements

#id_name{

} Id selector: It selects only the elements with ID

.class_name{

} Class selector: It selects only element with Class name

Also,

<textbox type="text">
<textbox type="password">

Here, if we want to select only password attribute then

textbox[type="password"]{

}
```
- __pseudo class__ is also an important concepts to look forward to like:

```
a:first-child{

}     It selects the first a tag (~ a:last-child)

a:nth-child(2n){

}     Select even numbered anchor tag i.e. 2,4,6...

```
2. Cascade
3. [Box Model](https://bibekdhkl.github.io/CSS-RoadMap/Extra/index.html)<br>[BoxModel-cheatsheet](https://bibekdhkl.github.io/CSS-RoadMap/Resources/CSS-Box-Model-Cheat-Sheet-Light.pdf)
```
It is all about arrangement of layouts in web page
example:
<p> Heading</p>
In this above element:
  Content is Heading
  And after content there is padding which is transparent gap between content and border
  Then comes border whose thickness can be changed by css shorthand property border
  And finally comes margin which is the gap outside the border to other element
```
4. [Specificity](https://blog.webdevsimplified.com/2020-02/css-specificity/)
```
It means what CSS styles will be applied or override in case of multiple styles on same element
In layman's term:
!important > Inline CSS > #id > .class > element
example:
h1 {
  color: blue !important;
}
h1 {
  color: green;
}
Here, blue will be applied on h1
```
5. Position
6. Display
7. Flexbox
8. Grid
9. Float
10. Calc
11. Pseudo Elements
12. Pseudo Classes
13. Custom Properties
14. Media Queries
15. Animations

### Projects
1.Easy
- [Transparent Login Form](https://bibekdhkl.github.io/CSS-RoadMap/TransparentLoginForm/index.html)
- [Responsive Video Background](https://bibekdhkl.github.io/CSS-RoadMap/ResponsiveVideoBg/index.html)

2.Medium
- [CSS Only Tooltips](https://bibekdhkl.github.io/CSS-RoadMap/CSSOnlyTooltips/index.html)
- CSS Emoji Art 
- CSS Face Art 
- Advanced Hover Effects 
- Animated Page Load 
- Custom Checkbox Tutorial 
- 3D Flip Button 
- Animated Loading Spinner 

3.Hard
- YouTube Clone 
- Price Comparison Table 
- Landing Page 1 
- Landing Page 2 
