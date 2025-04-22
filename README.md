# DSA-Journal
A daily log of my journey through Data Structures and Algorithms.

<p align="center">
  <img src="https://media0.giphy.com/media/TIj8cbzWYKnE9ul3ab/giphy.gif?cid=6c09b952m2v01jnc6p5njarynl6ix8mmwqikiyhpntpqxrnn&ep=v1_internal_gif_by_id&rid=giphy.gif&ct=s" 
       width="100%" height=10px" />
</p>

### 1.🐰 Rabbits in Forest - Leetcode 781 (Took 50 Mins to solve)

#### Problem Statement:
In a forest, there are a number of rabbits, each of which can ask how many other rabbits are the same color as themselves. Each rabbit's answer can be one of the following:
- If a rabbit says "X", it means there are exactly "X" other rabbits with the same color as this rabbit(including it).

Here we need to calculate the **Minimum number Of Rabbits** in the forest that satisfy all the given answers.

---

UseFul TestCases
> i.[0,0,1,1,1] <br>
> ii.[10,10,10,10,10,10,10,10,10,10,10,10] <br>
> iii.[0,1,0,2,0,1,0,2,1,1]

![Screenshot from 2025-04-20 07-28-42](https://github.com/user-attachments/assets/971c8713-9a81-432b-977c-5ac775a53c0a)

<hr>

### 2. Count the Hidden Sequences - Leetcode 2145 (Took 42 Mins to solve)

### Problem Statement:

Given Differences and length of tha array and lower bound and upper bound.
- Said to Calculate the number of hidden arrays which can be formed using the bounds. ***Hidden Array*** in the sense ***differences[i] = hidden[i + 1] - hidden[i].***
  
#### APPROACH :
- My first approach is to go through the each element and calculate the differnces using prefix sum and getting count (TLE)
- My Second approach is to get first valid sequence and get max from it,, and the count number using the forumla is **((upper-max)+1)** (Passed 81/86)
- Last Approach is I attached it got passed all test cases.

![Screenshot from 2025-04-21 07-28-35](https://github.com/user-attachments/assets/57b40e55-6f7a-4ea9-b01d-e246c118548f)

<hr>

### 3. Learned Fermat's Little Theorem

### Statement of Fermat's Little Theorem:

If `p` is a **prime number** and `a` is an integer such that `a` is **not divisible by p** (i.e., `a % p ≠ 0`), then the following equation holds:

***a^(p - 2) mod p***

<hr>
