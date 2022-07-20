# Brackets Junior Developer Code Test

## READ CAREFULLY
* Spend as little or as long as you want on these tasks.
* Work must be completed in your own private repository. 
* You may use any additional technology or library you see fit.
* Answer the questions in the README.md of your repo, or by adding .php or .js files where stated.

Once completed add patrickAsare as a collaborator to your private repo.

## What we are looking for

Firstly, we look for code that works. Secondly, we look for short clear commit messages. This helps us determine how you approach problems. Finally, we look for code that is clean, readable and maintainable.

### Question 1. 
Explain the difference between a get and post request.

### Question 2. 
Explain the difference between `include`, `include_once`, `require` and `require_once` in PHP.

### Question 3.
Explain the benefits of using PDO and Prepared Statements in PHP.

### Question 4. 
How would you turn all errors on in a PHP script?

### Question 5.
Why is the var_dump statement used in PHP. What is it useful for?

### Question 6. 
What is composer and why is it used in PHP?

### Question 7.
Write a PHP script named fizzbuzz.php. The script should include a function that echos numbers from 1 to n. But for multiples of three print “fizz” instead of the number and for the multiples of five print “buzz”. For numbers which are multiples of both three and five print “fizzbuzz”. Commit the file to your repo.

```php
// --- Example output
fizzBuzz(5);
//   1
//   2
//   fizz
//   4
//   buzz
```

### Question 8.
Write a PHP script named capitalise.php which includes a function that accepts a string. The function should capitalize the first letter of each word in the string then return the capitalized string. Commit the file to your repo.

```php
// --- Example output
capitalise('a short sentence');
// 'A Short Sentence'

capitalise('a lazy fox');
// 'A Lazy Fox'

capitalise('look, it is working!');
'Look, It Is Working!'
```

### Question 9. 
What does the following javascript code output? Explain why.

```javascript
(function(){
  function bar() { return 7; }
  function foo() { return 1; }
  return foo() + bar() + ',' + baz;
  function foo() { return 2; }
  var bar = () => { return 3 }
  var baz = 'Hello world';
}());
```

### Question 10.

A set of URLs is defined in an array:

```javascript
    var urls = [
      'https://api.binance.com/api/v3/avgPrice?symbol=BTCUSDT',
      'https://api.binance.com/api/v3/avgPrice?symbol=ETHUSDT',
      'https://api.binance.com/api/v3/avgPrice?symbol=LTCUSDT'
    ];
```

Write JavaScript in a file named fetch.js. The file should include a function that takes a set of urls and fetches all of the URLs. After each request’s success or failure, log the result. 
When and if all have loaded, execute some logic on the result of all the calls.

### Question 11. 

Your site is taking 30s to be painted by the browser over a 3G connection on every visit. Name 5 things you would look into to reduce this time, why you would choose those and how you would investigate and fix them? 

### Question 12.
You are looking at production code of an Express.js app and see this. What are your thoughts?

```javascript
const myFile;

app.get('/', function (req, res) {
    myFile = require('fs').readFileSync('35df8h/a.txt', 'utf8');
    res.send(myFile);
});
```

### Question 13.

This legacy code checks to see if a value exists in a url.

How would you make this statement more readable for other developers to understand what’s going on?
Describe what you would do and / or provide pseudocode.

```php
if (!empty($fms5->urlArray[count($fms5->urlArray) - 2]) && $fms5->urlArray[count($fms5->urlArray) - 2] === "cast-creatives") {
    //
}
```

### Question 14.
Explain the differences between the 3 different types of array in PHP.

### Question 15.
The special tag `<?=` is used to do what in PHP?

### Question 16.
Create a a separate private repository with a default installation of the latest version of Laravel. https://laravel.com/ Once completed add patrickAsare as a collaborator to your private repo.
