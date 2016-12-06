# sass-reset
SASS based CSS reset file 

The goal of a reset stylesheet is to reduce browser inconsistencies in things like default line heights, 
margins and font sizes of headings, and so on.

In case you didn’t know, every browser has its own default ‘user agent’ stylesheet, that it uses to make 
unstyled websites appear more legible. For example, most browsers by default make links blue and visited 
links purple, give tables a certain amount of border and padding, apply variable font-sizes to H1, H2, H3 etc. 
and a certain amount of padding to almost everything. Ever wondered why Submit buttons look different in every browser?

Obviously this creates a certain amount of headaches for CSS authors, who can’t work out how to 
make their websites look the same in every browser.

Using a CSS Reset, CSS authors can force every browser to have all its styles reset to null, 
thus avoiding cross-browser differences as much as possible.

This is a basic SASS based reset file which can be imported into the main SASS file using the @import keyword.
Note that you dont have to include the .sass extension or the '_' character at the beginning of the file for 
importing the '_reset.sass' file.

More information about sass imports can be found here - http://sass-lang.com/guide
