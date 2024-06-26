# CompareMalware
This repository provides the code to compare PE and ELF files and generate a similarity matrix for files of the same format.

These scripts are designed to analyze malware samples from different malware families. These samples are collected from honeypots, which are controlled environments used to attract and study malicious activity. The analysis depends on the type of binary, so there's a specific script for each format.

For PE-type binaries, the second version of the script creates a CSV file containing a matrix with the similarity percentages between the samples. This allows you to compare and visualize the relationship between samples from different malware families based on their internal characteristics and their level of similarity.
