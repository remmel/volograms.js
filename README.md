# volograms-js
Volograms JS Reader for Threejs

[demo](https://remmel.github.io/volograms-js) [example src](https://github.com/remmel/volograms-js/blob/main/src/demo.js)

```javascript
import {Vologram} from "./Vologram"
let vologram = new Vologram(url, p => console.log("loading...", p))
scene.add(vologram)

function animate() {
    ///...
    vologram.update() //to animate the vologram
}
```
