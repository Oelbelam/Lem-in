# Lem-in
a program that manage the flow of fictional ants going from a starting point to an end point, a node can contain only one ant, the goal of the program is to have the minimum instructions with the shortest paths.

## Usage :
you must generate a map with the generator in the root folder and put it in file 
```
  ./generator --flow-one > file
```  
 # options:
 ```
	--help : to read the manual
	--flow-one : generates an ant farm with distinctive path and [1] ant in it
	--flow-ten : generates an ant farm with distinctive path and approximately [10] ants in it
	--flow-thousand : generates an ant farm with distinctive path and approximately [100] ants in it
	--big : generates a big map (approximately [1000] rooms) to test the time complexity
	--big-superposition : generates a big map with overlapping paths
```
and then you should make the project using make and then execute the programe by redirect the file 
```
./lem-in < file
```

# Out put
```
[File Contnent]

L[number]-[node]
```
