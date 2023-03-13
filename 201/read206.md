# 201 Reading 06

## Problem Domain, Objects, and the DOM

### JavaScript Object Basics

Objects are a collection of related data/functions. Basically an easy way to think of it is a folder within your filing cabinent that holds some paperwork that is all related. They can be recalled later (or reprinted in our example)

Object literal is when you've literally written out the object contents as it's created. This is different compared to objects instantiated from classes. Object literal is commonly used when you want to transfer a series of structred & related data items in some manner. Sending a single object is much more efficient than sending several items individually, thus it is easier to work with an array when you want to identify individual items by name. (Mozilla.org)

Objects & arrays are basically the same thing but instead of using an index number to select an item, you use the name associated with each value. Sometimes objects are known as **associative arrays**!

While dot notation is often preferred over bracket notation, there are some exceptions. Like if an object property name is held in a vairable, you can't use dot notation to access that value, but could use bracket notation (Mozilla.org)

`this` will refer to the current object the code is being written inside. So in the code provided `this` enables you to use the same method of definition for every object we create.

### Introduction to DOM

The DOM is the Document Object Model. This is the data representation of the objects that comprisethe structure & content of a document. DOM represents the document as nodes & objects so that programming languages can interact with the page.

DOM & JavaScript work together, despite being a seperate entity. DOM is a Web API to build websites. DOM was built to be independent of a programming language. JavaScript can be used in other contexts.
