# README

This file simply lists [Stack Overflow](http://stackoverflow.com) questions, and some answers,
that are useful when closing new questions as duplicates. Below you should find a list of the
typical questions that already answer many of the questions that are asked again and again.

---

* [What is a NullReferenceException, and how do I fix it?](https://stackoverflow.com/questions/4660142/what-is-a-nullreferenceexception-and-how-do-i-fix-it/4660186#4660186)

    Any question regarding `NullReferenceException` that ends up asking "why do I get this?".
    
    The reason why this is a good duplicate is that in almost every single case the real answer
    is to debug more, and to uncover the reason why there was an expectation that something
    wasn't `null` when clearly something has assigned `null` to it. Every such question is different,
    so even if the OP says "My question is different", there should be a really good reason given
    for why that is before the question is reopened.
    
* [How do I convert a string into safe SQL String?](https://stackoverflow.com/questions/5528972/how-do-i-convert-a-string-into-safe-sql-string)

    Any question regarding how to properly "encode" or "escape" characters so that one can "safely"
    construct a SQL statement containing data from outside.
    
    Real answer is don't do it, do proper parameterization instead.
    
    **Todo**: See if I can find a better one, I think I've seen one but can't find it now.
    
* [RegEx match open tags except XHTML self-contained tags](https://stackoverflow.com/questions/1732348/regex-match-open-tags-except-xhtml-self-contained-tags/1732454#1732454)

    Any question about how to parse HTML or XML or a breed of the two using regular expressions.
    
    Real answer is don't do it, there's good libraries available for all good programming
    platforms that does a proper and better job of this problem than a regular expression every will.