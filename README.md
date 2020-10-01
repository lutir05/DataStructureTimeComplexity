# DataStructureTimeComplexity
Data Structure Time Complexity
### Data Structure Operations Cheat Sheet
**Note:** For best case operations, the time complexities are O(1).
<table >
<tr>
<th rowspan="2">Data Structure Name</th>
<th colspan="4">Average Case Time Complexity</th>
<th colspan="4">Worst Case Time Complexity</th>
<th>Space Complexity</th>
</tr>
<tr>
<td><strong>Accessing n<sup>th</sup> element</strong></td>
<td><strong>Search</strong></td>
<td><strong>Insertion</strong></td>
<td><strong>Deletion</strong></td>
<td><strong>Accessing n<sup>th</sup> element</strong></td>
<td><strong>Search</strong></td>
<td><strong>Insertion</strong></td>
<td><strong>Deletion</strong></td>
<td><strong>Worst Case</strong></td>
</tr>
<tr>
<td><strong>Arrays</strong></td>
<td>O(1)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
</tr>
<tr>
<td><strong>Singly Linked List</strong></td>
<td>&theta;(n)</td>
<td>&theta;(n)</td>
<td>&theta;(1)</td>
<td>&theta;(1)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(1)</td>
<td>O(n)</td>
</tr>
<tr>
<td><strong>Stacks</strong></td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(1)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(1)</td>
<td>O(n)</td>
</tr>
 <tr>
<td><strong>Queues</strong></td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(1)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(1)</td>
<td>O(1)</td>
<td>O(n)</td>
</tr>
 <tr>
<td><strong>Binary Trees</strong></td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
</tr>
  <tr>
<td><strong>Binary Search Trees</strong></td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
<td>O(n)</td>
</tr>
   <tr>
<td><strong>Balanced Binary Search Trees</strong></td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
<td>O(logn)</td>
</tr>
</table><br>

## Sorting Algorithm Cheat Sheet

<table>
 
<tr>
<th rowspan="2">Storting Algorithm Name</th>
<th colspan="3">Time Complexity</th>
<th>Space Complexity</th>
<th rowspan="2">Is Stable?</th>
<th rowspan="2">Storting Class Type</th>
<th rowspan="2">Remarks</th>
</tr>
<tr>
<th>Best Case</th>
<th>Average Case</th>
<th>Worst Case</th>
<th>Worst Case</th>
</tr>
<tr>
<td><strong>Bubble Sort</strong></td>
<td>O(n)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(1)</td>
<td>Yes</td>
<td>Comparison</td>
<td>Not a preferred sorting algorithm</td>
</tr>
<tr>
<td><strong>Insertion Sort</strong></td>
<td>O(n)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(1)</td>
<td>Yes</td>
<td>Comparison</td>
<td>In the best case (already sorted), every insert requires constant time.</td>
</tr>
<tr>
<td><strong>Selection Sort</strong></td>
<td>O(n<sup>2</sup>)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(1)</td>
<td>No</td>
<td>Comparison</td>
<td>Even a perfectly sorted array requires scanning the entire array.</td>
</tr>
<tr>
<td><strong>Merge Sort</strong></td>
<td>O(nlogn)</td>
<td>O(nlogn)</td>
<td>O(nlogn)</td>
<td>O(n)</td>
<td>Yes</td>
<td>Comparison</td>
<td>On array, it requires O(n) space and on linked lists, it requires constant space.</td>
</tr>
<tr>
<td><strong>Heap Sort</strong></td>
<td>O(nlogn)</td>
<td>O(nlogn)</td>
<td>O(nlogn)</td>
<td>O(1)</td>
<td>No</td>
<td>Comparison</td>
<td>By using input array as storage for the heap, it is possible to achieve constant space.</td>
</tr>
<tr>
<td><strong>Quick Sort</strong></td>
<td>O(nlogn)</td>
<td>O(nlogn)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(logn)</td>
<td>No</td>
<td>Comparison</td>
<td>Randomly picking a pivot value can help avoid worst case scenarios such as a perfectly sorted array.</td>
</tr>
<tr>
<td><strong>Tree Sort</strong></td>
<td>O(nlogn)</td>
<td>O(nlogn)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(n)</td>
<td>Yes</td>
<td>Comparison</td>
<td>Performing inorder traversal on the balanced binary search tree.</td>
</tr> 
<tr>
<td><strong>Counting Sort</strong></td>
<td>O(n + k)</td>
<td>O(n + k)</td>
<td>O(n + k)</td>
<td>O(k)</td>
<td>Yes</td>
<td>Linear</td>
<td>Where k is the range of the non-negative key value.</td>
</tr>
<tr>
<td><strong>Bucket Sort</strong></td>
<td>O(n + k)</td>
<td>O(n + k)</td>
<td>O(n<sup>2</sup>)</td>
<td>O(n)</td>
<td>Yes</td>
<td>Linear</td>
<td>Bucket sort is stable, if the underlying sorting algorithm is stable.</td>
</tr>
<tr>
<td><strong>Radix Sort</strong></td>
<td>O(dn)</td>
<td>O(dn)</td>
<td>O(dn)</td>
<td>O(d + n)</td>
<td>Yes</td>
<td>Linear</td>
<td>Radix sort is stable, if the underlying sorting algorithm is stable.</td>
</tr>
</table>
