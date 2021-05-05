# Rubix Cube

## Challenge

A rubix cube has 6 sides: Front (F), Back (B), Up (U), Down (D), Left (L), Right (R). 

Given a rubix cube configuration, have a series of actions run until a solved rubix cube is outputted.

Actions:
- F (Front): the side currently facing the solver
- B (Back): the side opposite the front
- U (Up): the side above or on top of the front side
- D (Down): the side opposite the top, underneath the Cube
- L (Left): the side directly to the left of the front
- R (Right): the side directly to the right of the front
- x (rotate): rotate the entire Cube on R
- y (rotate): rotate the entire Cube on U
- z (rotate): rotate the entire Cube on F
- A number after the letter indicated the number of turns. F2 indicates turn the front side two times clockwise. 


# Example

```bash
Front  Down  Back  Left  Up   Right
444    331   555   112   220  003
003    331   112   444   220  555
005    551   114   333   440  222
Moves to solve:
U1, R3, F3
```