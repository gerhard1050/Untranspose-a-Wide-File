Untranspose-a-Wide-File 

Authors: 
Arthur S. Tabachneck, Ph.D., AnalystFinder, Inc.; 
Matthew Kastin, NORC at the University of Chicago; 
Joe Matise, NORC at the University of Chicago; 
Gerhard Svolba, Ph.D., SAS Institute, Inc.

Email: art@analystfinder.com

Presented at SAS Global Forum 2018 in Denver, Colorado - Paper 2419

PROC TRANSPOSE is an extremely powerful tool for making long files wide, and wide files less wide or long, but getting it to do what you need often involves a lot of time, effort, and a substantial knowledge of SAS® functions and data step processing. This is especially true when you have to untranspose a wide file that contains both character and numeric variables. And, while the procedure usually seamlessly handles variable types, lengths and formats, it doesn’t always do that and only creates a system variable (i.e., _label_) to capture variable labels. The present paper introduces a macro that simplifies the process, significantly reduces the amount of coding and programming skills needed (thus reducing the likelihood of producing the wrong result), runs up to 50 or more times faster than the multiple PROC TRANSPOSE and data steps that would otherwise be needed, and either creates untransposed variables that inherit all of the original variables’ characteristics or creates a file that contains all of the relevant metadata. 
