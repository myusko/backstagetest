# An amazing documentation

## Code
```python
class A:
    def __init__(self, value: int):
        self.value = value
    
    def __eq__(self, other):
        return self.value == other.value

  
a1 = A(1)
a2 = A(2)

assert a1 == a2
```
