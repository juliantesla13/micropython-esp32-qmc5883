# micropython-esp32-qmc5883
A class for working with the HMC5883L 3-axis digital compass IC with micropython on the esp
# Usage
Upload QNC5883l.py to the micro-controller (e.g. you can use adafruit-ampy) and use as:
  
```python 	
from QMC5883 import QMC5883L
qmc=QMC5883L()
x, y, z, status, temp =qmc.read()
print (x, y, z, status, temp)

```
