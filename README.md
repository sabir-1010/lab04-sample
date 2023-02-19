# Sample_solution_W23-lab04_assignment


## Sample Solution: TASK2
 
```python
midtermMarks = [48.0, 64.25, 71.80, 82.0, 53.45, 59.75, 62.80, 26.5, 55.0, 67.5, 70.25, 52.45, 66.25, 94.0, 65.5, 34.5, 69.25, 52.0]

##you code here
CountA= 0
CountB= 0
CountC= 0
CountD= 0
CountF= 0
for marks in midtermMarks:
    if marks>= 0 and marks <50:
        CountF = CountF + 1
    elif marks>= 50 and marks <60:
        CountD = CountD + 1
    elif marks> 60 and marks<70:
        CountC= CountC+1
    elif marks>= 70 and marks< 80:
        CountB = CountB + 1
    elif marks>= 80 and marks< 100:
        CountA = CountA + 1
print("Number of As:", CountA)
print("Number of Bs:", CountB)
print("Number of Cs:", CountC)
print("Number of Ds:", CountD)
print("Number of Fs:", CountF)
```
