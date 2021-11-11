# Stair stringer calculator

For feedback or support please contact me at <framingcalc@gmail.com>. If you like the app please leave a review / rating.

## Input values
Enter values in decimal or imperial format, an apostrophe suffix denotes feet. Examples of valid inputs: 
* 5.5 
* 5'
* 5.5'6 3/16
* 5' 6.5

## Input fields
**RO rise -** the total rise of the stairs, can be used to find landing height

**Rise -** rise of one step

**Max rise -** maximum rise of each step

**No. of treads -** total number of treads in the stair

**Run -** the run of one step

**Flooring tk -** thickness of flooring to be installed after stringers

**Tread tk -** thickness of finished treads

![](stringerrise.PNG)

## Output results
**Top riser -** The distance from top of stair hole to top of stringer (forms the last riser of the stairs)

**Risers -** total number of risers in stairs including riser formed by top of stair hole

**Stringer length -** The total length of board you need to cut the stringer from

**Marks -** Each mark corresponds to a point of a step on the stringer with the last mark being the end of the stringer. Mark the lengths along the edge of a board. Place your angle guide (framing square etc.) on these points to mark the steps.

![](stringerlayout.PNG)


## How it is calculated
Stairs are calculated from finished floor to finished floor using the given flooring thicknesses. 
The rise (if not given) is calculated from (RO rise - btm flooring tk + top flooring tk) / Max rise.
The bottom rise is adjusted to account for tread thickness and flooring thickness.

## Notes
If you use the rise to calculate your stairs there will be a remainder due to rounding to account for. This is shown as (REM: ) next to the rise value. For example a REM of -1/2 means you need add 1/2 to the rises over the length of the stringer. **You do not need to do this if using the generated marks.**





