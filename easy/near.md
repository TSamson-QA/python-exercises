# Near

## Challenge

Create a function that when given two strings of letters, determine whether the second can be made from the first by removing one letter. The remaining letters must stay in the same order.

## Example

```python
>>> near("reset", "rest")
True
>>> near("dragoon", "dragon")
True
>>> near("eave", "leave")
False
>>> near("sleet", "lets")
False
```