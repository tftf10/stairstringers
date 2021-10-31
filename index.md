#Stair stringer calculator

##Input values
Enter values in decimal or imperial format, an apostrophe denotes feet. Examples of valid inputs: 5.5, 5', 5.5'6 3/16 etc.

##Input fields
RO rise - the total rise of the stairs, can be used to find landing height
Rise - rise of one step
Max rise - maximum rise of each step
No. of treads - total number of treads in the stair
Run - the run of one step
Flooring tk - thickness of flooring to be installed after stringers
Tread tk - thickness of finished treads

##Output results
Top riser - The distance from top of stair hole to top of stringer (forms the last riser of the stairs)
Risers - total number of risers in stairs including riser formed by top of stair hole
Stringer length - The total length of board you need to cut the stringer from
Marks - Each mark corresponds to a point of a step on the stringer with the last mark being the end of the stringer. Mark the lengths along the edge of a board. P
lace your angle guide on these points to mark the steps.



##How it is calculated
Stairs are calculated from finished floor to finished floor using the given flooring thicknesses. 
The rise (if not given) is calculated from (RO rise - btm flooring tk + top flooring tk) / Max rise.
The bottom rise is adjusted to account for tread thickness and flooring thickness.

##Notes
If you use the rise to calculate your stairs then there will be a remainder due to rounding that you must account for. This is shown as (REM: ) next to the rise value. For example a REM of -1/2 means you need to deduct -1/2 from the rises over the length of the stringer. **You do not need to do this when using the generated marks.**





