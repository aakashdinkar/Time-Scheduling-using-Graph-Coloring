# Time-Scheduling-using-Graph-Coloring
  A timetable can be thought of as an assignment of timeslots to different events in any institution. So, we made this simple “Scheduling     of Class timetable using Graph Coloring” where each color denotes a particular time slot. Time slots are reserved for each course and       semester according to various factors.
  
## Graph-Coloring
  Graph coloring problem is to assign colors to certain elements of a graph subject to certain constraints. Vertex coloring is the most       common graph coloring problem. The problem is, given m colors, find a way of coloring the vertices of a graph such that no two adjacent     vertices are colored using same color. The other graph coloring problems like Edge Coloring and Face Coloring  can be transformed into     vertex coloring. 
 
## Applications
*Making Schedule or Time-Table*</br> 
*Mobile Radio Frequency Assignment*</br>
*Sudoku*</br>
*Register Allocation*</br> 
*Map Coloring*</br>

## Implementation
We used Python programming language.</br>
**Imported Packages:**</br>
pandas              - for file handling</br>
numpy               - for arrays</br>
itertools           - for iterating values</br>
matplotlib.pyplot   - for plotting the points</br>
networkx            - for graph making</br>

## Result
After using graph coloring concept, we are able to find timeslots for each subject.</br> Let's generate the time table:</br> 
![Result](https://raw.githubusercontent.com/aakashdinkar/TIme-Scheduling-using-Graph-Coloring/master/result.png)</br>
Here, if any student has recourse for previous semesters then he/she can attend those classes. If no recourse, then class of particular semester can take place at same time without any modification. 



 
