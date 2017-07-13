# Space-animation
Animation space intro with awesome text rotator

### Live preview
<a href="http://demo.eadhassan.com/space" target="_blank">Demo</a>

### Usage
  1. Enter your text for text rotator like below
```html
<h1 class="tlt">
  <ul class="texts">
    <li>Web developer</li>
    <li>Web designer</li>
    <li>Graphic designer</li>
  </ul>
</h1>
```
  2. customize In & Out effects
```javascript
$('document').ready(function(){
  $('.tlt').textillate({
    loop: true, 
    type: 'char', 
    out: { effect: "bounceOutRight", reverse: true },  // Enter any class from animate.css
    in: { effect: "bounceInLeft"} // Enter any class from animate.css
  });
});
```

### Credits
Here is the list of the awesome resources we used to create this template.
  1. jQuery <a href="https://jquery.com/">website</a>
  2. animate.css <a href="https://daneden.github.io/animate.css/">website</a>
  3. fittext.js <a href="http://fittextjs.com">website</a>
  4. jquery lettering <a href="http://letteringjs.com/">website</a>
  5. textillate <a href="http://textillate.js.org/">website</a>
  
