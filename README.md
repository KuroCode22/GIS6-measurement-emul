# GIS6-measurement-emul
Report that emulate total station mesuments in Geodetic Iinformation System 6.

What is it?
  This is report for GIS6 (Ukrainian land surveying program that have specific purpose http://www.gis.org.ua/gis6.htm)
  It emulate mesurement with total station of 5" accuracy, from nearby points of geodetic system.
  Main code is writen on PascalScript.
  
How does it work?
  Incoming data:   at least two coordinates of "hard" points (by defualt there are points from Berdiansk region of Zaporizka oblast)
  
  Proceeding data: 1 two base points of total station mesurement, drown by line 159 in "definition" layer of GIS6 program
                   2 lines of mesurements drown by 9 line in "definition" layer, all mounts become points of land plot,
  
  Result: 5 sheets of paper to satisfy corrupted Ukrainian bureaucracy machine.
