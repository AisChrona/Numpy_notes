
# Array Types & Dimensions

print(arr.ndim)       # Dimension
print(arr.shape)      # Shape of array
print(arr.dtype)      # Data type


 # Array Indexing and Slicing

arr2 = np.array([[1, 2, 3], [4, 5, 6]])
print(arr2[0, 1])      # Output: 2
print(arr2[:, 1])      # Column slicing

 # Array Reshaping

a = np.array([1, 2, 3, 4, 5, 6])
print(a.reshape(2, 3))


# Broadcasting

a = np.array([1, 2, 3])
b = np.array([4])
print(a + b)           # Output: [5, 6, 7]

# Useful NumPy Functions

np.zeros((2, 3))       # Create array of zeros
np.ones((2, 3))        # Array of ones
np.eye(3)              # Identity matrix
np.random.rand(2, 2)   # Random values


 # Mathematical Operations

arr = np.array([1, 2, 3])
print(np.mean(arr))    # Mean
print(np.sum(arr))     # Sum
print(np.std(arr))     # Standard deviation
