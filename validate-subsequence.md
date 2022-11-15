```
 function isValidSubsequence(array, sequence) {
  
  let seqIdx = 0; // Pointer
   
  for (const value of array) {
    if (value === sequence[seqIdx]) seqIdx++;     // Match, and move on
    if (seqIdx === sequence.length) return true;  // Seqence end (possibly early)
  }
  return false;
}
```
