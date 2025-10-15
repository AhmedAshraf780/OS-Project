
# Description
- What if i told you put this empty box in your little room and after x minutes i will come and put something inside it, isn't that a load to you?? cause you are putting empty box that takes some spaces in your room waiting for this guy to come and put sth inside it , is it logical?? ofcourse not, so what we should do in this case?
- because our room is not big, and we only need to put this box if this box's not empty, so 
- we will receive this empty box that i took from the guy and put it in other room or any other place but our little room, and whenever this guy comes with the thing he wants to put it inside the box we'll move this box to our little room, with this approach we saved our room from distraction and did our mission successfully, win win , this is what we call `kernel Heap`
- `Taking couple of addresses that we don't know what to store in them at the same time we don't need to take these addressess from the memory, it would be non sense`
- Example: `int x = malloc(sizeof(int))` , this tells us put this x in the memory, but don't store any value in it, but the question is `Is that we will do???`

# Our Mission
- Understand what's the `block allocator` and `page allocator`
- Make this kernel Heap as efficient as we can 
- we will take the virtual address from the system call function
- store this virtual address with some sort of pagging tricks in the kernel heap
- moving these address to the memory when it get accessed and mark some bits in 
- its address that it's in memory now

# Functions
1. ![[assets/Pasted image 20251015175336.png]]


2. ![[assets/Pasted image 20251015175359.png]]
3. ![[assets/Pasted image 20251015175438.png]]
4. ![[assets/Pasted image 20251015175458.png]]
5. ![[assets/Pasted image 20251015175509.png]]
6. ![[assets/Pasted image 20251015175522.png]]
7. ![[assets/Pasted image 20251015175559.png]]
8. ![[assets/Pasted image 20251015175536.png]]
# Bonus
![[assets/Pasted image 20251015175626.png]]
