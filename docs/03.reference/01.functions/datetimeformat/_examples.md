**Adding regular text within the mask**
You can add regular text between mask characters by wrapping them in single quotes, assuming your write the mask within double quotes.
And example that outputs date and time separated by the text 'at':

    DateFormat( Now(), "d mmmm yyyy 'at' hh:nn tt" )
Would print

    24 November 2015 at 01:05 PM
