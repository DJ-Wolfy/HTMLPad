Welcome to HTMLPad by DJ-Wolfy (Rory A. Michie)
OpenSource fast accessible html editor and website builder

Welcome to HTMLPad pad, your one-stop shop for building web pages at a lightning fast speed
Version: 0.1.0 beta
Note: This product will probably never come out of beta. I will try to fix as many trivial errors as I can, but, ultimately, this product is mainly for my own use and I will not stop you from breaking it if you do something that the program doesn't understand. Always back up your code files (use git!!!) and I am not responsible for any lost data.
Pull requests are,, of course, welcome, if you have any improvements that you think could be helpful. Thanks for making HTMLPad better!

Do you like how fast notepad is but wish you had something which was easier to use to rapidly build prototype websites? HTMLPad is here to fill that desire
HTMLPad was built from the ground up using PureBasic. This is because PureBasic is the programming language I know with the fastest UI handler there is (faster than wx python and maybe faster than horizon but making an entire UI framework is out of the scope of this project and something I might do later).
Anyway, it's very simple. It works just like notepad, and has the following keyboard shortcuts:
control+n; make a new file and save it
control+o; select a file and open that
control+s; save the file
other than that all basic editing commands should work but let me know if something breaks
Now here's where the HTMLPad differs from notepad:
alt+1 through 6: turn that line into a heading
alt+l: turn a tabulated line into a link (first tab is url and second tab is how the link should appear to the user)
alt+t: turn a tabulated group of lines that ends in a blank line into a table
alt+u: turn a group of lines that ends in a blank line into an unordered list
alt+n: numbered list
alt+a: alphabetical  list
alt+p: paragraph break
alt+h: horizontal rule
f5: save the page and open a preview in the browser

How to compile?
To compile this you'll need PureBasic. Other than that I put windows binaries in the bin folder. That's the only palce I think it works anyway, it isn't cross platform
license
This product is licensed under the GPL v3. Tldr is that If you want to make your own version, you're more than welcome to do so, but if you use this code, in full or in part, you must release your product as open source. The full license is in the license file
