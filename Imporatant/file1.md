## Type Juggling

What do you think is going to be the result of the following line of code? if("7 hashes" == 7) If you said True, congrats you were right. But shouldn’t it be false? Not only are they dissimilar but also of different data types. Now let’s see how. Before the comparison of values of different types, PHP converts them to a singular comparable type. In the above case, PHP will try to extract the integer ,7 from the string (7 hashes) and then compare it against the integer 7, hence giving out a True Value.
