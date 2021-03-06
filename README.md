## Delete-the-second-column-from-a-given-array-and-insert-the-following-new-column-in-its-place.-sample
## Sample code to check the details for the Month
```sh
import numpy

print("Printing Original array")
sampleArray = numpy.array([[34,43,73],[82,22,12],[53,94,66]]) 
print (sampleArray)

print("Array after deleting column 2 on axis 1")
sampleArray = numpy.delete(sampleArray , 1, axis = 1) 
print (sampleArray)

arr = numpy.array([[10,10,10]])

print("Array after inserting column 2 on axis 1")
sampleArray = numpy.insert(sampleArray , 1, arr, axis = 1) 
print (sampleArray)

```
## Example Output
Printing Original array
[[34 43 73]
 [82 22 12]
 [53 94 66]]

Array after deleting column 2 on axis 1
[[34 73]
 [82 12]
 [53 66]]

Array after inserting column 2 on axis 1
[[34 10 73]
 [82 10 12]
 [53 10 66]]
