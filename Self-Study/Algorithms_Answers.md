## Excercise I

a) O(n) 

b) O(n**2)

c) O(1) (or O(0) because of the bug)

## Exercise II
Set _f_ to _n_/2

Drop an egg off of the _f_ story
If the egg breaks 
  set _n_ to _f_ and _f_ to _n_/2 (half the distance to the ground)
Else
  set _f_ to _f_ + _n_ - _f_ / 2 (half the distance between the lowes broken level)

continue doing this until _n_ - _f_ = 1 (one floor difference)