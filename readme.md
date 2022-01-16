

**This package is already complete and ready for use**

**How to make js code**

1. The first thing you want to do is create a file. It's easy to name this "index.js".

2. Write your code. In order to make this simple, just do a basic command, like `console.log('test');`

3. Go to your terminal and do the command `npm init -y`. This will create a "package.json" file.

4. Go to the "scripts" section, then right after you will see `echo \"Error: no test specified\" && exit 1`. Replace that with `node index your_script_here.js`.
In this case, our start script is `node index.js` so you can replace `echo \"Error: no test specified\" && exit 1` with `node index.js`.

5. Go to your terminal again and run `node index.js`.

6. All done!