#3.5 Your Website, part 3 

## Release 3: Reflect

answer the following questions:

1. What did you learn about CSS padding, borders, and margin by doing this challenge?

    *   Explanation of the different parts:
        -   Content - The content of the box, where text and images appear
        -   Padding - Clears an area around the content. The padding is transparent
        -   Border - A border that goes around the padding and content
        -   Margin - Clears an area outside the border. The margin is transparent

2. What did you learn about CSS positioning?

    * All boxes in html are placed on top of each other.
    * I used float property to position boxes next to each other.
    * i Used max-min width property to control their size.
    * overflow property to control content in the box.

3. What aspects of your design did you find easiest to implement? What was most difficult?

  Easiest part was to create logical section of page. e.g 
  `<header> <body> <footer>`

  Difficult part was to position boxes e.g. 
  Using *float* property. Pitfall is that sometimes unwanted content begins to wrap around a floated element. 

4. What did you learn about adding and formatting elements with CSS in this challenge?

```
.profile-pic{

  width: 37.91%;
  height: 47.91%;
  float: left;
  margin: 10px;
  }
  ```
I used _float_ property to place boxes next to each other
Used width property to control boxes per row
Height property to contain boxes relative to other boxes

```
.para{
  text-align: left;
}
```
This is used to align text.

