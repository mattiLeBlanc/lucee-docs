Mask that has to be used for formatting. The function follows Java date time mask. For details, see the Java documentation section [Date and Time Patterns](https://docs.oracle.com/javase/8/docs/api/java/text/SimpleDateFormat.html).

The mask proposed in the Date and Time Patterns doesn't seem to be correct with Lucee 4.5.
I found out that the patterns mentioned here (https://www.it-tallaght.ie/railo-context/doc/functions.cfm?item=timeformat) does work.
For example AM / PM time flag is set with 'tt' and not 'a'.
