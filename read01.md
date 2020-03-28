# SMACSS &amp; Responsive Web Design

**Responsive** web design is the practice of building a website suitable to work on every device and every screen size.
The different between *responsive* and *adaptive* web design is:
* Response for changes Responsive react quickly and positively to any change but the adaptive easily modified for a new purpose or situation. 
* changeability responsive continually and fluidly change based on different factors but the adaptive it’s built to a group of preset factors. 

*Mobile* web design is to build a separate website commonly in a new domain for mobile users and this Will make us need dependencies Of new code base and browser sniffing. to have a good response for the website it better to have all three, responsive, adaptive and mobile website design together. 

Responsive web design have three main components which is:
1. flexible layout 
2. media queries
3. flexible media 

Identify the proportions of a flexible layout **formula**:
 Target / context = result 

This formula will create a completely dynamic website, But this isn’t enough so we need to media queries also. 

**Media queries** : It’s an extension to media targeting style and it’s provide the ability to specify different styles for individual browser
We can use media query by @import @media 
And there are three different logical operators available for use in media queries: 
1. and
2. not
3. only 

Media features identify what attributes or properties will be targeted within the media query expression and the *height* and *width* is one of the most common media features, *orientation media* can determine if the device is in the landscape or portrait orientation. 

And we should to identify **breakpoint** and this should be introduced when the website start to break, look weird or being hampered.

**Mobile first** it’s a technique using media queries and it’s an approach include using style targeted to a smaller few ports as the default Styles then use media queries to add styles.

**Float** it’s a CSS position property and it’s related to text wrap floated elements remain a part of the flow of the webpage and this would differentiate float element then the absolute element. 
There are four valid values for the float property:
1. Left 
2. Right 
3. None
4. Inherit

**Clear** property is used with the float Property and the element that has the clear property Will not move to set in the available space area And this property have valid value: 
1. Both
2. Left / Right
3. None
4. Inherit

If the parent element of the floated element contain nothing else The height of the bed and would literally collapse to nothing and anti-property for this is the blocked element.