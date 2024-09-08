# Merge Sort Algorithm in JavaScript

This repository contains an implementation of the Merge Sort algorithm in JavaScript. Merge Sort is a highly efficient sorting algorithm that follows the divide and conquer paradigm. It works by recursively dividing the array into halves, sorting them, and then merging the sorted halves back together.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Features

- Efficient O(n log n) time complexity
- Stable sorting algorithm
- Easy to understand and implement

## Getting Started

To get a local copy up and running, follow these simple steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/merge-sort.git
   ```
2. Navigate to the project directory:
   ```bash
   cd merge-sort
   ```

## Usage

You can use the Merge Sort function by including the `mergeSort` function in your JavaScript code. Here's a simple example of how to use it:

const array = [38, 27, 43, 3, 9, 82, 10];
const sortedArray = mergeSort(array);
console.log(sortedArray);

## Example

Here’s a brief example of how the algorithm works:

1. Split the array into halves until each sub-array contains a single element.
2. Merge the sub-arrays back together in sorted order.

For example, given the array `[38, 27, 43, 3, 9, 82, 10]`, the sorted output will be `[3, 9, 10, 27, 38, 43, 82]`.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add new features, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
