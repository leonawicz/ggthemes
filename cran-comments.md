## R CMD check notes

-   "found ... marked UTF-8 strings": The UTF strings are necessary to the package.
    They encode specific non-ASCII characters to use as symbols.

-   URLs from jstor.org and twitpic.com are valid but sometimes return status 
    391 or 503 due to redirection.

-   In `DESCRIPTION`, the words "Geoms", "Stata", "Tufte", "Tufte's", 
    and "geoms" are not mis-spelled.
