# JavaXMLSanitizer
I saw that some samples of xml santinizer code on the internet are doing wrong things by comparing a char to 0x10FFF (0x10FFF is always larger than any possible char value)
So just built this sanitizer for fun

Sanitizing rules: http://www.w3.org/TR/REC-xml/#charsets
