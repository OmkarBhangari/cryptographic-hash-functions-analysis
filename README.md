# Cryptographic Hash Functions Analysis

## Overview

This repository provides a comprehensive analysis of various cryptographic hash functions. It evaluates their performance and security properties based on a set of test datasets. The key properties assessed include:

- **Compression Ratio**: The ratio of input data size to hash output size.
- **Speed/Throughput**: The number of hashes computed per second.
- **Avalanche Effect**: The percentage of changed bits in the hash output when a single bit of the input is altered.
- **Sensitivity**: The number of differing bits between hashes for the original and modified inputs.
- **Entropy**: The measure of randomness and unpredictability in the hash output.
- **Memory Usage**: The amount of memory required for storing hash values.
- **Hash Value Length**: The fixed length of the hash output.
- **Security Level**: A qualitative assessment of the hash function’s security based on its hash value length.
- **Parallelizability**: The hash function's ability to be parallelized for performance improvements.
- **Resistance to Length Extension**: Whether the hash function is resistant to length extension attacks.
- **Energy Consumption**: Estimated energy consumption for hashing (requires specific hardware measurement).
- **Side-channel Resistance**: The hash function's resistance to side-channel attacks (requires specific testing conditions).
- **Efficiency**: Time required to hash a single byte of data.

## Hash Functions Tested

The following hash functions were analyzed:

- **MD5**: Produces a 128-bit hash value.
- **SHA-1**: Generates a 160-bit hash value.
- **SHA-256**: Part of the SHA-2 family, generates a 256-bit hash value.
- **SHA-512**: Produces a 512-bit hash value.
- **SHA3-256**: Part of the SHA-3 family, generates a 256-bit hash value.
- **Blake2b**: A cryptographic hash function faster than MD5, SHA-1, and SHA-2.

## Dataset

The following datasets were used for testing:

- "Hello, world!"
- "The quick brown fox jumps over the lazy dog"
- "OpenAI creates and trains AI models."
- "Data integrity is crucial in information security."
- "Cryptographic hash functions are widely used."

## Files

- `hash_functions_properties_part1.csv`: Contains detailed properties and performance metrics for the hash functions.
- `hash_functions_properties_part2.csv`: Continues the analysis from the first file if necessary.

## How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/cryptographic-hash-functions-analysis.git
