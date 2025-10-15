# Description
- Think of Fault handling like Validation, it's an answer of a question
- ask your self what if the user tried to access index isn't in the array?? we all know this answer but don't know where it came, well the answer is `segmentation fault` , fault?? yeah this is what we are gonna do.
- we need to make answers for specific questions , but let's list some of them
    1. what if user tried to access index not in the array?
    2. what if user tried to store object 13M but in the memory or heap whatever there's no free space for 13M, what we should do then?
    3. what if user wanted something but it's not in the memory?
    4. question
    5. question
    6. question
    7. question


# Our Mission
- Resolve these problems as efficient as we can 
- answer these questions with a good way without breaking anything 
- we will check a lot of things , as we get a lot of questions we need to ask ourselves many questions as well 
- for example: what if user tried to access index out of boundaries? we take this question and ask ourselves where this array is being stored in the memory we get there and check if it's right accessing or it's illegal?


# Functions
![[Pasted image 20251015181141.png]]