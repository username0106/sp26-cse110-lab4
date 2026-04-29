1. values added: 20 
2. finals result: 20
3. you should not use var as var ignores the boundaries of if, for, or while blocks which would cause the var to be able to be accessed in the entire function when it's not supposed to be accessable. 
4. values added: 20
5. There would be an error as result is a let which does not leak outside the if block which would cause an error as it would not be able to find result
6. There would be an error before line 9 and line 7 as line 7 tries to reassign result which is a const so it cannot be reassigned
7. There would alreay be an error on line 7 but even then line 13 would have an error as result is not assigned a value so it wouldn't be able to find result