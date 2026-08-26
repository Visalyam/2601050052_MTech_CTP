Algorithm: Binary Search
Start
Create a sorted array containing numbers from 1 to 1,000,000.
Read the target book number from the user.
Set:
   low = 0
   high = length of array - 1
Repeat while low <= high:
   Calculate the middle position:
   mid = low + (high - low) // 2
   Compare array[mid] with the target.
If array[mid] == target:
   The book is found.
   Return the position mid.
If array[mid] < target:
   Search in the right half.
   Set low = mid + 1.
Otherwise:
   Search in the left half.
   Set high = mid - 1.
If low > high:
   The book is not found.
   Return -1.
Display whether the book was found or not.
Stop
