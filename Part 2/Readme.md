# Identify target browser hometask

## Task description
In this part, I configured a separate assembly for old and modern browsers based on the esmodules in babel. I use ES modules with Babel in order to create two different js files, one of which will be less weight and load in modern browsers (.babelrc), and the second(.babelrc-old-brousers) will be larger and provide support for older browsers

Structure of the task:

```
+---Part 2
|   +---src
|   \---package.json
|   \---webpack.config.js
|   \---.babelrc
|   \---...
```