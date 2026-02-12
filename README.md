# Java-Concepts

1) Count Factors

<img width="425" height="368" alt="image" src="https://github.com/user-attachments/assets/55408962-8fd3-41e9-8f4b-62d2e95ad0ff" />


2) Good Pair : Given an array A and an integer B. A pair(i, j) in the array is a good pair if i != j and (A[i] + A[j] == B). Check if any good pair exist or not.
    A = [1,2,3,4]
    B = 7
     (i,j) = (3,4)
     O/P : 1

     <img width="395" height="224" alt="image" src="https://github.com/user-attachments/assets/92d27580-0e5e-4568-baaa-742cffb5a3cb" />

3) Array Rotation : Given an integer array A of size N and an integer B, you have to return the same array after rotating it B times towards the right.
I/P : A = [1, 2, 3, 4] , B = 2
O/P : [3, 4, 1, 2]

<img width="657" height="359" alt="image" src="https://github.com/user-attachments/assets/766e03d2-a992-41e4-8a47-b5b2238014ee" />

4) Range Sum Query : PrefixSum[cummelative sum] and Queries[][] [l-r].
   I/P : A = [1, 2, 3, 4, 5], B = [[0, 3], [1, 2]]
   O/P : [10, 5]

    <img width="447" height="402" alt="image" src="https://github.com/user-attachments/assets/2d22a463-cc56-41ae-a469-c96b93dcdf89" />

 5) Special Subsequences "AG"
     I/P : A = "ABCGAG" 
     O/P : 3   [Subsequence "AG" is 3 times in given string, the pairs are (0, 3), (0, 5) and (4, 5)]

     <img width="384" height="286" alt="image" src="https://github.com/user-attachments/assets/8c767f17-d0ad-42d6-933c-9dc0d676880d" />

 6) Opt: Equilibrium index of an array 
 <img width="647" height="456" alt="image" src="https://github.com/user-attachments/assets/67ed9860-34c9-4c35-9a07-5a3c4fb7615d" />
 <img width="644" height="485" alt="image" src="https://github.com/user-attachments/assets/fd213cee-26fc-48b2-8e47-1307f9899541" />
 Ans
 <img width="502" height="340" alt="image" src="https://github.com/user-attachments/assets/d005b228-ae02-40ad-9c9f-b3e08726e0ad" />

 7) Special Index : Given an array, arr[] of size N, the task is to find the count of array indices such that removing an element from these indices makes the sum of even-indexed and odd-indexed array elements equal.
  Steps : Make Even Prefix Sum and Odd Prefix sum : now at perticuler Index  { Even Sum, [ Index ], Odd Sum } after index change or remove assume this change.
  I/P : A = [2, 1, 6, 4] => 1  ,  A = [1, 1, 1] => 3

  <img width="455" height="487" alt="image" src="https://github.com/user-attachments/assets/d05a64f9-8b13-4f07-bead-09cc0cb11435" />

  <img width="617" height="478" alt="image" src="https://github.com/user-attachments/assets/419ad11b-1ce6-4e15-811e-4b0cc3aec8ba" />

8) Leaders in an array : Given an integer array A containing N distinct integers, you have to find all the leaders in array A. An element is a leader if it is strictly greater than all the elements to its right side.

NOTE: The rightmost element is always a leader.

I/P : A = [16, 17, 4, 3, 5, 2] , O/P : [17, 2, 5]

<img width="429" height="453" alt="image" src="https://github.com/user-attachments/assets/6ccbd9c9-692a-499a-a3c9-15887ceb7340" />

9) Opt : Best Time to Buy and Sell Stocks : 
<img width="661" height="410" alt="image" src="https://github.com/user-attachments/assets/8cc8fddd-a38c-4865-9bee-fd25c5f44c91" />
<img width="685" height="669" alt="image" src="https://github.com/user-attachments/assets/98ae654b-9f6a-4a3c-bc7c-36ff8e68a96e" />
<img width="537" height="367" alt="image" src="https://github.com/user-attachments/assets/49994754-b219-47c6-ba76-157f690d7be0" />
<img width="624" height="401" alt="image" src="https://github.com/user-attachments/assets/fb34e583-76e4-44db-a73d-9e65c4d37d4a" />

10) Closest MinMax : Given Array A in which Subarray Contains Min & Max element 
==> Given an array A, find the size of the smallest subarray such that it contains at least one occurrence of the maximum value of the array and at least one occurrence of the minimum value of the array.
<img width="698" height="672" alt="image" src="https://github.com/user-attachments/assets/80acdb8e-6adc-45ce-a68e-728b21cfd5ee" />
<img width="897" height="386" alt="image" src="https://github.com/user-attachments/assets/456fc51f-0d62-49ce-9841-61217a4c45f5" />

But the solution approach is Explained Diff

<img width="529" height="707" alt="image" src="https://github.com/user-attachments/assets/3243765b-33c0-486c-b804-4fe9fc9e3310" />
<img width="553" height="707" alt="image" src="https://github.com/user-attachments/assets/40c5cea1-438f-4f93-b053-f0c1a7d6912d" />
|||||||||||||||||||||||||CODE IS HERE||||||||||||||||||||||||||||||||||||||||||||

<img width="496" height="660" alt="image" src="https://github.com/user-attachments/assets/7a0c553b-c2b3-4e89-8d4c-d62e65a76422" />
<img width="522" height="695" alt="image" src="https://github.com/user-attachments/assets/5258eaa4-9959-4790-9d84-9d04a3e80866" />

11) Sliding Window : Subarray with given sum and length
Given an array A of length N. Also given are integers B and C.
Return 1 if there exists a subarray with length B having sum C and 0 otherwise
<img width="691" height="678" alt="image" src="https://github.com/user-attachments/assets/cf04c539-1152-4fbf-8718-d038c3173ee0" />
<img width="470" height="380" alt="image" src="https://github.com/user-attachments/assets/1b519218-b0c4-4833-a25c-493d39d818bd" />

12) Noble Integer : Given an integer array A, find if an integer p exists in the array such that the number of integers greater than p in the array equals p.
    <img width="696" height="607" alt="image" src="https://github.com/user-attachments/assets/0f92981d-c664-409a-a4f5-093cfddb00c5" />
    <img width="440" height="293" alt="image" src="https://github.com/user-attachments/assets/3674212b-9684-4f36-95a0-cc67e3958746" />

13)  Elements Removal : Minimum cost to Remove An Element
    Given an integer array A of size N. You can remove any element from the array in one operation.
    The cost of this operation is the sum of all elements in the array present before this operation.
    Find the minimum cost to remove all elements from the array.  
    <img width="693" height="678" alt="image" src="https://github.com/user-attachments/assets/c62c1c25-f6f7-43a7-82a5-8309a75b8e08" />
    <img width="341" height="217" alt="image" src="https://github.com/user-attachments/assets/34c59fe2-91f9-49c1-824a-a9237497ea35" />

14) Row to Column Zero : You are given a 2D integer matrix A, make all the elements in a row or column zero if the A[i][j] = 0. Specifically, make entire ith row and jth column zero.
    <img width="709" height="690" alt="image" src="https://github.com/user-attachments/assets/1ca6dcdc-27f2-46a5-8ccc-3d5078331d4f" />

    <img width="404" height="440" alt="image" src="https://github.com/user-attachments/assets/05f0d3ca-bd14-4443-bc6d-527c2f3330d3" />
    
15) String Toggle Case : 'H' changes to 'h', 'o' changes to 'O'
    <img width="664" height="448" alt="image" src="https://github.com/user-attachments/assets/ca1b16a9-7f67-40f9-8c8d-6484b187354d" />

    <img width="453" height="224" alt="image" src="https://github.com/user-attachments/assets/5a96c7a3-34d0-492e-a23f-1e9e7cc62d9c" />

 16) Longest Palindromic Substring : Given a string A of size N, find and return the longest palindromic substring in A.

Substring of string A is A[i...j] where 0 <= i <= j < len(A)

Palindrome string:
A string which reads the same backwards. More formally, A is palindrome if reverse(A) = A.

Incase of conflict, return the substring which occurs first ( with the least starting index).

<img width="689" height="653" alt="image" src="https://github.com/user-attachments/assets/80ad00e2-256e-4048-a46e-4080bb4d0dc6" />
<img width="898" height="851" alt="image" src="https://github.com/user-attachments/assets/cf45391d-a9f2-4515-89bd-3266a741f558" />

17)  Rotate Matrix
18)  replace 0 -> 1 : Length of longest consecutive ones =>  A = "111011101" , O/P : 7 && A = "111000" , O/P : 3
19)  Swep Length of longest consecutive ones =>  A = "111011101" , O/P : 7 && A = "111000" , O/P : 3





     




 














  






   


