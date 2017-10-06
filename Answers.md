
-TODO also try with a LinkedList - does it make any difference?
The linked list didn't really make a difference in how the program ran. They both produced the same results

-list.remove(5); // what does this method do?
Goes to the value occupying the 5th in the size and removes it. What would be the 6th value in the overall size is now the 5th value.

-TODO what happens if you use list.remove(77)?
list.remove(77) would cause the an error because there isn't a 77 position in the list. list.remove("77") would make more sense.

-which of the two lists performs better as the size increases?
A Array List is more efficient for bigger sizes than the Linked List.

-list.remove(Integer.valueOf(5)); // what does this one do?
It returns the Int object of 5. Not to be mistaken with returning the index. 
