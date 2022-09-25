#Week 3 Feedback

As a general note, Clare, if you aren't getting your code to run successfully, you won't be able to receive full credit.  While I'll give you partial credit on the weekly assignments and you'll do OK overall, that won't be the case on the midterm and final.  If your code doesn't run end to end on those, you will receive few points.

Please reach out via Canvas if you're getting stuck rather than submitting something that doesn't work.


14.3 - You mostly had it, but you can see some issues from the error message that's given by Python.
* The test for equality is `==` rather than `=`.  The single equal sign is the "assignment" operator that gives a variable some value.  The double equal sign is used to test if two things are equal.
* You can see from my "assert" examples that the acute_flag is going to be True or False -- the boolean values -- rather than the string "True" or "False".  You would need to remove the quotation marks from around "True" for this test work correctly.

14.4 - This was good, but you didn't actually "call" the LACE function you created above.  You have `(ed_visits, length_of_stay, acute_flag, charlson)`, but you didn't tell Python to do anything with those variables.  The correct syntax would have been `LACE(...)` with the variables in the right order.

14.5 - In this one, you need to do the work of computing the qcsi value. Your code seems to assume that it is already calculated somewhere.

