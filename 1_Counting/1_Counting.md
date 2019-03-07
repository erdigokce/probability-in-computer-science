
# Report of Pigeonhole Principle

This program determines that at least 6 of the visitors came from same city in a website which has 412 monthly visitors from Turkey.

## Implementation

In order to use *ceil* function **math** library is imported.


```python
import math
```

**412** : total number of monthly visitors from Turkey (*pigeons*)


```python
NUMBER_OF_MONTHLY_VISITORS = 412.0
```

**81** : total number of cities of Turkey (*pigeonholes*)


```python
NUMBER_OF_CITIES_IN_TURKEY = 81
```

Output : 


```python
print('At least ' + str(int(math.ceil(NUMBER_OF_MONTHLY_VISITORS / NUMBER_OF_CITIES_IN_TURKEY))) + ' of the visitors hit the website from same city.')
```

    At least6 of the visitors hit the website from same city.

