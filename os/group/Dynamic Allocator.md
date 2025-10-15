# Description
- In this section we need to handle the data at the runtime, what I mean by the runtime is
- we don't know where to put this variable in the memory cause it's created by dynamic allocator
- Example: `int arr = new int[33]`
- this arr which its size is 33*4 is stored in the `heap`, why? because I don't know what values
- should i put in the memory, that's why we are putting this array in the heap and at the runtime
- when we try to use this array we will store them from the `heap` to the memory because we now
- know exactly what values we'll store, make sense right

# Our Mission
- Make this heap, provide this dynamic allocation to the user, we need to make code
- that tells the user you wanna create dynamic array? not a big deal we will handle it in the heap
- Tells the user you wanna store, access value in this dynamic array? not a big deal, we will
- handle the moving from the heap to the memory and your data will be in the memory safely.


# Functions will be created
1. 
![[assets/Pasted image 20251015173106.png]]
2. ![[assets/Pasted image 20251015173133.png]]
3. ![[assets/Pasted image 20251015173153.png]]
4. ![[assets/Pasted image 20251015173210.png]]
# Bonus
![[assets/Pasted image 20251015173314.png]]

