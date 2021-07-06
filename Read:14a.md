CSS3 has introduced countless possibilities for UX designers, and the best thing about them is that the coolest parts are really simple to implement.

Just a couple of lines of code will give you an awesome transition effect that will excite your users, increase engagement and ultimately, when used well, increase your conversions. What’s more, these effects are hardware accelerated, and a progressive enhancement that you can use right now.





![image](https://user-images.githubusercontent.com/85091281/124679619-6fc86c80-decd-11eb-8a12-f2edcce093ed.png)

![image](https://user-images.githubusercontent.com/85091281/124679679-8f5f9500-decd-11eb-879b-e50ac0c6dfe1.png)

Vendor Prefixes
The code above, as with the rest of the code samples in this lesson, are not vendor prefixed. This is intentionally un-prefixed in the interest of keeping the code snippet small and comprehensible. For the best support across all browsers, use vendor prefixes.

For reference, the prefixed version of the code above would look like the following.

![image](https://user-images.githubusercontent.com/85091281/124679788-cafa5f00-decd-11eb-8371-192b27a1001e.png)


Transitional Property
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.

In the example above, the background property is identified in the transition-property value. Here the background property is the only property that will change over the duration of 1 second in a linear fashion. Any other properties included when changing an element’s state, but not included within the transition-property value, will not receive the transition behaviors as set by the transition-duration or transition-timing-function properties.

If multiple properties need to be transitioned they may be comma separated within the transition-property value. Additionally, the keyword value all may be used to transition all properties of an element.

![image](https://user-images.githubusercontent.com/85091281/124679850-e4031000-decd-11eb-8062-38f2d3ca67d9.png)


Transitional Properties
It is important to note, not all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another. The display property, for example, may not be transitioned as it does not have any midpoint. A handful of the more popular transitional properties include the following.

![image](https://user-images.githubusercontent.com/85091281/124679911-01d07500-dece-11eb-911c-3b4fb88ff997.png)






