## EX NO 05(a)

## Aim:
Write a numpy program to replace all odd numbers in the given array with -1.

## Algorithm:
Step 1: Import the NumPy library. <br>
Step 2: Read the input values and create a NumPy array. <br>
Step 3: Check each element of the array. <br>
Step 4: If an element is an odd number, replace it with -1. <br>
Step 5: Display the modified array. <br>

## Program:
```
import numpy as np
a=np.array(eval(input()))
a[a%2!=0]=-1
print(a) 
```

## Output:

<img width="1261" height="306" alt="Screenshot 2025-12-28 131350" src="https://github.com/user-attachments/assets/b65d175f-69ca-40f2-aec9-4062c944be81" />

## Result:
The program is executed successfully.

## EX NO 05(b)

## Aim:
Create a NumPy program using the provided numPy array.return array of items by taking the third column from all rows.

## Algorithm:
Step 1: Import the NumPy library. <br> 
Step 2: Read the input values and create a NumPy array a. <br>
Step 3: Display the input array. <br>
Step 4: Select all rows and the third column of the array and store it in b. <br>
Step 5: Display the elements of the third column. <br>

## Program:
```
import numpy as np
a=np.array(eval(input()))
print("Printing Input Array")
print(a)
print()
b=a[:,2]
print("Printing array of items in the third column from all rows")
print(b)
```

## Output:

<img width="1329" height="492" alt="Screenshot 2025-12-28 131803" src="https://github.com/user-attachments/assets/a891a59f-2d50-4a64-a58c-9b3b2c21ab70" />

## Result:
The program is executed successfully.

## EX NO 05(c)

## Aim:
Create a numpy program using the absolute builtin function of numpy to print absolute value of given numpy array.

## Algorithm:
Step 1: Import the NumPy library. <br>
Step 2: Read the input values and create a NumPy array a. <br>
Step 3: Find the absolute value of each element in the array. <br>
Step 4: Display the resulting array. <br> 

## Program:
```
import numpy as np
a=np.array(eval(input()))
print(abs(a))
```

## Output:

<img width="1261" height="342" alt="Screenshot 2025-12-28 132132" src="https://github.com/user-attachments/assets/df80f38d-2f22-4582-a4b3-6b5fad3b34d3" />

## Result:
The porgram is executed successfully.

## EX NO 05(d)

## Aim:
Create a pandas program to get the positions of items of series A in another series B.

## Algorithm:
Step 1: Import the Pandas library. <br>
Step 2: Read the input values and create Series A. <br>
Step 3: Read the input values and create Series B. <br>
Step 4: For each element in Series B. <br>
Step 5: Find the position (index) of the same value in Series A. <br>
Step 6: Store the index in a list. <br>
Step 7: Display the list of indices. <br>

## Program:
```
import pandas as pd
A=pd.Series(eval(input()))
B=pd.Series(eval(input()))
result=[A[A==x].index[0] for x in B]
print(result)
```

## Output:

<img width="1247" height="308" alt="Screenshot 2025-12-28 132556" src="https://github.com/user-attachments/assets/85a3e7dc-b48a-41b7-a3cc-9a9dbe1f12e7" />

## Result:
The program is executed successfully.

## EX NO 05(e)

## Aim:
Write a Python Pandas program first to carry out the Multiplication mathematics operations for the following two series a1 and a2.

## Algorithm:
Step 1: Import the Pandas library. <br>
Step 2: Read the input values and create the first Series a1. <br>
Step 3: Read the input values and create the second Series a2. <br>
Step 4: Multiply the corresponding elements of both Series. <br>
Step 5: Store the result in a new Series. <br>
Step 6: Display the multiplied Series. <br>

## Program:
```
import pandas as pd
a1=pd.Series(eval(input()))
a2=pd.Series(eval(input()))
result=a1*a2
print("Multiplication of two Series:")
print(result)
```

## Output:

<img width="1338" height="542" alt="Screenshot 2025-12-28 133040" src="https://github.com/user-attachments/assets/ee877107-df21-43f7-9ea7-d5f22caa8896" />

## Result:
The program is executed successfully.
