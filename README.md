# 335-Project-1
The Alternating Disk Problem

# Description: 

Given a row of 2n disks of two colors with n light and n dark. The disks alternate: light, dark, light and so on. 

# Goal: 

You must move all the dark disks to the left hand end and all the light disks to the right hand end. 

# Algorithms:

Lawnmower algorithm: Starts with the leftmost disk, compares every two adjacent disks and swaps if necessary. Once it reaches the right hand end, starts with the rightmost disks and compares and swaps if necessary. The algorithm repeats ⌈n/2⌉ times.

Alternate algorithm:
It runs a total of n runs. The algorithm starts with the leftmost disk and proceeds to the right until it reaches the rightmost disk, compares every two adjacent disks and swaps if necessary. This is Run 1. On Run 2, we starts with the second leftmost disk and proceeds to the second rightmost disk, swapping if necessary. Repeat Run 1 and Run 2 continually until sorting is finished. 

Group member: Chanmolita Nuon molitanuon36@csu.fullerton.edu
