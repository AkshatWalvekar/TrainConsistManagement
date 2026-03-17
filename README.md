Overview

This use case implements Binary Search to efficiently locate a bogie ID from a sorted list of bogies in the Train Consist Management System.

Goal

Find a bogie ID quickly using the binary search algorithm instead of checking every element sequentially.

Actor

User

Flow

User provides sorted bogie IDs.

User enters the bogie ID to search.

System compares the key with the middle element.

The search range is reduced repeatedly.

Result is displayed when found or when the range ends.

Key Concepts

Binary Search,
Divide and Conquer,
Sorted Data Requirement,
compareTo() String comparison,
O(log n) search efficiency

Example Output

When bogie is found

Enter Bogie ID to search: BG104

Bogie ID found at position 3

When bogie is not found

Enter Bogie ID to search: BG200

Bogie ID not found
