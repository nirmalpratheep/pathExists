## Packages Required
```
pip install -q pillow matplotlib imageio
```
## Version
```
Python version >=3.0
```

## Functions
```
findPath_astar()
```
Description: A* pathfinding algorithm implementation.



```
pathExists(startPos,endPos,imgPath,visualize=False)
```
Description:
Check if a path exists between startPos and endPos in the image at imgPath.
If a path exists, color it in the image and save the result.

    

```
multiPathExists(startPosList, endPosList, imgPath, visualize)
```
Description: Check if multiple paths exist between startPosList and endPosList in the image at imgPath.
If paths exist, color them in the image and save the result.
    
    
