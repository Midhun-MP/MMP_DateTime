MMP_DateTime
============

This JavaScript module can be used for getting date in desired formats


This module can be used for formatting the JavaScript Date object to desired formats.
There are several patterns defined for doing this, for avoiding conflicts with normal words each pattern contains 3 to 5 characters.

Available Pattern Strings
------

1. `YYYY`
    Gives full year.  
    Eg : 1990
2. `YYY`
    Gives 2 digit year.  
    Eg : 90
3. `MMMMM`
    Gives full month name.  
    Eg : August
4. `MMMM`
    Gives abbreviation of month name.  
    Eg : Aug
5. `MMM`
    Gives month index.  
    Eg : 8 (for August)
6. `DDDDD`
    Gives full day name.  
    Eg : Monday
7. `DDDD`
    Gives abbreviation of day name.  
    Eg : Mon
8. `DDD`
    Gives the date index.  
    Eg : 20
9. `HHHH`
    Gives the hour in 24 hour format.  
    Eg : 16
10. `HHH`
    Gives the hour in 12 hour format.  
    Eg : 4
11. `mmm`
    Gives the minute.  
    Eg : 30
12. `sss`
    Gives the second.  
    Eg : 30
13. `lll`
    Gives the millisecond.  
    Eg : 619

Usage
------

```Javascript
var dateObj = new MMPDate("YYYY MMM DDD");
dateObj.FormattedDate();					// Gives the formatted date
```

Credits
------

Author : Midhun M P

Email  : midhunmp7@gmail.com

Copyright (c) 2014 Midhun-MP

If you have any suggestions for this module, please feel free to send me an email. :)