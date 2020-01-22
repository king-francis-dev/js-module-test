## Create your own module

# 1. Register in 'https://www.npmjs.com/'
# 2. Check if your desired module name exists
```bash
$ npm view your-first-node-module
```
A non-existing module will response like this
```bash
npm http GET https://registry.npmjs.org/your-first-node-module
npm http 404 https://registry.npmjs.org/your-first-node-module
npm ERR! 404 'your-first-node-module' is not in the npm registry.
npm ERR! 404 You should bug the author to publish it
npm ERR! 404 
npm ERR! 404 Note that you can also install from a
npm ERR! 404 tarball, folder, or http url, or git url.

npm ERR! System Darwin 13.0.0
npm ERR! command "/usr/local/bin/node" "/usr/local/bin/npm" "view" "your-first-node-module"
npm ERR! cwd /Users/tmpvar/work/tmp
npm ERR! node -v v0.10.25
npm ERR! npm -v 1.3.24
npm ERR! code E404
npm ERR! 
npm ERR! Additional logging details can be found in:
npm ERR!     /Users/tmpvar/work/tmp/npm-debug.log
npm ERR! not ok code 0
```

# 3. Initialize Package.json

```bash
$ npm init
```

# 4. Add Code
Export your code in the main entrance of your project which is in your ```package.json```'s main property

# 5. Publish your module

```bash
$ npm publish
```