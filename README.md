# Problem Solving Keys 🔑

A comprehensive collection of Data Structures and Algorithms implementations in multiple programming languages (C, C++, Go, and Java).

## 📚 Contents

### Sorting Algorithms

#### Go Implementations
- **[BitonicSort.go](BitonicSort.go)** - Bitonic sort algorithm for parallel sorting
- **[heapsort.go](heapsort.go)** - Heap sort implementation
- **[insertionsort.go](insertionsort.go)** - Insertion sort algorithm
- **[quicksort.go](quicksort.go)** - Quick sort implementation
- **[radixsort.go](radixsort.go)** - Radix sort for integer sorting
- **[timsort.go](timsort.go)** - Tim sort (hybrid sorting algorithm)

#### Java Implementations
- **[BogoSort.java](BogoSort.java)** - Bogo sort (random sort algorithm)
- **[AlgorithmComparison.java](AlgorithmComparison.java)** - Compare performance of different algorithms

#### Go Algorithm Comparison
- **[AlgorithmComparison.go](AlgorithmComparison.go)** - Benchmark and compare sorting algorithms

### Operating System Algorithms

#### CPU Scheduling
- **[1stIn1stOut.cpp](1stIn1stOut.cpp)** - First-Come-First-Served (FCFS) scheduling algorithm
- **[ShortestTimeRemaining.c](ShortestTimeRemaining.c)** - Shortest Remaining Time First (SRTF) scheduling

#### Memory Management
- **[First Fit.cpp](First%20Fit.cpp)** - First Fit memory allocation algorithm
- **[Best Fit.cpp](Best%20Fit.cpp)** - Best Fit memory allocation algorithm
- **[Worst Fit.cpp](Worst%20Fit.cpp)** - Worst Fit memory allocation algorithm
- **[small to big- bouble slot - os.cpp](small%20to%20big-%20bouble%20slot%20-%20os.cpp)** - Bubble sort based memory slot allocation

#### Deadlock Management
- **[banker.c](banker.c)** - Banker's algorithm for deadlock avoidance

## 🚀 Getting Started

### Prerequisites

To run the programs in this repository, you'll need:
- **C/C++ Compiler** (GCC, Clang, or MSVC)
- **Go** (version 1.16 or higher)
- **Java JDK** (version 8 or higher)

### Compilation & Execution

#### For C/C++ files:
```bash
# Compile
gcc filename.c -o output
# or for C++
g++ filename.cpp -o output

# Run
./output
```

#### For Go files:
```bash
# Run directly
go run filename.go

# Or compile and run
go build filename.go
./filename
```

#### For Java files:
```bash
# Compile
javac filename.java

# Run
java ClassName
```

## 📊 Algorithm Complexity Reference

### Sorting Algorithms

| Algorithm | Best Case | Average Case | Worst Case | Space Complexity |
|-----------|-----------|--------------|------------|------------------|
| Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) |
| Heap Sort | O(n log n) | O(n log n) | O(n log n) | O(1) |
| Insertion Sort | O(n) | O(n²) | O(n²) | O(1) |
| Radix Sort | O(nk) | O(nk) | O(nk) | O(n+k) |
| Tim Sort | O(n) | O(n log n) | O(n log n) | O(n) |
| Bitonic Sort | O(log²n) | O(log²n) | O(log²n) | O(n log²n) |
| Bogo Sort | O(n) | O(n·n!) | O(∞) | O(1) |

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new algorithms
- Improve existing implementations
- Add documentation
- Report bugs or suggest improvements

## 📝 License

This project is open source and available for educational purposes.

---

⭐ If you find this repository helpful, please give it a star!