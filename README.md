Purpose
-------

This Objective-C code contains several methods to help you calculate dates, such as the first and last date of a month, quarter, or year. The methods are provided in a Category of `NSDate`, so they're very simple to use.

For example, here's how you would get an NSDate for the first day of this quarter:


    NSDate *myDate = [NSDate firstDayOfCurrentQuarter];
    
Originally created for use in an iOS app, which needed to filter dates when generating reports. Hence the name (NSDate+Reporting).


Usage
-----

Simply `#import "NSDate+Reporting.h"` in the file where you wish to use any of these methods, and then use them as if they were part of **NSDate** itself.

The individual methods are documented in `NSDate+Reporting.h`.

License (MIT)
-------
Copyright © 2012 Mel Sampat

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
	
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
	
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
