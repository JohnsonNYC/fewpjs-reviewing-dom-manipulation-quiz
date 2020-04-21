## Quiz: Reviewing DOM Manipulation

Answer the questions below using the following code example.

```html
<body>
  <h1>List of pets ideal for city-dwellers</h1>
  <div>
    <ul>
      <li><span id="dog">Poodle</li>
      <li><span id="king-cobra">Nag</li>
      <li><span id="mongoose">Joe Mongoose</li>
   </ul>
  </div>
</body>
```


# Reviewing DOM Manipulation

1. Which of the following declarations will create a variable whose content CANNOT be changed?

* [ ] `var lunchOrder = "tofu"`
* [ ] `let lunchOrder = "soup"`
* [x] `const lunchOrder = "rock salt"`

2. Given a method called `razzle`, how do you trigger its behavior? 

* [ ] `razzle`
* [ ] `razzle[]`
* [ ] `(razzle)` 
* [x] `razzle()`

3: In the HTML snippet above, select the JavaScript command that would select the node containing the text "Poodle."

* [ ] `document.querySelector('.dog')`
* [ ] `document.querySelector('#king-cobra')`
* [x] `document.getElementById('dog')`
* [ ] `document.getElementById('#dog')`

4: In the HTML snippet above, select the JavaScript command which would select all the `<li>` nodes.

* [ ] `document.querySelector("li")`
* [x] `document.querySelectorAll("ul > li")`
* [ ] `document.querySelectorAll("ul")`
* [ ] `document.querySelector("span")`

5: Which of the following JavaScript statements will change the text of the node with the `id` of "dog" to the text "Byron"?

* [ ] `document.querySelectorAll("span[0]").textContent = "Byron";`
* [ ] `document.querySelector("#li").innerHTML = "Byron";`
* [x] `document.querySelector("#dog").textContent = "Byron";`
* [ ] `document.getElementsByClass("span")[0].textContent = "Byron"`

6: Talk about bad ideas, king cobras are not good pets. How can we remove the `span` with the `id` "king-cobra"?

* [ ] `document.querySelector("span").delete("#king-cobra");`
* [x] `el = document.querySelector("span#king-cobra"); y = el.parentNode; y.removeChild(el);`
* [ ] `el = document.querySelector("span#king-cobra"); y = el.parentNode(); y.removeChild(el);`
* [ ] `document.querySelector("ul").removeChild("span#king-cobra");`

7: We’ve been inundated by cat owners who are angry that we have missed their favorite species of pet. What JavaScript snippet will add an `li` with a `span` inside with the text "Nancy Drew (the cat)" inside to our `ul`?

* [ ] `document.getElementsByTagName("ul")[0] += "<li><span id=\"cat\">Nancy Drew (the cat)</span></li>";`
* [ ] `ul = document.getElementsByTagName("ul")[0]; ul.innerText += "<li><span id=\"cat\">Nancy Drew (the cat)</span></li>";`
* [x] `base = document.getElementsByTagName("li")[0].parentNode; item = document.createElement("li"); s = document.createElement("span"); s.id = "cat"; s.textContent = "Nancy Drew (the cat)"; item.appendChild(s); base.appendChild(item)`
* [ ] `base = document.getElementsByTagName("li")[0].parentNode; item = document.createElement("li"); s = document.createElement("span#cat"); s.textContent = "Nancy Drew (the cat)"; item.addChild(s); base.addChild(item)`

8: What JavaScript command would return the name of the mongoose?

* [ ] `document.querySelectorAll("#mongoose").text;`
* [x] `document.querySelector("#mongoose").textContent;`
* [ ] `document.querySelector("#mongoose").text;`
* [ ] `document.querySelectorAll("#mongoose").content;`

9: Which snippet correctly uses `innerHTML` to replace an HTML document’s body with a `div`containing an `h1` with content "No Pets Allowed"?

* [ ] `document.querySelector("#body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"`
* [ ] `document.querySelector(".body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"`
* [x] `document.querySelector("body").innerHTML = "<div><h1>No Pets Allowed</h1></div>"`
* [ ] `document.querySelectorAll(".body").innerHTML = "<div><h1>No Pets Allowed</h1></div>`

10: Changing rendered text in the DOM with JavaScript changes the HTML source.

*  [ ] True
*  [x] False

