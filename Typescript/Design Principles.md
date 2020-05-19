
**DRY Principle**

*DRY stands for Don't Repeat Yourself and the principle is that there should only ever be one copy of any important piece of information.*

**DRY in Front End**

# DRY in HTML

To keep HTML DRY, you can follow the component approach and keep them separate. And each file should be responsible for only one component.

Most of the times it will be a Server Side Language rendering HTML or a Single Page Application.

In case of both Server Side or Client Side HTML generation, keeping one component per file will keep the HTML DRY. But sometimes you can't ignore the repetition and have to go on with that.


#DRY in CSS
to keep CSS clean and DRY, There are different approaches to keep CSS sane i.e. modular and maintainable like BEM (Block Element Modifier), OOCSS (Object Oriented CSS), Atomic CSS etc. These methodologies will provide a way to create css without being dependent on the structure or content very much.

**Example for BEM**
```
/* Block component */
.btn {}

/* Element that depends upon the block */ 
.btn__price {}

/* Modifier that changes the style of the block */
.btn--orange {} 
.btn--big {}
```

#HTML + CSS

In various scenario mixing both of these two we can keep our front end code DRY.
Keep only copy of html template and use css to format.
CSS instead repeating same rule set for different elements, separete generic css rules and reuse.

