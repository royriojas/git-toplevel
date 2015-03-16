# git-toplevel
> Method to find the top level git directory

# Install
```bash
npm i --save git-toplevel
```

# Usage
```javascript
var gitTopLevel = require('git-toplevel');

gitTopLevel().then(function(dir) {
  // dir ===> the git root 
}).catch(function(err) {
  // err ===> any error that happen when trying to get the top level dir
});
```