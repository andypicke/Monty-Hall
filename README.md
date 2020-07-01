

The explanation of the solution I've seen that makes the most sense to me goes something like this:
* Say you choose door 1. We can say there is a 1/3 probability (P=1/3) the prize is behind door 1, and P=2/3 that the prize is behind *either* door 2 or 3.
* The host must now open either door 2 or 3 (let's say the prize is actually behind door 3 for this example, so he opens door 2). 
* There is still a 2/3 probability the prize is behind *either* door 2 or 3; however we now know it can't be door 2, so there is P=2/3 it is behind door 3. Based on this, you should switch doors.
* The success of the strategy of switching doors depends on whether you guess the door correctly initially. You have a P=1/3 of guessing correctly (in which case switching doors loses), and a P=2/3 of guessing incorrectly (in which case switching doors wins). So we expect that if you switch doors you will win 2/3 of the time, while if you don't switch you will win 1/3 of the time.
