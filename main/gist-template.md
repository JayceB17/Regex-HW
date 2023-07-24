Title (Regex)
HI!! my name is Jayce and I wanted to talk a little bit about Regex. Today we will be going over, What regex, why do I need to know this, and how can I create one? 

Summary
Regex also known as "regular expressions" it is a pattern of sequences uses to find something in a database. Another way that I have heard it is "It is engin logic".  This is an example of a
regex /^(https?://)?([\da-z.-]+).([a-z.]{2,6})([/\w .-])/?$/.

Anchors
-The anchors is what starts and ends.  They match the characters postions.  This ^ is at the beggining and $ is at the end.
/^(https?://)?([\da-z.-]+).([a-z.]{2,6})([/\w .-])/?$/.

Quantifiers
-Quantifiers specify how many times a characters or group is need to to find a match. For example in this regex /^(https?://)?([\da-z.-]+).([a-z.]{2,6})([/\w .-])/?$/
these are the quantifiers [\da-z.-]+).([a-z.]. 

Flags
Flags are a way to change how the search is preformed.  For example I Makes the expression search case-insensitively.

Character Classes
Characters Classes or Characters Sets you can use it to find or match to a specific characters.  Just put the characters in square brackets[].

Character Escapes
Character Escapes are used to match a character that has a special meaning in the regex.  In our example the period . matches a period.  
/^(https?://)?([\da-z.-]+).([a-z.]{2,6})([/\w .-])/?$/

Grouping Constructs
Grouping is done by defining groups of characters by using parentheses.  Because of this we can extract information for more processing.
 like (https?://), or ([a-z.]{2,6}).

The OR Operator
The OR operator is used to match the expression, it can do this eather before of after the operator.  An example from our regex is 
(https?://)? it means it will eather match with http:// or https://.

Bracket Expressions
Bracket expression is matching list expression or nonmatching list expression.  It usuall matches a single character of a group of characters.  
For example  [\da-z.-] Its a single character thats a letter, a period, a dash, or a digit.

Author
Jayce Hampton

