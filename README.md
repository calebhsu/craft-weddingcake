# craft-weddingcake

Parameterized cake model.

### Install
	$ npm install craft-weddingcake
 
### Parameters
- width: adjusts width of cake base
- height: adjusts height of cake base
- tiers: adjusts number of cake layers

### Example
```html
<craft>
	<craft name="cake" module="calebhsu/craft-weddingcake"/>
	<craft name="candle" module="calebhsu/craft-candle"/>
	<row>
	    <cake height="1" tiers="2"/></cake>
    	<stack>
    		<scale factor="0.3">
    			<candle height="20" width="5"></candle>
    		</scale>
    		<cake tiers="1"></cake>
    	</stack>
        <cake></cake>
	</row>
</craft>
```

![example](example.png)
