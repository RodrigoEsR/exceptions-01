EXCEPTIONS IN JAVA
1a: Very bad option - validation logic in main program
- Not delegated to the reservation.

2a: Bad option - method return String
- The semantics are affected.
- Returning a String has nothing to do with updating a reservation.
- What if the operation actually needs to return a String?
- There is no compiler assistance.
- -The logic ends up with nested conditionals.

3a: Good option - handling exceptions.
