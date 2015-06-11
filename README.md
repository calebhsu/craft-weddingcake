# craft-weddingcake

Parameterized cake model.

### Install
    $ npm install craft-weddingcake
 
### Parameters
- width: adjusts width of cake base
- height: adjusts height of cake base
- tiers: adjusts number of cake layers
- beadNumber: adjusts number of decorative beads

### Example
```html
<craft>
    <craft name="cake" module="calebhsu/craft-weddingcake"/>
    <craft name="candle" module="calebhsu/craft-candle"/>
    <row spacing="1" align="y50">
        <cake width="25" height="1"/></cake>
        <stack align="x50 y50">
            <candle height="20" width="5" transform="scale(0.3,0.3,0.3)"></candle>
            <cake></cake>
        </stack>
    </row>
</craft>
```

![example](example.png)
