# Scott_Jackson_1756_Appendix_xml

For this activity, I used an online XML validator instead of the suggested "xmllint" utility. 

https://www.freeformatter.com/xml-validator-xsd.html

Between the error messages provided using this utility, as well as visual inspection of the provided client feed ("appendix.xml"), I detected three types of errors contained in the client XML feed. It's possible that other errors could be detected using "xmllint", but I was unable to determined that due to time constraints and unfamiliarity with the installation/setup process for "xmllint". 

Here are the basic error types I discovered and corrected:

1. Broken closing tags (i.e. line breaks introduced within a closing tag)
2. "&" needs to be coded as "&amp;amp;" in client's text values
3. "UniqueIdType" text values cannot have whitespaces

In the commit history for "appendix.xml", I've included more detail about my process in investigating/correcting these issues and communicating them to the client: 

https://github.com/shjackson/Scott_Jackson_1756_Appendix_xml/commits/master/appendix.xml

Note: As you can see, the version of the “appendix.xml” file that I’ve tested and uploaded here is missing the tab indentation that was included in the “appendix” in the test PDF. That indentation disappeared when I tried copy/pasting that source code out of the PDF file. I researched the issue of indentation in XML files and the dominant opinion is that it does not affect parsing, but it is mainly a best practice for human readability. Based on that assumption, I did not recreate the tab indentation for this verification process.

Note: These are the links I discovered for installing “xmllint”. As noted above, it seemed like it was going to be too time intensive to install/learn/use this tool for the deadline required by this test.

http://xmlsoft.org/downloads.html
https://www.zlatkovic.com/projects/libxml/index.html
https://stackoverflow.com/questions/19546854/installing-xmllint

Please let me know if you have any questions / comments.

All the best,

Scott
