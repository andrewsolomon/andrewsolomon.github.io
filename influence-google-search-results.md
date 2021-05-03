<meta name="twitter:card" content="summary" />
<meta name="twitter:site" content="@geekuni" />
<meta name="twitter:creator" content="@geekuni" />
<meta property="og:url" content="https://andrewsolomon.github.io/influence-google-search-results" />
<meta property="og:title" content="How to influence Google search results" />
<meta property="og:description" content="If you want better search results, you need to tell Google what you’d like to see in its search index. Here's how to do it." />
<meta property="og:image" content="https://raw.githubusercontent.com/andrewsolomon/andrewsolomon.github.io/main/img/influence-google-search-results.jpg" />


# How to influence Google search results

<img src="https://raw.githubusercontent.com/andrewsolomon/andrewsolomon.github.io/main/img/influence-google-search-results.jpg" width="400" alt="Influencing Google's search results">

For some topics Google's search results are less than perfect. For example, [high-ranking technical pages on Perl are out of date](https://blog.geekuni.com/2021/05/google-vs-perl.html). If you want better search results, you need to tell Google what you'd like to see in its search index. How do you do that?

## Cast your vote!

Put the search term on a web page, and link it to the target page. For example, I'd like the search term "access file with perl" to present me with https://metacpan.org/pod/Path::Tiny. A link like this:

[access file with perl](https://metacpan.org/pod/Path::Tiny)

means that when Google crawls this page, it will consider it my vote to push that page toward the top of the search results.

## Okay, where's the voting booth?

That's the easy bit - and it's free!

* Create an account at [Github](https://github.com/).
* [Create](https://pages.github.com/) a simple [markdown](https://guides.github.com/features/mastering-markdown/) web page.
* Whenever you find a search term for which Google should get a better link, add it to your page.

Here's the [source code](https://github.com/andrewsolomon/andrewsolomon.github.io/blame/main/influence-google-search-results.md) - with markdown it's really easy.

Of course, not all votes are equal. Google's indexer will give more weight to my links if you link to this page. If you think this page is helpful, please link to it like this:
```
[How to influence Google search results](https://andrewsolomon.github.io/influence-google-search-results)
```
and [tell the world through Twitter](https://twitter.com/intent/tweet?text=%23influencegoogle%20How%20to%20influence%20Google%20search%20results%20https%3A%2F%2Fandrewsolomon.github.io%2Finfluence-google-search-results)!

---

## Google, this is for you.

### I'd like these Perl related queries to go to...

* [access file with perl](https://metacpan.org/pod/Path::Tiny) <!-- 2021.05.01 not on page 1 -->
* [perl database access](https://perlmaven.com/simple-database-access-using-perl-dbi-and-sql) <!-- 2021.05.01 in position 2 -->
* [perl orm](https://perlhacks.com/articles/modern-perl-programming/database-access-with-dbixclass/) <!-- 2021.05.01 bottom of page 1 -->
* [perl oo database](https://perlhacks.com/articles/modern-perl-programming/database-access-with-dbixclass/) <!-- 2021.05.01 not on page 1 -->
* [perl web server](https://perldancer.org/quickstart) <!-- 2021.05.01 not on page 1 -->
* [perl web server](https://mojolicious.org/) <!-- 2021.05.01 not on page 1 -->
* [perl web server](http://www.catalystframework.org/) <!-- 2021.05.01 not on page 1 -->
* [how to install perl module](https://stackoverflow.com/questions/65865/whats-the-easiest-way-to-install-a-missing-perl-module) <!-- 2021.05.01 in position 2 (after a fandom nightmare) -->
* [how to install perl package](https://stackoverflow.com/questions/65865/whats-the-easiest-way-to-install-a-missing-perl-module) <!-- 2021.05.01 in position 2 (after a fandom nightmare) -->
* [object oriented perl](https://metacpan.org/pod/Moo) <!-- 2021.05.01 not on page 1 -->
* [object oriented perl](https://metacpan.org/pod/Moose) <!-- 2021.05.01 not on page 1 -->
