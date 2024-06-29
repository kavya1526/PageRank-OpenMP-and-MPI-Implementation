# PageRank-OpenMP-and-MPI-Implementation

This project implements serial and parallel versions of the PageRank algorithm using OpenMP ans MPI.

## Overview

The PageRank algorithm is used to rank web pages based on their importance and connectivity. This implementation includes:

- Serial version
- Parallel version using OpenMP
- Comparison to a state-of-the-art implementation

## Features

- Implements PageRank formula with teleportation factor
- Uses adjacency matrix representation of web graph
- Parallelized using OpenMP directives
- Tested on Gnutella peer-to-peer network datasets
- Includes profiling and performance analysis

## Requirements

- C compiler with OpenMP support
- OpenMP library
- Gnutella network datasets (p2p-Gnutella24 and p2p-Gnutella25)

## Usage

Compile the code: gcc -fopenmp pagerank.c -o pagerank
Run: ./pagerank <dataset_file> <num_threads>

## Performance Analysis

The project includes:

- Runtime comparison of serial vs parallel versions
- Speedup and efficiency metrics
- Load balancing analysis 
- Cache performance profiling
- Comparison to state-of-the-art implementation

## Results

Key findings:

- Parallel implementation achieves speedup up to 4x with 4 threads
- Memory-bound problem, with high cache miss rates
- State-of-the-art implementation outperforms due to optimized data structures

## Contributors

- Kavya Parikh
- Nidhi Manek
- Vishv Joshi  
- Krupal Patel
- Ashray Kothari
- Vidhi Badrakiya

## References

See full paper for detailed references on PageRank algorithm and related work.
