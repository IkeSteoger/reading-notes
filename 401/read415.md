# 401 Reading 15

## Teach: How to set up a linked list with insert functionality

First you need to set up a class for your Nodes. Within this you'll set a constructor that will intake a value, setting this.value = value and this.next = null. Like so!

``` JavaScript
class Node {
  constructor(value){
    this.value = value;
    this.next = null;
  }
}
```

Then you'll start up your linked list class, using a constructor with a this.head = null. After which we will create our insert(value) function. The insert function will definite a new node, and node.next to this.head. Then you set this.head to the new node! Its so easy. Like so:

``` Javascript
class LinkedList {
  constructor(){
    this.head = null;
  }

  insert(value){
    let node = new Node(value);
    node.next = this.head;
    this.head = node;
  }
}
```

Now you have a functional linked list you can add new values to! Enjoy!
