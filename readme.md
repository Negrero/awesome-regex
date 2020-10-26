# Regex
* text in html: `/<[^>]+>/g`
  ```
    var htmlString= "<div><h1>Hello World</h1>\n<p>It's me, Mario</p></div>";

    var stripedHtml = htmlString.replace(/<[^>]+>/g, '');

    //Hello World
    //It's me, Mario
    console.log(stripedHtml);
    ```

# Library
* [he](https://github.com/mathiasbynens/he)