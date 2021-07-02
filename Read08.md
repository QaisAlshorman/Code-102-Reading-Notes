![image](https://user-images.githubusercontent.com/85091281/124283270-626d5400-db54-11eb-8c24-122215068993.png)

![image](https://user-images.githubusercontent.com/85091281/124283264-613c2700-db54-11eb-97c5-cbc02bd322b3.png)

CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the positionproperty in CSS. You can also float elements using the float property.

#### Relative Positioning
This moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This does not affect the position of surrounding elements; they stay in the position they would be in in normal flow.

#### Absolute positioning
This positions the element in relation to its containing element. It is taken out of normal flow, meaning that it does not affect the position of any surrounding elements (as they simply ignore the space it would have taken up). Absolutely positioned elements move as users scroll up and down the page.

#### To indicate where a box should be positioned, you may also need to use 
box offset properties to tell the browser how far from the top or bottom and left or right it should be placed. 

#### Fixed Positioning 
This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.



#### Fixed Positioning 
This is a form of absolute positioning that positions the element in relation to the browser window, as opposed to the containing element. Elements with fixed positioning do not affect the position of surrounding elements and they do not move when the user scrolls up or down the page.

#### Floating Elements
Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box. The floated element becomes a block-level element around which other content can flow

![image](https://user-images.githubusercontent.com/85091281/124284764-ed9b1980-db55-11eb-9792-831fe656a143.png)

![image](https://user-images.githubusercontent.com/85091281/124285543-acefd000-db56-11eb-8631-6ca8375d4360.png)

![image](https://user-images.githubusercontent.com/85091281/124285770-f0e2d500-db56-11eb-8b44-32df8eeb3d75.png)

#### When you use relative, fixed, or absolute positioning, boxes can overlap. 
If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. 

![image](https://user-images.githubusercontent.com/85091281/124290249-e1b25600-db5b-11eb-8ace-aabc1fea170b.png)

The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.Anything else that sits inside the containing element will flow around the element that is floated.
*When you use the floatproperty, you should also use the width property to indicate how wide the floated element should be. If you do not, results can be inconsistent but the box is likely to take up the full width of the containing element (just like it would in normal flow).*

A lot of layouts place boxes next to each other. The floatproperty is commonly used to achieve this.
When elements are floated, the height of the boxes can affect where the following elements sit.
![image](https://user-images.githubusercontent.com/85091281/124290905-a9f7de00-db5c-11eb-872f-8fd0f902d455.png)

The clear property allows you to say that no element (within the same containing element) 
should touch the left or righthand sides of a box. It can take 
the following values:
left The left-hand side of the box should not touch any other elements appearing in the same containing element.
rightThe right-hand side of the box will not touch elements appearing in the same containing element.
bothNeither the left nor right-hand sides of the box will touch elements appearing in the same containing element.
noneElements can touch either side.
![image](https://user-images.githubusercontent.com/85091281/124291251-11159280-db5d-11eb-8b4e-300ff4b697af.png)

More recently, developers have opted for a purely CSS-based solution because it means that there is no need to add an extra element to the HTML page after the floated elements. The pure CSS solution adds two CSS rules to the containing element (in this example the <div> element):
● The overflow property is given a value auto.
● The width property is set to 100%.

![image](https://user-images.githubusercontent.com/85091281/124291450-41f5c780-db5d-11eb-9975-dcb7e8c19d84.png)
  
Many web pages use multiple columns in their design. This is achieved by using a <div>element to represent each column. The following three CSS properties are used to position the columns next to each other: 
##### width
This sets the width of the columns.floatThis positions the columns next to each other.marginThis creates a gap between the columns.
 #### Screen Sizes
The size of a user's screen affects how big they can open their windows and how much of the page they will see. There are also an increasing number of handheld devices (mobile phones and tablets) that have smaller screens.
#### screen Resolution
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens.
#### Page Sizes
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide (since most users will be able to see designs this wide on their screens)
  
#### Fixed Width Layouts
  
  ![image](https://user-images.githubusercontent.com/85091281/124292770-9ea5b200-db5e-11eb-934f-f4423d3b5fc4.png)

#### Liquid Layouts
  
  ![image](https://user-images.githubusercontent.com/85091281/124292993-dc0a3f80-db5e-11eb-9d2f-9748804e8292.png)

  ![image](https://user-images.githubusercontent.com/85091281/124293508-6bafee00-db5f-11eb-9346-cd1f9ce19fc3.png)

  ![image](https://user-images.githubusercontent.com/85091281/124293823-b9c4f180-db5f-11eb-9be1-e5baf3c20f6e.png)

- <div> elements are often used as containing elements to group together sections of a page.
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.
 
