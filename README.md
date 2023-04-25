# Selection-sort<br>
Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted portion. This process is repeated for the remaining unsorted portion of the list until the entire list is sorted. One variation of selection sort is called “Bidirectional selection sort” which goes through the list of elements by alternating between the smallest and largest element, this way the algorithm can be faster in some cases.<br>
![image](https://user-images.githubusercontent.com/124968304/234186256-e98a80b7-cb83-40fc-9849-da9ab4f721d4.png)
<br>
# Selection Sort Algorithm<br>

The algorithm maintains two subarrays in a given array.<br>

1.The subarray which already sorted. <br>
2.The remaining subarray was unsorted.<br>
<br>
In every iteration of the selection sort, the minimum element (considering ascending order) from the unsorted subarray is picked and moved to the beginning of the sorted subarray.<br>

After every iteration sorted subarray size increase by one and the unsorted subarray size decrease by one.<br>

After the N (size of the array) iteration, we will get a sorted array.<br>
<br>
<b><ins>Follow the below steps to solve the problem:<b><ins><br>

1.Initialize minimum value(min_idx) to location 0.<br>
2.Traverse the array to find the minimum element in the array.<br>
3.While traversing if any element smaller than min_idx is found then swap both values.<br>
4.Then, increment min_idx to point to the next element.<br>
5.Repeat until the array is sorted.<br>
<br>
<b><ins>Output<b><ins><br>
<img width="922" alt="Selection sort" src="https://user-images.githubusercontent.com/124968304/234187660-2bf8d8d0-0ced-4fca-804c-ccb8bbbf17d8.png">



