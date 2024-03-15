# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### Links

- Solution URL: (https://github.com/Tesfayeaweke/Recipe-main-page.git)
- Live Site URL: [Add live site URL here](https://tesfayeaweke.github.io/Recipe-main-page/)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

-Reseting list style using list-style-type property after using css reset.


```html
<section class="instructions">
            <h2 class="headings">Instructions</h2>
            <ol class="instructions-list">
                <li class="instruction-items"><span class="ol-titles">Beat the eggs</span>: In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed.You can add a tablespoon of water or milk for a fluffier texture.</li>
                <li class="instruction-items"><span class="ol-titles">Heat the pan</span>: Place a non stick frying pan over a medium heat and add butter or oil.</li>
                <li class="instruction-items"><span class="ol-titles">Cook the omelette</span>: Once the butter is melted and bubbling,pour in the eggs. Tilt the pan to ensure the eggs evenly coat the surface.</li>
                <li class="instruction-items"><span class="ol-titles">Add fillings(optional)</span>: When the eggs begin to set at the edges but are still slightly runny in the middle, sprinkle your chosen fillings over one and half of the omelette.</li>
                <li class="instruction-items"><span class="ol-titles">Fold and serve</span>: As omelette continues to cook, carefully lift one edge and fold it over the fillings. Let it cook for another minute, then slide it on to a plate.</li>
                <li class="instruction-items"><span class="ol-titles">Enjoy</span>: Serve hot, with additional salt and pepper if needed.</li>
            </ol>
        </section>
```
```css
.instructions ol{ 
    
    list-style-type : decimal;
    margin-left: 1.5em;
    /* display: flex;
    flex-direction: column;
    align-items: center;
     */
   
    
} 
```
-Using the pseudo-element  ::marker to change the color of the numerals in the ordered list.
```css
.instructions ol li::marker{ 
    color: hsl(14, 45%, 36%);
    
    
    
} 
```
-Spacing table columns by setting width to 100%

```css
section:last-of-type table{
    width: 100%;
    font-weight: 300;
    
    font-size: 0.8em;
    line-height: 1.5;
    margin: 24px 0;
    border-spacing: 100px 0;

}
```

## Author

- Frontend Mentor - [@Tesfayeaweke](https://www.frontendmentor.io/profile/@Tesfayeaweke)
- Twitter - [@Tesfaye08701635](https://www.twitter.com/@Tesfaye08701635)



# Recipe-main-page
 a project of frontend mentor
