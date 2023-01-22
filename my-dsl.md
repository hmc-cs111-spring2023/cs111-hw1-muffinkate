# Language

Purl

https://arxiv.org/pdf/1606.08708.pdf

# Domain

Modular knitting patterns

# Computational model

When Purl runs, it verifies that it is a valid knitting pattern and then creates a knitting
pattern using standard knitting notation, as well as adding information to help the knitter
reduce their own mistakes.

# DSL-ness

I think this language lies somewhere in the middle, since the use case is very domain specific
and uses a lot of vocabulary that is specific to knitting. However, the "grammar" uses a lot of
concepts that are really important in general-purpose languages like loops and functions. 

# Internal or external?

This is an external DSL because it has it's own syntax that gets parsed into an AST, and then into
the HTML knitting pattern.

# Host language

I think the compiler was written in javascript, and then it uses CSS and HTML to generate the pattern and create a rudimentary IDE for the language.

# Benefits

It makes it easier to identify and reuse the modular elements of a knitting pattern, as well as checking the pattern to make sure that it's valid, and using knitting notation inside the language helps leverage computational thinking when creating a pattern.

# Drawbacks

It isn't as elegant as a general-purpose language because it has to adhere to a strict notation. The user can't define variables or use a notation that makes sense to them because it has to be able to be compiled.
