# CSS
### 1. What are the main differences between external, internal, and inline CSS?
    The external CSS means you need to add CSS in a diferrent file and then link it to the HTML file. The internal CSS gets added directly in the HTML file into a <style> tag and the inline CSS gets added directly on the HTML element as an attribute.
### 2. What is the syntax for class and ID selectors?
    For class you use .className and for id you use #idName.
### 3. How would you apply a single rule to two different selectors?
    You can add a single rule to multiple selectors by grouping and dividing the by a comma (selector-1 , selector-2 {})
### 4. Given an element that has an id of title and a class of primary, how would you use both attributes for a single rule?
    #title, .primary {}
### 5. What does the descendant combinator do?
    Combinators allow us to combine multiple selectors differently than either grouping or chaining them, as they show a relationship between the selectors.
### 6. Between a rule that uses one class selector and a rule that uses three type selectors, which rule has the higher specificity?
    The class selector is more spacific to that element then the type selector.
### 7. From inside to outside, what is the order of box-model properties?
    The order is margin, border, padding, content.
### 8. What does the box-sizing CSS property do?
    The box-sizing CSS property sets how the total width and height of an element is calculated.
### 9. What is the difference between the standard and alternative box model?
    In the alternative box model, any width is the width of the visible box on the page. The content area width is that width minus the width for the padding and border. No need to add up the border and padding to get the real size of the box. In the standard box model, if you give a box an inline-size and a block-size (or width and a height) attributes, this defines the inline-size and block-size (width and height in horizontal languages) of the content box. Any padding and border is then added to those dimensions to get the total size taken up by the box.
### 10. Would you use margin or padding to create more space between 2 elements?
    You use margin.
### 11. Would you use margin or padding to create more space between the contents of an element and its border?
    You use padding.
### 12. Would you use margin or padding if you wanted two elements to overlap each other?
    I wouldn't use neither but you can use margin.
### 13. What is the difference between a block element and an inline element?
    Block elements always start from a new line. Inline elements never start from a new line.
### 14. What is the difference between an inline element and an inline-block element?
    The major difference is that inline-block allows to set a width and height on the element.
### 15. Is an h1 block or inline?
    h1 is block.
### 16. Is button block or inline?
    Inline.
### 17. Is div block or inline?
    Block.
### 18. Is span block or inline?
    Inline.
### 19. What’s the difference between a flex container and a flex item?
    Flex Container is the parent element while Flex Item represents the children.
### 20. How do you create a flex item?
    You make the parent a flex container. Then the elements inside are flex items.
### 21. What are the 3 values defined in the shorthand flex property?
    flex: flex-grow flex-shrink flex basis.
### 22. How do you make flex items arrange themselves vertically instead of horizontally?
    To make flex items arrange themselves vertically you use flex-direction: column.
### 23. What is the difference between justify-content and align-items?
    justify-content aligns items on the axis of the flex-direction of the container and align-items on the other axis of the container.
### 24. How do you use flexbox to completely center a div inside a flex container?
    align-items: center;
    justify-content: center;
### 25. What’s the difference between justify-content: space-between and justify-content: space-around?
    space-between it will make equal space between elements, but no space in the start and end of the box
    space-around it will make equal space between elements and half of space in the start and end of the box