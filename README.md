Noel Capule
Perl Script
Command to execute: ./exercise data.txt

- Based on the data.txt, there are 3 data centers (dc=I, dc=S, and dc=A) which monitors the value of each request. It seems to me that an average value is at least greater than zero and the negative values are the unexpected values that needs to be flagged within the code. 

- The output below captured all the negative values along with the associated Data Center and time.

- According to the output below, dc=A did not experience any issue, however, dc=S experienced a number of glitches with dc=I having only total of 3. 


OUTPUT
------

Type            Time            Value           Data Center
------------------------------------------------------------
rtb.requests    1443457080      -1630442.511    dc=I
rtb.requests    1443534480      -238156.0083    dc=I
rtb.requests    1443536640      -1136099.312    dc=I
rtb.requests    1443448800      -3622.098174    dc=S
rtb.requests    1443448860      -3576.097777    dc=S
rtb.requests    1443449520      -98273.33278    dc=S
rtb.requests    1443449580      -142325.554     dc=S
rtb.requests    1443449880      -142363.6679    dc=S
rtb.requests    1443455640      -106828.9067    dc=S
rtb.requests    1443455700      -270192.3317    dc=S
rtb.requests    1443456000      -652992.7283    dc=S
rtb.requests    1443456060      -575417.7992    dc=S
rtb.requests    1443468420      -94833.67253    dc=S
rtb.requests    1443468720      -64383.04452    dc=S
rtb.requests    1443473040      -154653.1849    dc=S
rtb.requests    1443473100      -155527.771     dc=S
rtb.requests    1443474840      -599792.8623    dc=S
rtb.requests    1443475200      -4605179.815    dc=S
rtb.requests    1443475260      -4656151.122    dc=S
rtb.requests    1443475560      -802533.9795    dc=S
rtb.requests    1443536340      -249490.2596    dc=S
rtb.requests    1443536640      -201545.4414    dc=S

