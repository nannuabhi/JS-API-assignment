# JS-API-assignment
Create APIs to fetch and show data

3 APIs:
getRoot
getParentFolder
getChildFolder

Show a home page when call to getRoot is successful like this
[+] Home

Clicking on + sign should toggle +/- sign, make a call to the api getParentFolder and on success show it like this
[-] Home
  [+] Child 1
  [+] Child 2
      Child 3

Clicking on Child 1 or Child 2 should toggle +/- sign, make a call to the api getChildFolder and on success show it like this
[-] Home
  [-] Child 1
      Child 1-2
      Child 1-3
  [+] Child 2
      Child 3
