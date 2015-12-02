# csharp_BTC_Markets_Harness

A Harness written in C# to demonstrate the use of all the BTC Markets API functions.

This solution has the third party Nuget package RestSharp as well as NewtonSoft JSON included. You will need to add these to use the existing functions but if you rewrite the Query function to use any other Request method then you will be able to connect successfully with the helper functions for signing strings and generating the timestamps.

I have housed this sample in a Console application for demonstration purposes, feel free to refit to your purpose.

To get the solution up and running, go to the ApplicationConstants.cs file and change the values stored for API KEY and PRIVATE KEY that can be access from within the BTC Markets page.

The Main code block has each of the API functions accessible commented out, uncomment to test out each function (be careful with Create Order!)

For the CancelOrder and OrderDetail API functions I have only created functions to cater for a single OrderID. I will endeavour to extend this to cater for a list of OrderID's.
