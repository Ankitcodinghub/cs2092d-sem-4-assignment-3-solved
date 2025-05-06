# cs2092d-sem-4-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [CS2092D Sem 4 Assignment 3 Solved](https://www.ankitcodinghub.com/product/cs2092d-sem-4-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97470&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2092D Sem 4 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
QUESTIONS

1. Write a program to create an AVL TREE A and perform the operations insertion, deletion, search and traversal. Assume that the AVL TREE A does not contain duplicate values. Your program should contain the following functions.

• INSERT(A, k) — Inserts a new node with key ‘le into the tree A.

• SEARCH(A, k) – Searches for a node with key k in A, and returns a pointer to the node with key k if one exists; otherwise, it returns NIL.

• DELETENODE(A,k) — Deletes a node with the key ‘le from the tree A.

Note: The caller of this function is assumed to invoke SEARCH() function to locate the node x.

• GETBALANCE(A,k) — Prints the balance factor of the node with k as key in the tree A. Note:- Balance factor is an integer which is calculated for each node as:

B_factor = height(left_subtree) — height(right_subtree)

• LEFTROTATE(A,k) — Perform left rotation in the tree A, with respect to the node k.

• RIGHTROTATE(A,k) — Perform right rotation in the tree A, with respect to node k.

• IsAVL(A) — Checks whether the tree pointed by A is an AVL tree or not.

• PRINTTREE(A) — Prints the tree given by A in the paranthesis format as: ( t ( left-subtree )( right-subtree ) ). Empty parentheses ( ) represents a null tree.

Note: After each insertion on an AVL TREE, it may result in increasing the height of the tree. Similarly, after each deletion on an AVL TREE, it may result in decreasing the height of the tree. To maintain height balanced property of AVL tree, we need to implement rotation functions.

Input Format:

• Each line contains a character from `V, ‘cl’, ‘s’, ‘b’, `13′ and ‘e’ followed by at most one integer. The integers, if given, are in the range [-106, 1061.

• Character ‘V is followed by an integer separated by space; a node with this integer as key is created and inserted into A.

• Character ‘cl’ is followed by an integer separated by space; the node with this integer as key is deleted from A and the deleted node’s key is printed.

• Character ‘s’ is followed by an integer separated by space; find the node with this integer as key in A.

• Character ‘V is followed by an integer separated by space; find the balance factor of the node with this integer as key in A and the print the balance-factor.

• Character `p’ is to print the PARENTHESIS REPRESENTATION of the tree A.

• Character ‘e’ is to ‘exit’ from the program.

Output Format:

• The output (if any) of each command should be printed on a separate line.

• For option ‘cl’, print the deleted node’s key. If a node with the input key is not present in A, then print FALSE.

• For option ‘ s’ , if the key is present in A, then print TRUE. If key is not present in A, then print FALSE.

• For option ‘b’, if the key k is present in A, then print the balance factor of the node with k as key. If key is not present in A, then print FALSE.

• For option “73′, print the space-separated PARENTHESIS REPRESENTATION of the tree A.

Sample Input:

i4

i6

i3

i2

i1

s2

P

b4 d3 P

Sample Output:

TRUE

(4(2(100)(30()))(60()))

1

3

(4 ( 2 ( 1 00)())( 6 00))

2. Given an array of n integers with any of these integers appearing any number of times. Write a program to sort these n integers in (9(nlogm) time, where m is number of distinct elements in array.

Hint: Use AVL tree. The idea is to extend tree node to have count of keys also. Each node in the tree is of the following type.

Struct node{ int key;

int count;

int height;

struct node *left; struct node *right; } //number of times a key appears in the array

Input Format:

• The first line of the input contains an integer n E [1, 100], number of elements in the array.

• Second line containing space separated integers of the array. The integers are in the range [-106,106]

Output Format:

• Single line containing space separated integers of the given input array in non-decreasing order.

Sample Input:

12

100 12 100 1 1 12 100 1 12 100 1 1 Sample Output:

1 1 1 1 1 12 12 12 100 100 100 100

3. A Red-Black tree is a self-balancing binary search tree where every node obeys the following rules.

(a) Every node is either red or black

(b) The root is always black

(c) There are no two adjacent red nodes (A red node cannot have a red parent or red child)

(d) All paths from a node to descendant nodes contain the same number of black nodes

Write a program to create a Red Black Tree from the given input. Your program should include the following function

• INSERTREDBLACK(struct node* root, key) : Inserts a new node with the ‘key’ into the tree and prints parenthesized representation (with corresponding colors) of the created red-black tree.

Input Format:

• Each line of the input contains a positive integer “key” or a character ‘t’. If the input is a positive integer then Call function INSERTREDBLACK(root, key). If ‘t’ is encountered, terminate the program.

Output Format:

• For each line of the input, the corresponding line of the output should contain the parenthesis representation (key value followed by color) of the current tree.

Sample Input:

25 18 50 80 12 100

34 t

Sample Output:

( 25 B 0 0 )

( 25B( 18 R()())0)

( 25B( 18 ROW( 50 ROW)

( 25B( 18 BOW( 50 B()( 80 R() ())))

( 25B( 18 B( 12 R0())())( 50 B()( 80 R()())))

( 25B( 18 B( 12 R0())())( 80B( 50 R()())( 100 R()())))

( 25B( 18 B(12 R0())())( 80R( 50B( 34 R0())())( 100 BO OM

4. Write a program to implement a BINOMIAL HEAP and perform the operations insertion, deletion, extract_minimum and union. Your program should contain the following functions:

• MAKEHEAP() – Creates and returns a new heap H containing no elements.

• INSERT(H, x) — Inserts a new node with key ‘x’ into the heap H.

• MINIMUM(H) — Return the value of the smallest key in the heap H.

• ExTRAcTMIN(H) — Deletes the node with minimum key value from heap H.

• DECREASEKEY(H, x, k) — If the node of H with key ‘x’ is at least ‘k’, then decreases the value of node with key ‘x’ by ‘k’. Otherwise, it print -1.

• DELETE(H, x) – Deletes the node with key ‘x’ from the heap H. If node is not present, then print -1.

• UNION(H1, H2) – Create and return a new heap H that contains all the nodes of heaps H1 and H2. Heaps H1 and 112 are “destroyed” by this operation.

Input Format:

• Each line contains a character from ‘i’, ‘m’, ‘x’ , ‘r’, ‘d’ and `e’ followed by at most one integer. The integers, if given, are in the range [-106,1061.

• i k – inserts k into the heap

• d k – deletes node k from the heap

• p – prints the binomial heap

• m – prints the minimum element in the binomial heap (Note:- In print function, level order traversal is to be used).

• x – extracts the minimum element from the heap

• r y z – decreases the value of node with key y by z.

• e – ‘exit’ from the program.

Output Format:

• The output (if any) of each command should be printed on a separate line.

Sample Input:

i 10

i 20

i 30

i 40

i 50

P m

x

P

 50 4

P

 70 5

Sample Output:

50 10 10 20 46 20 -1 10

30

30 30

40

40 20

50

46 40

5. Write a program to implement a FIBONACCI HEAP and perform the operations insertion, deletion,

extract_minimum, decrease_key and union. Your program should contain the following functions:

• MAKEHEAP 0 – Creates and returns a new heap H containing no elements.

• INSERT(H, x) — Inserts a new node with key ‘x’ into the heap H.

• MINIMuM(H) — Returns a pointer to the node in heap H whose key is minimum.

• ExTRAcTMIN(H) — Deletes the node with minimum key value from heap H.

• DECREASEKEY(H, x, k) – Decreases the value of node ‘x’ of the heap H by ‘k’, If node x’s key is at least ‘k’. Otherwise, it returns NIL.

• DELETE(H, x) – Deletes the node with key ‘x’ from the heap H. (If node not present, it returns NIL)

• UNIoN(Hi, H2) – Create and return a new heap H that contains all the nodes of heaps H1 and H2. Heaps H1 and H2 are “destroyed” by this operation.

Input Format:

• Each line contains a character from ‘i’, ‘m’, ‘x’, ‘r’, ‘cl’ and `e’ followed by at most one integer. The integers, if given, are in the range [-106,106].

• i k – inserts k into the heap

• d k – deletes node k from the heap

• p – prints the Fibonacci heap (Note:- In print function, level order traversal is to be used).

• m – prints the minimum element in the Fibonacci heap

• x – extracts the minimum element from the heap

• r y z – decreases the value of node with key y by z.

• e – ‘exit’ from the program.

Output Format:

• The output (if any) of each command should be printed on a separate line.

Sample Input:

i 10 i 20 i 30 i 40 i 50 m

x

P

r 50 15

P

Sample Output:

10

10

20 30 40 50

35

20 30 40 35

6. Write a program that implements the DISJOINT-SET data structure using rooted forests. Also,write functions to implement the ranked union and path compression heuristics on your data structure, and compute the efficiency of the disjoint set data structure find operation by applying neither, either or both of the heuristics, by counting the total number of data accesses performed over the course of the program. Your program must support the following functions:

• MAKESET(X) – creates a singleton set with element x.

• FIND(x) – finds the representative of the set containing the element x.

• umoN(x,Y) – merges the sets containing elements x and y into a single set. The representative of the resultant set is assigned with find(x) , unless the ranked union heuristic is used and the ranks of both find(x) and find(y) are different. Otherwise,the representative is assigned in accordance with the ranked union heuristic.

• Note that looking up an element in the data structure must be done in 0(1) time. Input Format:

• The input consists of multiple lines, each one containing a character from f`m’, ‘f’, `u’, ‘s’l

followed by zero, one or two integers. The integer(s), if given, is in the range 0 to 10000.

— Call the function makeset(x) if the input line contains the character ‘m’ followed by an

integer x . Print -1 if x is already present in some set, and the value of x, otherwise.

— Call the function find(x) if the input line contains the character ‘f’ followed by an integer x Output the value of find(x) if x is found, and -1, otherwise.

— Call the function union(x,y) if the input line contains the character ‘u’ followed by space separated integers x and y . Print -1, without terminating, if either x or y isn’t present in the disjoint set. Print find(x) itself if find(x)=find(y) . Otherwise, print the representative of the resultant set. The representative of the resultant set is assigned with find(x), unless the ranked union heuristic is used and the ranks of both find(x) and find(y) are different. Otherwise, the representative is assigned in accordance with the ranked union heuristic.

— If the input line contains the character ‘s’, print the number of data accesses performed by the find commands by each of the data structures over the course of the program and terminate.

Output Format:

• The output consists of multiple lines of space-separated columns. The columns correspond to the following disjoint-set data structures:

a. with neither ranked union nor path compression applied.

b. with only ranked union applied.

c. with only path compression applied.

d. with both ranked union and path compression applied.

• Each line in the output contains the output of the corresponding line in the input, after applying to the respective data structures.

• The last line of the output contains the number of data accesses performed by the find com¬mands by each of the data structures over the course of the program.

Sample Input

ml

m2

m3

m4

m5

m6

m7

m8

m9

u 1 2

u 3 4

u 5 6

u 7 8

u 9 8

u 6 8

u 4 8

u 2 8 f9

m 10

u 10 9 s

Sample Output

1

2

3

4

5

6

7

8

9

1 1 1 1 3333 5555 7777 9797 5555 3535 1 5 1 5 1 5 1 5

10

10 5 10 5

38 32 33 30
