# Maze Turner

## Challenges

Our maze explorer has some weird rules for finding the exit. It is up to you find out if it is possible with the following rules, whether they will escape.

Our explorer has the following rules:
They always walk 6 blocks straight and then turn 180° and start walking 6 blocks again.
If a wall is in their way they turn to the right, if that not possible they turn to the left and if that is not possible, they turn back from where they came.

Legend:
```
>: Explorer looking East
<: Explorer looking West
^: Explorer looking North
v: Explorer looking south
E: Exit
#: wall
 : Clear passage way (empty space)
```

## Example

```python
Enter a maze:
####### 
#>   E#	
#######

Escaped!
```
```python
Enter a maze:
#####E#
#>    #	
#######
Escaped!
```
```python
##########
#>      E#
##########
Trapped!
```

