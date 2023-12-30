## Lesson 2 - Relative

A relatively positioned element is positioned relative to its normal position in the document flow. This means you can move it left, right, up, or down, and the space it occupies in the normal flow remains reserved. Imagine it is a static position but it can be move using left, right, up, or down.

```css
/* Syntax */
#container {
  position: static;
}

#box-one {
  position: relative;
  top: 20px;
  left: 20px;
}

#box-two {
  position: static;
}
```

![Relative Sample Output](../images/relative.png)

### Exercise

NOTE: Remember to modify the given code in start folder. As much as possible, do not at look the final output folder. If you are done you can check and compare the results to final output folder if it is the same.

In the CSS file, Try to change the position of the `#box-two` into `relative` and add both top and left property a `100px`, and observe the changes.

```css
#box-two {
    height: 100px;
    width: 100px;
    border: 2px solid blue;
    position: static
}
```

Congratulations! You have now completed Lesson 2. Let's move on to the [next lesson](https://github.com/sharproyalz/css-position/blob/main/3_Lesson/README.md#lesson-3---absolute).
