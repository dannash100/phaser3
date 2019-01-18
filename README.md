
### coordinates

- (0.0) origin is in top left corner of screen
- down is positive of y, right is positive of x

### scaling

- `obj.setScale(x, y)` multiply sprite dimensions

#### origin

- change origin with `bg.setOrigin(x, y)`

#### init()

- called once
- initiates parameters

#### preload()

- called once
- load external files to memory

#### create()

- called once
- create sprites and display on scene
- sprites render in order of definition
- depth property can also be used to re-define default rendering order.

#### update()

- each frame

### misc

- `this.sys.game.config[width | height]`

- `[flipX | flipY]`
- `setAngle(45) setRotation(Math.PI / 4)`
