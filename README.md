# CS471-Assignment6
Homework Assignment 6
YOU NEED TO READ
Chapter 3: pgs 115-125 (up to 3.3)
Chapter 8: pgs 388-398 (8.5)


THIS ASSIGNMENT MAY BE DONE INDIVIDUALLY OR IN TEAMS OF UP TO 4 (no more than 4 members) .

DUE Tuesday, March 3 at 11:59.   Note Test 1 will be on Wed, March 4.

SUBMIT a txt. CODE FILES MUST be tar'd. It would be a good idea if you copied the questions from the text book before your answers (though this is not absolutely required).

ALL GROUP MEMBERS MUST BE LISTED ON THE TOP OF THE FILE.  All members must submit the SAME assignment.  If you use sources (including the textbook) for you answer -- you need to reword and cite the source.  Answers should be short and to the point.
Page 167 exercise 3.1

In assignment 1 problems 2 and 3 you studied  iterative and functional versions of the pow function.  Download and compile powR.c to assembly code on your machine: Use the command gcc -S powR.c You can run this remotely on the department machines by ssh remote.cs.binghamton.edu -l<your id>
Give a table for the activation record for powR() based on the assembly code generated.   Each entry should include a relative address and what is stored at that location. Relative addresses should be consistent with the assembly. The activation record should include the return address and everything on the stack between the return address and the return address in the next frame.
Which way does the program stack grow? (i.e. towards higher addresses or lower addresses?)
Annotate the powR.s file.  Indicate all the instruction that read, write, "create" or "delete" the stack memory.  Name the fields affected by instruction. 
e.g
31::  movl    $13, -4(%ebp) -- copies the value to the "n" argument field in the AR.

Now compile powR.c to assembly code on your machine using the command "powR -O2 -S powR.c". Compare the assembly file created using optimization switch, -O2, with the assembly file created without optimization (from the previous problem).  Pay attention to how pow's recursion is "implemented".  How are they different?

Many storage-management algorithms maintain a list of free blocks.  Here are two different algorithms, first fit and best fit, used to search this list and return a block of the appropriate size.  Which strategy, if either, will result in lower external fragmentation?  What does external fragmentation depend on?

What is the complexity of using first fit algorithm to allocate blocks?  Briefly explain an algorithm to speed up the allocation. What is the complexity of this modification?

Page 398 cyu # 26.  Your answer should be both concise and complete.



l fragmentation?  What does external fragmentation depend on?

What is the complexity of using first fit algorithm to allocate blocks?  Briefly explain an algorithm to speed up the allocation. What is the complexity of this modification?

Page 398 cyu # 26.  Your answer should be both concise and complete.


