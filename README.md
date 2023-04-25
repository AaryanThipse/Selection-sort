# Selection-sort<br>
Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list. The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted portion. This process is repeated for the remaining unsorted portion of the list until the entire list is sorted. One variation of selection sort is called “Bidirectional selection sort” which goes through the list of elements by alternating between the smallest and largest element, this way the algorithm can be faster in some cases.<br>
![image](https://user-images.githubusercontent.com/124968304/234186256-e98a80b7-cb83-40fc-9849-da9ab4f721d4.png)
<br>
# Selection Sort Algorithm<br>

The algorithm maintains two subarrays in a given array.<br>

1.The subarray which already sorted. <br>
2.The remaining subarray was unsorted.<br>
In every iteration of the selection sort, the minimum element (considering ascending order) from the unsorted subarray is picked and moved to the beginning of the sorted subarray.<br>

After every iteration sorted subarray size increase by one and the unsorted subarray size decrease by one.<br>

After the N (size of the array) iteration, we will get a sorted array.<br>
