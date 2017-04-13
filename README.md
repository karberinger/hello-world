# hello-world
A place to put some "warm up" code.

// This is pseudocode
procedure fibonacci( n:non-negative_integer ) := 
{
  // "out of bounds" check
  if n < 0 OR n > MAX: return 0. 
  
  // BASE CASE to return recursive function calls
  if n = 0 OR n = 1: return 1. 
  
  // RECURSIVE CASE to call the function from within
  else: return fibonacci( n - 1 ) + fibonacci( n - 2 )
}
