# Leetcode-GeekForGeeks-Coding-Problems---Python-Programming

QUESTION :
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

Solution : 

def friends_in_trouble(j_angry, s_angry):
    if (j_angry == True and s_angry == True):
        return True
    if (j_angry is False and s_angry is False):
        return True
    return False
