### Introduction

Adds a method to pc.Entity to return an array of components or scripts that match the search term suppllied

### Installation

```language-shell
npm install --save playcanvas-of-type
```

### Usage

```language-javascript
import 'playcanvas-of-type'

...

//Get collision components
this.entity.ofType('collision').forEach(doSomething);

this.entity.ofType('myscript').forEach(script=>{
    script.method();
}); 
 

```

### Requirements

Requires PlayCanvas Engine to be running on the page.  Uses ES6/Babel/PlayCanvas template.
