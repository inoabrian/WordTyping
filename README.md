# Letter-By-Letter
Javascript plugin that simulates a real time typing text.

###How to use

It's a very easy-to-use function. You just need to pass through the **id** where is the text, and the **speed** you want to load the text.

```html
<h1 id="message">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</h1>

...

<script type="text/javascript">
	var lbl = new LetterByLetter("message", 3);
</script>
```