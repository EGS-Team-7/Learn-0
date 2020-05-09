





# Never Modify a Scene

 - Scene files _will_ break and are irreparable during a merge conflict.
 - To avoid this happening, _never modify a scene without telling someone_.
 - If two people make changes to a scene, the internal referencing in the file will break.
 - These references mean someone's changes cannot be added.
 - _If you value your time and efforts, do not modify scenes_.
 - Instead, copy the scene and _make a new one_.
 - Alternatively, if you are working on an asset in the scene, **prefab it**, and modify the prefab instead.
     - This is _significantly_ easier to debug than an entire scene in conflict
 - In the example here, you can see two scene files, `SceneOne.unity` and `SceneTwo.unity`
 - Note that they both have a single `cube`, in the exact same position.
 - However, because the cube was deleted, and a new one spawned in its place, the `GUID` is different
     - `GUID` is "**G**lobally **U**nique **ID**entifier". It is essentially a long, random number.
     - This means that _all of the references in the entire scene_ are different, and prevent merging






