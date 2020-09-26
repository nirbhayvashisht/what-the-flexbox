# Introduction to FlexBox

### display:flex;
- To start a flexbox, we define the container as display:flex;
- the immediate children automatically becomes flex-items

### display: inline-flex;
- It wraps arround the content, and it only occupies the width that it needs.

### height: 100vh;
- viewport height
- takes the height of the device.
- Equivalent to height:100%;


# Working with flexbox flex-direction

### flex-direction: row;
- Default value
- Puts the flex-items side by side
- main axis is left to right
- cross axis is from top to bottom

### flex-direction: column;
- Stacks the items virtically on top of each other.
- main axis is from top to bottom.
- coss axis is from left to right.

### flex-direction: row-reverse;
### flex-direction: column-reverse;
- Reverses the axis


# Wrapping elements with Flexbox

### flex-wrap
- by default it is nowrap, ie, flex-wrap:nowrap;
- flex-wrap: wrap;
    - We can give wridth to flex-items after doing this
- flex-wrap: wrap-reverse;
    - The cross axis reverses, ie., becomes bottom to top.
    