#### Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names. 

#### IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES If a variable is part of an object, it is called a property

#### IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object.

![image](https://user-images.githubusercontent.com/85091281/123527130-bb1c9700-d6e5-11eb-88ae-c741d0bd75b6.png)

#### Once you have created an object (using literal or constructor notation), you can add new properties to it. You do this using the dot notation that you saw for adding properties to objects

![image](https://user-images.githubusercontent.com/85091281/123527205-19497a00-d6e6-11eb-83df-d0981fa0ecd3.png)

### THE DOM TREE IS A MODEL OF A WEB PAGE As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.

#### THE DOCUMENT NODE Above, you can see the HTML code for a shopping list, and on the right hand page is its DOM tree. Every element, attribute, and piece of text in the HTML is represented by its own DOM node. At the top of the tree a document node is added; it represents the entire page (and also corresponds to the document object, which you first met on p36). When you access any element, attribute, or text node, you navigate to it via the document node. It is the starting point for all visits to the DOM tree. 

#### ELEMENT NODES HTML elements describe the structure of an HTML page. (The <h l > - <h6> elements describe what parts are headings; the <p> tags indicate where paragraphs of text start and finish; and so on.) To access the DOM tree, you start by looking for elements. Once you find the element you want, then you can access its text and attribute nodes if you want to. This is why you start by learning methods that allow you to access element nodes, before learning to access and alter text or attributes. 
  
  ![image](https://user-images.githubusercontent.com/85091281/123527236-688faa80-d6e6-11eb-99de-06587600a4eb.png)
  
 #### ATTRIBUTE NODES The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree. Attribute nodes are not children of the element thar carries them; they are part of that element. Once you access an element, there are specific JavaScript methods and properties to read or change that element's attributes. For example, it is common to change the values of cl ass attributes to trigger new CSS rules that affect their presentation. 

#### TEXT NODES Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node. Text nodes cannot have children. If an element contains text and another child element, the child element is not a child of the text node but rather a child of the containing element. (See the <em> element on the first <l i > item.) This illustrates how the text node is always a new branch of the DOM tree, and no further branches come off of it. 
  
### WORKING WITH THE DOM TREE 
Accessing and updating the DOM tree involves two steps:
  
1: Locate the node that represents the element you want to work with.
  
2: Use its text content, child elements, and attributes.
  
  ![image](https://user-images.githubusercontent.com/85091281/123527267-b73d4480-d6e6-11eb-86cd-1832d13578f3.png)
  
  The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element. 
  
  ![image](https://user-images.githubusercontent.com/85091281/123527284-e0f66b80-d6e6-11eb-9047-dc6916f2b8b4.png)


![image](https://user-images.githubusercontent.com/85091281/123527299-fe2b3a00-d6e6-11eb-9f04-6988cf379c21.png)
  
  ![image](https://user-images.githubusercontent.com/85091281/123527305-1307cd80-d6e7-11eb-9145-f1f1543b880f.png)









