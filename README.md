# craft-weddingcake

Parameterized cake model.

### Install
	$ npm install craft-weddingcake
 
### Parameters
- size: scales model
- width: adjusts width of cake base
- height: adjusts height of cake base
- tiers: adjusts number of cake layers

### Example
```html
<craft>
	<craft name="cake" module="craft-weddingcake"/>
	<craft name="candle" module="craft-candle"/>
	<cake height="1" tiers="2"/></cake>
	<stack>
		<candle height="20" width="5" size="0.3"></candle>
		<cake tiers="1"></cake>
	</stack>
	<cake></cake>
</craft>
```

![example](example.png)
