# HuaweiB535
Huawei B535 Scripts and Stuffs
# Scripts
setB7+B1
This script act as the js hack script: it first set the main band ( B7 ) and then set the main band + second band ( B7 + B1 ).
This fix the problem that you set B7+B1 and nothing else, you'll probably get B1 as main band, which is wrong.

<LTEBand>0000000041</LTEBand>

this is the exadecimal sum of codes below

Codes for each Band as follows

- 0000000001 B1 2100
- 0000000004 B3 1800
- 0000000040 B7 fdd 2600
- 0000000080 B8 900
- 0008000000 B28 700
- 8000000000 B40 fdd 2300

so 41 is B7 (40) + B1 (01)
