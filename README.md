# Leetcode-GeekForGeeks-Coding-Problems---Python-Programming  & Java Programming 
QUESTION : (Python Programming Question)
There are two friends, John and Smith, and the parameters j_angry and s_angry to indicate if each is angry. You are in trouble if both of them are angry or no one of them is angry.

Now, complete the function which returns true if you are in trouble, else return false

Example 1:

Input:
j_angry = True, s_angry = True
Output:
True
Explanation:
Since both of them are angry, you are in trouble.


Example 2:

Input:
j_angry = True, s_angry = False
Output:
False
Explanation:
Only one of them is angry, you are not in trouble.

Solution Python Code : 

def friends_in_trouble(j_angry, s_angry):
    if (j_angry == True and s_angry == True):
        return True
    if (j_angry is False and s_angry is False):
        return True
    return False

Question 2 :
Given a positive integer x. Your task is to check, if it is even or odd (Any number that gives zero as remainder when divided by 2 is an even number)

Examples

Input: x = 4
Output: Even
Input: x = 5
Output: Odd
Your Task:

Your task is to complete the function checkOddEven(), which returns True (In python, True starts with caps T) if the number is even, else return False (In Python, False starts with caps F).

Note: Python functions, just like variables, don't have a datatype keyword preceding the identifier.

Constraints:
1 <= x <= 106
