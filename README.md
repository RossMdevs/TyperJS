[Demo - V3 SITE](https://rossmers.ch) | [Download](#) 


1. Download the Typer.js file. It's only 3KB!

2. Place a link to the Typer.js script at the bottom of your html file.

If you want to self-host the JS: ```<script src="location/of/your/typer.js"></script> ``` 
OR
If you don't want to self-host the JS: ```<script async src="https://unpkg.com/typer-dot-js@0.1.0/typer.js"></script>```


3. Place a typer and cursor into your html file, like this:

```<h1>Typer.js is
  <span class="typer" id="main" data-words="great,fun,lightweight,easy" data-colors="white" data-delay="100" data-deleteDelay="1000"></span>
  <span class="cursor" data-owner="main"></span>
</h1>
<p>the typing effect with a pure HTML interface</p>
