# **CSS Session Notes**
This document is for **STEAM4Girls IV**, has notes for **`CSS`** session of the web devlopment module

## **Terminology in CSS**
| Term | Desc | Example |
| ---- | ---- | ------- |
| **Property**| A **`CSS`** term to a design aspect for a **`HTML`** element  | `color`, `background-color`, `font-size`|
| **Rule**| A **collection** of **properties** that is applied in the same time  | **/**|
| **Selector**| A pattern of elements and other terms that tell the browser which element should be selected to have the CSS property values inside the rule applied to them  | **/**|

## **Syntax**

```css
    selector{
        property-one: "value";
        property-two: "value";
        property-three: "value";
    }
```

### **How to type a correct `CSS` Rule?:**
- The **`CSS`** rules starts with the **selector** followed by an **opening curly bracket / brace "`{`"**
- In the next line, you type the **property name** followed by a **`colon ":"`** followed by **the value of the property** ending it with a **semi colon `";"`**
- A rule must finish with a **closing curly bracket / brace `"}"`**

#### **Examples:**

```css
    body{
        padding: 0;
        margin: 0;

        background-color: #222222;
        color: #fefefe;

        font-family: Georgia, serif;
        font-size: 20px;
    }

    .red-text{
        color: red;
    }

    #black-face{
        face-color: black;
        freckles-color: orange;
    }
```

Of coure the last rule  is imaginary lol, yet that would be a correct syntax if both `face-color` and  `freckles-color` were actually defined in `CSS`

### **Units in CSS:**
Those are SOME of the units in CSS
| Unit | Desc |
| ---- | ---- |
| **px** | the smallest unit of a digital image or graphic that can be displayed and represented on a digital display device |
| **em** | Font size of the parent, in the case of typographical properties `font-size`, and font size of the element itself, in the case of other properties `width` **(By default 1em = 16px)** |
| **vh** | 1% of the viewport's height |
| **vw** | 1% of the viewport's width |

## **Some Properties**
Here some of the properties we had on the session and some other extra ones
| Property | Desc | Notes |
| -------- | ---- | ----- | 
| **`color: colorValue`** | Colors the text of the selected element with the given **`color value`**  | The color value can be either a **predefined value** such `red`, `blue`, `green` ... ect or  a `hexadecimal value` such  `#000000`, `#fefefe` ... ect,  or using a CSS function like `rgb`, `rgba` where **r** stands for **red**, **g** stands for **green** and **b** stands for **blue** and **a** stands for **alpha (opacity)** |
| **`background-color: colorValue`** | Colors the background of the selected element with the given **`color value`**  | **Look at the previous column**|
| **`font-family: fontValue`** | Applies the font for the typography of the selected item with the given **`font value`**  | the `fontValue` can be either predefined or imported from another  source like `Google fonts` or defined in a seperate rule |
| **`width: value`** | Gives a specific width to the selected element (**`value`**)  | **/** |
| **`height: value`** | Gives a specific height to the selected element (**`value`**)  | **/** |
| **`border: borderSize colorValue typeValue`** | Gives a selected element a `border` with a size of **`borderSize`** and a color of **`colorValue`** and a type of **`typeValue`**  | **`typeValue`** can be one of the following **`solid`**, **`dotted`**, **`dashed`**, **`none`** ... |

**Note:** those are SOME of the properties, CSS is very rich with them and has many other and many other are to come, so I invite you to check this resource for reference: [Mozilla MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

