





# The Importance of Prefabs

 - Prefabs are an essential part of not screwing up in Unity
 - Using prefabs _everytime_ is good practice, and especially when you nest them.
 - Open this project in Unity, and change all of the `Cube`'s materials to blue in `NoPrefabs.unity`
 - Notice that it takes a _very_ long time to do because you either need to select all of the `Cube`s in the environment, or need to visit each and every one of them
 - Now open `WithPrefabs.unity`, and do the same
 - Instead of needing to hunt down every last `Cube` in the scene, you can instead select the `Cube`, `open prefab` in inspector, and modify it _once_
 - Also note the differences between `NoPrefabs.unity` and `WithPrefabs.unity`:
     - _Every_ object in `WithPrefabs.unity` is a prefab. This makes the scene file _significantly_ smaller and easier to version, and means conflicts are less frequent
     - This also means that if the scene is lost or deleted, that all of the components within that scene can still be used.
 - The big lesson here is _always prefab_. You should never just 'Create a Cube' in a scene.
     - If the object you are creating has any amount of detail or appears more than once, **prefab it**






