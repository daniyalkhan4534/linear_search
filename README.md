# linear_search

A linear search is the simplest method of searching a data set. Starting at the beginning of the data set, each item of data is examined until a match is made. Once the item is found, the search ends. If there is no match, the algorithm must deal with this.

How Linear Search Works?
*Step 1: First, read the search element (Target element) in the array.
*Step 2: Set an integer i = 0 and repeat steps 3 to 4 till i reaches the end of the array.
*Step 3: Match the key with arr[i].
*Step 4: If the key matches, return the index. Otherwise, increment i by 1.

Illustration of Linear Search:
Consider the array arr[] = {10, 50, 30, 70, 80, 20, 90, 40} and key = 20

Step 1: Set i = 0 and check key with arr[0].
![image](https://user-images.githubusercontent.com/127819492/234484804-3cbc3bb2-ec89-47da-8e3c-14528009571d.png)

Step 2: key and arr[0] are not the same. So make i = 1 and match key with arr[1].
![image](https://user-images.githubusercontent.com/127819492/234484865-efc89cf4-3438-4dfb-8433-f43e03ca0925.png)

Step 3: arr[1] and key are different. Increment i and compare key with arr[2].
![image](https://user-images.githubusercontent.com/127819492/234484945-c46befcb-4fa9-415b-8777-f27bb6c824c7.png)

Step 4: arr[2] is not the same with key. Increment i and compare key with arr[3]
![image](https://user-images.githubusercontent.com/127819492/234485004-cc474831-408c-425a-8dd4-ec8c7b7d0b67.png)

Step 5: key and arr[3] are different. Make i = 4 and compare key with arr[4].
![image](https://user-images.githubusercontent.com/127819492/234485068-c831dc09-28db-48b3-a4e6-ca34ebaf566e.png)

Step 6: key and arr[4] are not same. Make i = 5 and match key with arr[5]
![image](https://user-images.githubusercontent.com/127819492/234485119-baa0b478-851f-4a2b-ab64-297aba16bb68.png)

Time Complexity:


Best Case:
In the best case, the key might be present at the first index. So the best case complexity is O(1)

Worst Case:
In the worst case, the key might be present at the last index i.e., opposite to the end from which the search has started in the list. So the worst case complexity is O(N) where N is the size of the list.

Average Case:
O(N)

Auxiliary Space: O(1) as except the variable to iterate through the list, no other variable is used.
