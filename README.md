Download Link: https://assignmentchef.com/product/solved-605-202-data-structures-lab-1-elevator
<br>
ABC Corporation has an old office building with out of date elevators, which need to be modernized or replaced. You have been hired to evaluate the current use of the elevators so they can make an appropriate decision. You decide a computer simulation would be the best strategy to evaluate the use of the elevator, so you go to the office building to collect some actual data on the use of the elevator.  You record actual usage (see input file) and observe the following facts:

<ul>

 <li>There are two elevators which each hold five people. One elevator is very small, so the limit is closely followed. The second elevator seems to be permanently broken.</li>

 <li>The elevator is very narrow so people have to get off to let out anyone that is behind them.</li>

 <li>The building has 5 floors serviced by the elevator.</li>

 <li>People always get on the elevator if there is room, even if it is going in the wrong direction, i.e. they may get on to go down even if they really want to go up.</li>

</ul>

You decide to use stacks.  In the simulation, at each floor, you do the following:

<ul>

 <li>Remove people scheduled to get off on that floor</li>

 <li>Print the name of people exiting; along with the number of times each person had to exit temporarily during their trip.</li>

 <li>Restore people who got off temporarily.</li>

 <li>Load people waiting to get on.</li>

 <li>If the elevator is full or empty, print that out. Identify people who are waiting to get on but are unable to do so, if the elevator is full. Assume that people unable to get on the elevator will take the stairs.</li>

 <li>Print the name of each person getting on along with their destination floor.</li>

 <li>Proceed to the next floor, which is the next floor selected by a current passenger or the next floor selected by a person waiting to get on, whichever is sooner.</li>

</ul>

After your simulation is finished, print out the total number of people who rode, the number of time someone could not ride because it was full, the number of empty occasions, etc.




The input you collected is in a separate file. Since you did not know the name of the people working at ABC Corporation, you amused yourself by making up names for them.  The data is the name followed by the entrance floor, followed by the exit floor.  You end up going back a second time to collect addition data (student generated)




Summarize your findings and recommendations in a report to ABC Corporation. Explain your strategy and the program you wrote in detail. Explain what you learned about elevator use at ABC and make recommendations.  Be sure to consider the second elevator.  As an addendum, you write report for in-house use, in which you justify your simulation design choices and why a stack is an appropriate choice. Defend your implementation decisions. Discuss what you leaned, and what you would change going forward with the simulation. Besure to consider efficiency consideration (both time and space)