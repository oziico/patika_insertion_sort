# Patika.dev Veri Yapıları Ve Algoritmalar Projesi

## Insertion Sort Project:
## [22,27,16,2,18,6] 

## 1-Insertion Sort:
### Write the stages of the above given sequence according to the sort algorithm.

<p>FIRST STEP:
Firstly we need the find least element --> "2"
and after we need the swap "22" and "2"

The  list has become:
[2,27,16,22,18,6]

SECOND STEP:
We need the find least element again -->6
and after we need swap "27 and "6"

The  list has become:
[2,6,16,22,18,27]

THIIRD STEP:
We need the find least element again -->16
But WE DONT NEED SWAP ANY ELEMENT.

The  list has become:
[2,6,16,22,18,27]

FOURTH STEP:
We need the find least element again -->18
and after we need swap "22 and "18"

The  list has become:
[2,6,16,18,22,27]

FIFTH STEP:
We need the find least element again -->22
But WE DONT NEED SWAP ANY ELEMENT.

The  list has become:
[2,6,16,18,22,27]</p>

## 2-BIG-O:
### Write the Big-O notation.
<p>
We have n element
n = 6
We have formula this situation.
Formula : (n*(n+1)/2) equal to (n^2 + n) /2
Our Big-O = O(n^2)
</p>

## 3-TIME COMPLEXITY:
<p>
Time Complexity: 
Average case: The number we are looking for is in the middle
Worst case: The number we're looking for is at the last.
Best case:The number we're looking for is at the very beginning of the list.
</p>

## 4-What case does the number 18 fall into after the array is sorted?
<p>
The list has become after sorting:
[2,6,16,18,22,27]
This situation is included the average case because the number we are looking for is in the middle.
</p>


## [7,3,5,8,2,9,4,15,6] Write the first 4 steps according to the Insertion Sequence.

### Our List [7,3,5,8,2,9,4,15,6] 
<p>
FIRST STEP:

Firstly we need the find least element --> "2"
and after we need the swap "7" and "2"

The  list has become:
[2,3,5,8,7,9,4,15,6]

SECOND STEP:

We need the find least element again -->3
But WE DONT NEED SWAP ANY ELEMENT.

The  list has become:
[2,3,5,8,7,9,4,15,6]

THIRD STEP:

We need the find least element again -->4
and after we need the swap "5" and "4"

The  list has become:
[2,3,4,8,7,9,5,15,6]

FOURTH STEP:

We need the find least element again -->5
and after we need the swap "8" and "5"

The  list has become:
[2,3,4,5,7,9,8,15,6]</p>








