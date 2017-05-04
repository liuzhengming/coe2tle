# coe2tle

```java
@Description    :kepler orbit elements to TLE Algorithm
@Method_Name    : simpleCoe2Tle
@param startYear:startYear,(for example,17 for 2017)
@param startTime:start from Jan 1th 00:00:000 every year,(for example,124.16666667 for May 4th 04:00:000)
@param six		:kepler orbit elements sorted as below:
	 Mean					:mean motion(revs per day)
	 Eccentricity			:
	 Inclination			:(deg）
	 Argument of perigee    :(deg)
	 RAAN					:(deg）
	 Mean					:mean motion(deg)
@param name		:satellite number，(5 numbers at most,01 for example)
@return 		:tle tle[0] for first line,tle[1] for second line
@return         :String[]

```
