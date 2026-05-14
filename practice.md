# What I learned 

In the first lecture I learned that JavaScript has different types, and that some results can be surprising. For example, `typeof null` gives `"object"`, and loose equality with `==` can convert values before comparing them. JavaScript sees `0` as a number and `""` as a string, so when I use `==`, it converts the empty string into `0` before comparing them.

- JavaScript has multiple data types.
- The `typeof` operator tells you the type of a value.
- Using `==` can sometimes give unexpected results because it does type conversion.

## Input 

```javascript
typeof null
0 == ""
```
## Output 

```
'object'
true
```
