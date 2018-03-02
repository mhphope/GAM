Individual or bulk has the same process:

gam csv CSV_NAME.csv gam user ~UserName sendas ~DefaultEmail ~FullName signature file MHPHOPEsignature.html replace FullName ~FullName replace Title ~Title replace Department ~Department replace Address ~Address replace TelephoneNumber ~TelephoneNumber replace MobileNumber ~MobileNumber replace FacsimileTelephoneNumber ~FacsimileTelephoneNumber default treatasalias True

Replace CSV_NAME.csv with file name

CSV must be in current directory in command prompt (i.e., C:\Users\yourUserName)

HTML file “MHPHOPEsignature.html” must be stored in the same directory:
 <p>{FullName}, {Title},<br />{Department}<br />{Address}<br />o: {TelephoneNumber}{RT}, m: {MobileNumber}{/RT}{RT}, f: {FacsimileTelephoneNumber}{/RT}<br /><a href="www.mentalhealthpartnerships.org" target="_blank"><img alt="Mental Health Partnerships: Together, we build hope" src="https://i.imgur.com/HlyjQK3.jpg" /></a></p>

CSV must include the following columns: UserName, DefaultEmail (*@mhphope email address), FullName, Title, Department, Address, TelephoneNumber, FacsimileTelephoneNumber, MobileNumber (Fax/Mobile optional… will only appear in each signature if there is data in cell, otherwise “m: ,” or “f: ,” will be omitted)
