# Codeforces Problem Solutions
![C++](https://img.shields.io/badge/language-C%2B%2B-blue)

This repository contains my solutions to various Codeforces problems. These problems span a range of topics and difficulty levels, from beginner to intermediate. The solutions focus on problem-solving strategies, efficient algorithms, and clear explanations.

## 📂 Problem List
This section includes the problems and their corresponding solutions:

#### 1. Boy or Girl (800)
  - **Problem**: Determine if a username has an even or odd number of distinct characters.
  - **Approach**: Use a set to track unique characters in the string. If the size of the set is even, print "CHAT WITH HER!", otherwise print "IGNORE HIM!".
2. Domino Piling (800)
  - **Problem**: Given an m x n rectangular board, find how many 2x1 dominoes can fit on it.
  - **Approach**: Use integer division to calculate the number of dominoes that can fit by dividing the total area (m * n) by 2.
3. Elephant (800)
  - **Problem**: Find the minimum number of steps an elephant needs to take to cover a distance x, with step sizes of 1, 2, 3, 4, or 5.
  - **Approach**: Use integer division and modulo to compute the minimum number of steps required.
4. I_love_%username% (800)
  - **Problem**: Count the number of times a user's performance is a new personal best or worst during a competition.
  - **Approach**: Track the current maximum and minimum scores, updating them as needed.
5. Is your horseshoe on the other hoof? (800)
  - **Problem**: Given 4 horseshoes, determine how many need to be replaced to make all 4 distinct.
  - **Approach**h: Use a set to count the number of unique horseshoes, and subtract that from 4 to get the number of replacements required.
6. Next Round (800)
  - **Problem**: Determine how many participants advance to the next round based on scores.
  - **Approach**: Count how many participants have scores greater than or equal to the score of the k-th place finisher and ensure they have non-negative scores.
7. System of Equations (800)
  - **Problem**: Find the number of integer pairs (a, b) that satisfy the equations a^2 + b = n and b^2 + a = m.
  - **Approach**: Iterate through possible values of a and solve for b using the given equations.
8. Team (800)
  - **Problem**: Count the number of problems that can be solved when at least two out of three teammates agree.
  - **Approach**: For each problem, check if at least two teammates have the same answer (1 for yes, 0 for no).
9. Theatre Square (800)
  - **Problem**: Given a rectangular theatre of size n x m, determine how many square tiles of size a x a are needed to cover the area.
  - **Approach**: Calculate the number of tiles for each dimension by taking the ceiling of the division of n and m by a.
10. Good Matrix Elements (1200)
  - **Problem**: In an n x n matrix, find the sum of the "good" elements (elements located on both the main diagonal and anti-diagonal).
  - **Approach**: Iterate through the matrix and add the elements that meet the criteria for being "good."

## 📌 Topics Covered
  - **Math**: Divisibility, Number Theory, Geometry, Greedy Algorithms.
  - **Strings**: Manipulation, Pattern Matching, Counting Distinct Elements.
  - **Data Structures**: Arrays, Sets.
  - **Implementation**: Simulations, Counting, Iteration over Sequences.



