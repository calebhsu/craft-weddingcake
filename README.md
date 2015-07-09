# craft-weddingcake

Parameterized cake model.

### Usage
```html
<craft>
    <craft name="cake" module="craft-weddingcake"/>
    <cake></cake>
</cake>
```
 
### Parameters
- width: adjusts width of cake base
    - default: 30
- height: adjusts height of cake base
    - default: 10
- tiers: adjusts number of cake layers
    - default: 2
- beadNumber: adjusts number of decorative beads
    - default: 10

### Example
```html
<craft>
    <craft name="cake" module="craft-weddingcake"/>
    <craft name="candle" module="craft-candle"/>
    <row spacing="1">
        <cake width="25" height="1"/></cake>
        <stack>
            <candle height="20" width="5" t="scale(0.3,0.3,0.3)"></candle>
            <cake></cake>
        </stack>
    </row>
</craft>
```

![example](example.png)
