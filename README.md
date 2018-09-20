
#eslint-config-lky


# How to Use lky

if you want to use thi ESlint configuration in your project, you can install with following steps:

First, install this package, ESlint ang the necessary plugins

``` javascript
 npm install --save-dev eslint-config-lky eslint@^4.2.0 eslint-plugin-import@^2.7.0  eslint-plugin-jsx-a11y@^6.0.0 eslint-plugin-react^7.1.0

```
Then, create a file named .eslintrc.* with the following contents in the root folder of your project:

```javascript
{
    "env": {
        "es6": true,
    },
    "extends": "lky",
}
```

Will ！ Do That, you can override the settings from eslint-config-lky by editing the .eslintrc.* file. learn more [configuring ESlint](https://eslint.org/docs/user-guide/configuring) on the esLint website.
