# Ivy PoC GSoC'23

The diag_embed function and its corresponding test are designed to mimic the functionality of PyTorch's torch.diag_embed function. The diag_embed function takes an input array and returns a new array with the input array's elements as a diagonal. The function accomplishes this by extracting the diagonal elements of the input array using the diagonal function from the Ivy library, expanding the resulting 1D array into a 2D array, and filling the remaining elements with zeros.

The corresponding test checks that the diag_embed function produces the expected output for a variety of input shapes, data types, and other parameters, comparing the output with the numpy.diag function. The test is designed to be run with multiple front-end libraries supported by the Ivy library.
