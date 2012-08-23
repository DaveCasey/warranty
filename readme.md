#warranty.rb

warranty.rb accepts arguments of machine serial numbers and contacts Apple's selfserve servers to return warranty information. If no serial is provided, it will use the serial from the current mac.

All of the good ideas herein came from [glarizza][1], except for the rest of the good ideas which came from [pudquick][2].

##Sample serials to use for troubleshooting:

Product Description: MacBook Pro (15-inch, Mid 2009)  
Serial Number: W80090N064C  
Expires: 2013-03-01  
ASD Version: 3S132  

Product Description: MacBook (13-inch Late 2006)  
Serial Number: 4H64872FWGL  
Expirespires: Expired  
ASD Version: 3S116  

Product Description:	MacBook Pro (15-inch, Early 2011)  
Serial Number: C02F83SDDF8X  
Expires: 2014-02-24  
ASD Version: 3S144  

Product Description: MacBook Pro (15-inch, Mid 2010)  
Serial Number: W80493AFAGZ  
Expires: 2013-12-05  
ASD Version: 3S138  

Product Description:	MacBook Pro (15-inch Early 2008)  
Serial Number: W881116PYK0  
Expires: Expired  
ASD Version: 3S123  

[1]: https://github.com/glarizza/scripts/blob/master/ruby/warranty.rb "glarizza"
[2]: https://github.com/pudquick/pyMacWarranty/blob/master/getwarranty.py "pudquick"
