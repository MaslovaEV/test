# Test File 
## In Markdown

You can use Markdown and reStructuredText in the same Sphinx project. We support this natively on Read the Docs, and you can do it locally:

``$ pip install recommonmark``

Then in your ``conf.py:``

``from recommonmark.parser import CommonMarkParser``

``source_parsers = {``
    ``'.md': CommonMarkParser,``
``}``

``source_suffix = ['.rst', '.md']``
# Note 
![Note mark](https://github.com/MaslovaEV/test/blob/master/icon48.png?raw=true)

Markdown doesn't support a lot of the features of Sphinx, 
           like inline markup and directives. However, it works for 
           basic prose content. reStructuredText is the preferred 
           format for technical documentation, please read `this blog post`_ 
           for motivation.
           
