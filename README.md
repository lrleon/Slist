# Slist
================

A Go package implementing a singly-linked list data structure.

## Overview
--------

The Slist package provides a comprehensive implementation of a singly-linked list, including various methods for manipulating the list, such as insertion, deletion, traversal, and more.

## Features
--------

*   **Create and Initialize**: Create a new list with the [New](cci:1://file:///home/lrleon/work/Slist/slist.go:26:0-34:1) function, and initialize it with a variable number of elements.
*   **Insertion**: Insert elements at the beginning or end of the list using the [Insert](cci:1://file:///home/lrleon/work/Slist/slist.go:97:0-105:1) and [Append](cci:1://file:///home/lrleon/work/Slist/slist.go:72:0-80:1) methods.
*   **Deletion**: Remove the first element of the list using the [RemoveFirst](cci:1://file:///home/lrleon/work/Slist/slist.go:107:0-120:1) method.
*   **Traversal**: Traverse the list using the [Traverse](cci:1://file:///home/lrleon/work/Slist/slist.go:237:0-248:1) method, which executes a given operation on each element.
*   **Reversal**: Reverse the list in-place using the [ReverseInPlace](cci:1://file:///home/lrleon/work/Slist/slist.go:258:0-268:1) method or create a reversed copy using the [Reverse](cci:1://file:///home/lrleon/work/Slist/slist.go:270:0-273:1) method.
*   **Rotation**: Rotate the list in-place by a specified number of positions using the [RotateLeftInPlace](cci:1://file:///home/lrleon/work/Slist/slist.go:275:0-287:1) method or create a rotated copy using the [RotateLeft](cci:1://file:///home/lrleon/work/Slist/slist.go:289:0-292:1) method.
*   **Swapping**: Swap two lists in O(1) time using the [Swap](cci:1://file:///home/lrleon/work/Slist/slist.go:16:0-24:1) method.
*   **Iteration**: Iterate over the list using the [Iterator](cci:2://file:///home/lrleon/work/Slist/slist.go:174:0-177:1) type, which provides methods for accessing the current element, moving to the next element, and checking if the iterator is valid.

## Testing
--------

The package includes a comprehensive test suite, which covers all the methods and functions provided by the Slist package.

## License
-------

The Slist package is released under the MIT License.

## Usage
-----

To use the Slist package, simply import it in your Go program and start using the provided functions and methods.

```go
import "github.com/yourusername/slist"