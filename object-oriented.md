# Object Oriented JavaScript


## Constructors
Describe how an object should be created. Each one created is known as an instance.

```javascript
function Contact(name, email) {
  this.name = name;
  this.email = email;
}

// The instance
var contact = new Contact("Jacob", "myemail@email.com");
```
