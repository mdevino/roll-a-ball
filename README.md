# Roll A Ball

Project created by following this [Unity tutorial](https://learn.unity.com/project/roll-a-ball).


## Notes

* `Update()` is called before a frame is redenred, while `FixedUpdate()` is called before every physics calculation.
* `LateUpdate()` runs after every `Update()` method is run.
* The "Is Trigger" property of colliders is used to use them for events, rather than physics.
* `Time.deltaTime` contains the time elapsed since the last frame update.