# Word typing effect
Javascript plugin that simulates a real time typing text. This plugin/function is a wip, so will be updated soon.

You can see an example working [here](http://jordillobet.es/projects/letter-by-letter/).

###How to use

It's a very easy-to-use function. You just need to pass the **id** where the text is, and the **speed* *you want to load the text at.

```html
<h1 id="message">This is a simple text example</h1>

...

<script type="text/javascript">
	var wt = new WordTyping("message", 3);
	
	// Added support for callbacks to enable chaining events
	// added by : inoabrian
	new WordTyping("1", 5, function(){
		console.log('1 is done.');
		new WordTyping('2', 2, function(){
			console.log('2 is done.');
		});
	});
</script>
```

======
Jordi Llobet | newpatriks@gmail.com 
