<!DOCTYPE html>
<html>
<body>
  <h1>Cache-Simulator</h1>
  
  <h2>Description</h2>
  <p>
    This program is a simulator for the behavior of the cache memory system. It is part A of the cache lab - the 4th lab of <a href="https://www.cs.cmu.edu/afs/cs/academic/class/15213-f15/www/schedule.html"> 2015 Fall: 15-213 Introduction to Computer Systems.</a>
  </p>
  
  <h2>Features</h2>
  <ul>
    <li>Takes a <a href="https://man7.org/linux/man-pages/man1/valgrind.1.html">Valgrind</a> memory trace as input</li>
    <li>Simulates cache memory behavior of an arbitrary size</li>
    <li>Outputs total number of hits, misses, and evictions</li>
    <li>Implements the LRU (Least Recently Used) policy for cache eviction</li>
  </ul>
  
  <h2>Lab Files</h2>
  <ul>
    <li><code>cachelab.pdf</code>: Lab writeup</li>
    <li><code>csim.c</code>: Contains the main function</li>
    <li><code>cache.c</code>: Contains the cache simulator implementation</li>
    <li><code>traces/</code>: Directory containing Valgrind memory trace files</li>
    <li><code>test-sim</code>: Tests the correctness of the simulator</li>
  </ul>
  
  <p>
    Note: This repository is specific to the <a href="https://www.cs.cmu.edu/afs/cs/academic/class/15213-f15/www/schedule.html">CMU 15-213</a> course and the cache lab.
  </p>
</body>
</html>
