###Penumbra's Code

In the book [Mr Penumbra's 24 Hour Book Store](http://www.robinsloan.com/penumbra/), one of the main plot points is a code involving substitution of a given text with numbers notched into the glyphs of a typeface. It sounded pretty simple, so I started coding a version on the flight home. If you're clever with letter frequencies and assignments, this code could be pretty difficult. 

Note that I have no association with Mr. Sloan, other than being a fan. I'm building this so I can do some cryptanalysis of the cypher; I think that as described in the book it wouldn't take much to break. I feel like 500 years of codebreaking effort would probably crack anything but a one time pad; Almost any cypher that's over 100 years old has already been cracked, sometimes multiple ways (I'm thinking of Vignere, but there are many examples; google 'history of cryptography' if you're curious). 

####todo

add some of the salting functions I was thinking about 

write some tests to confirm that things are working
 
reorganize & refactor methods in module PenumbraEncoding

gemspec & gem creation

release gem

create sinatra app 