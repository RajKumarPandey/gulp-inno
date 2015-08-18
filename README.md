# gulp-inno

Compile a windows installer using Inno Setup Compiler and Gulp.

### Example:

Pass your inno script in gulp src and pipe it to Inno.

```javascript
var gulp = require('gulp');
var inno = require('gulp-inno');
gulp.src('./installer_script.iss').pipe(inno());
```

For OS X Users: If you get `Failed to start Cocoa app main loop`, you need to upgrade wine to the latest devel

```brew install wine --devel```

### TODO:
- Write proper Readme.
- Clean unneeded inno files.
