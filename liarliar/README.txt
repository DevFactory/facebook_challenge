Liar, Liar

As a newbie on a particular internet discussion board, you notice a distinct trend among its veteran members; everyone seems to be either unfailingly honest or compulsively deceptive. You decide to try to identify the members of the two groups, starting with the assumption that every senior member either never lies or never tells the truth. You compile as much data as possible, asking each person for a list of which people are liars. Since the people you are asking have been around on the board for a long time, you may assume that they have perfect knowledge of who is trustworthy and who is not. Each person will respond with a list of people that they accuse of being liars. Everyone on the board can see that you are a tremendous n00b, so they will grudgingly give you only partial lists of who the liars are. Of course these lists are not to be taken at face value because of all the lying going on. 

You must write a program to determine, given all the information you've collected from the discussion board members, which members have the same attitude toward telling the truth. It's a pretty popular discussion board, so your program will need to be able to process a large amount of data quickly and efficiently. 


Input Specifications

Your program must take a single command line argument; the name of a file. It must then open the file and read out the input data. The data begins with the number of veteran members n followed by a newline. It continues with n chunks of information, each defining the accusations made by a single member. Each chunk is formatted as follows:
 <accuser name> <m>
followed by m lines each containing the name of one member that the accuser says is a liar. accuser name and m are separated by some number of tabs and spaces. m will always be in [0, n]. All member names contain only alphabetic characters and are unique and case-sensitive. 

Output Specifications

Your output must consist of two numbers separated by a single space and followed by a newline, printed to standard out. The first number is the size of the larger group between the liars and the non-liars. The second number is the size of the smaller group. You are guaranteed that exactly one correct solution exists for all test data. 

Example output:
3 2