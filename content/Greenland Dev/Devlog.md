# 12/27/23
Trying to implement: `if the player is not moving, then adds '_idle' to the end`. The trick is that you have to prevent double adding idle.
```python
def getStatus(self):  
    # If the player is not moving, then add adds idle  
    if self.direction.magnitude() == 0:  
        self.status += "_idle"
```
![[Pasted image 20231227203553.png]]
___


