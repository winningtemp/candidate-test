# Backend test

This is a repository for Winningtemp candidate tests. It is intended to provide insight into the range of your skill set. It is not a pass/fail test. Please do what you can.

**Guidelines for submitting your test:**

- Read the instructions
- Do the tasks
- E-mail your result to career@winningtemp.se with subject: "Candidate test"
  - The e-mail should contain your test or a link to your test (could be a link to a repo)
  - The e-mail should contain all the instructions that is needed to run and examine your test

If you have any questions, feel free to drop a line to: career@winningtemp.se.

Good luck!

### Background

Your city has decided to implement toll fees for vechicles in order to reduce traffic congestion during rush hours. This is the current draft of requirements:

 - Fees will differ between 8 SEK and 18 SEK, depending on the time of
   day (SEK = swedish currency)
 - Rush-hour traffic will render the highest fee. The fee that you have
   to pay is based on these hours:
 - 06:00–06:29, 9 SEK
 - 06:30–06:59, 16 SEK
 - 07:00–07:59, 22 SEK
 - 08:00–08:29, 16 SEK
 - 08:30–14:59, 9 SEK
 - 15:00–15:29, 16 SEK
 - 15:30–16:59, 22 SEK
 - 17:00–17:59, 16 SEK
 - 18:00–18:29, 9 SEK
 - 18:30–05:59, 0 SEK
 - The maximum fee for one day is 60 SEK
 - A vehicle should only be charged once an hour
 - Some vehicle types are toll-free (meaning they don't have have any fee)
 - Weekends and holidays are toll-free (meaning they don't have have any
   fee)

### Task

The current code is legacy code that never made it to production. There are plenty of room for improvements. Your task is to make this code production ready and make sure that it meets all the requirements above. 

This test is intended to provide insight into the range of your skill set. It is not a pass/fail test. Please do what you can. Feel free to refactor any code you want and rewrite all parts that you think needs to be rewritten.

**Requirements:**

- Create a Visual Studio solution (sln) that contains your code 
- The code should be easy to maintain and extend with new features in the future
- The code must have unit tests that prove that the above requirements are met

