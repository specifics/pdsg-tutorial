# Learning Python with Portland Data Science Group
The goal of this quickstart guide is to get you up and running with Python as quickly as possible so you can participate in the Portland Data Science Group. This will be done in four steps:

1. Set up a Python development environment
1. Choose a beginner resource to learn Python syntax
1. Get started with `pandas` (Python Data Analysis Library)
1. 

## <a name="python-references"></a>Python References

This section assumes that you have zero programming knowledge. Your goal here is to go from your first `Hello world!` program to what Chris Moffitt calls the ["plateau of productivity"](http://pbpython.com/plateau-of-productivity.html).

Many people who start coding for the first time get stuck in the "trough of disillusionment" stage of learning, and struggle to break out of it. I pushed a boulder up this same hill many times, only to fall back into the trough and give up for a while. But after a bit of a learning curve, I can attest that it has certainly been worth all the effort, not only in time Python has saved me, but also in a sense of accomplishment.

### <a name="why-python"></a>Why Python?
* It's easy to learn and a great first coding language. You can start start building your own projects within a few weeks!
* It's a mature language with many libraries and helpful documentation.
* It's used for many applications such as scientific computing, web development, data analysis, and machine learning.

### <a name="beginner-novice"></a>Beginner-Novice
Whether you're learning to code for the first time or an experienced programmer looking to add Python to your repertoir of languages, these resources will get you up and running quickly. The very first thing you'll want to do is download the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, and start up an IDE of your choice for one of the resources below. I recommend _JupyterLab_ or _Spyder_

#### <a name="learning-python-for-the-first-time"></a>Learning Python for the First Time
There are five main resources recommended by the Python community, all of them free. You only need to choose one and stick with it, but as we are all blessed with different minds, you'll want to try several to see which is more suited to your learning style. As my electrical engineering professor once told me, *"Find a voice that speaks to you."*

1. [Automate the Boring Stuff with Python](http://inventwithpython.com/#automate) by Al Sweigart
1. [Dive into Python 3](http://www.diveintopython3.net/) by Mark Pilgrim
1. [Think Python](http://greenteapress.com/wp/think-python-2e/) by Allen B. Downey
1. [Python 101](http://python101.pythonlibrary.org/index.html) ([ebook version here](https://leanpub.com/python_101)) by Michael Driscoll
1. [The Official Python Tutorial](https://docs.python.org/3/tutorial/index.html) by the Python Software Foundation

All of them cover the basics of Python, but don't completely overlap with each other in the topics they cover. The main difference is that 1 & 2 get you off the ground faster, giving you the knowledge to start writing practical programs very quickly, while 3-5 take longer to get through, but are more comprehensive and focus on helping you build a solid foundation in Python. It's completely fine to go with one of the faster resources and fill in the gaps later when you can accommodate it.

I like "Automate the Boring Stuff with Python" the best, which took me about 50 hours (and numerous tries) to get through. At some point early on, you'll start to get the itch to write real programs. That's perfectly normal, and I encourage you to start applying what you've learned using a project-based approach — finding problems and solving them with Python is the best way to remember what you've learned so far, and ultimately get better at programming, rather than spending all your time reading and watching videos.

The only resource I recommend avoiding is "Learn Python the Hard Way" by Zed Shaw, mainly because it's outdated.

#### <a name="code-like-a-pythonista"></a>[Code Like a Pythonista: Idiomatic Python](http://python.net/~goodger/projects/pycon/2007/idiomatic/handout.html)
As you learn Python, you'll start to understand why styling and whitespace are important. David Goodger's "Code Like a Pythonista" and similarly [PEP8](https://www.python.org/dev/peps/pep-0008/) are important companions to have so that you get into the habit writing readable code. While you can afford to skip over some bits of Python as a language to learn at a later time, you can never afford to write crappy code because it is the opposite of saving time.

As [SICP](https://mitpress.mit.edu/sicp/full-text/book/book-Z-H-7.html) wisely stated:

> \[...] a computer language is not just a way of getting a computer to perform operations but rather \[...] it is a novel formal medium for expressing ideas about methodology. Thus, programs must be written for people to read, and only incidentally for machines to execute.

Or as [The Zen of Python](https://www.python.org/dev/peps/pep-0020/) simply says: __Readability counts.__

#### <a name="pbpython"></a>[Practical Business Python](http://pbpython.com/)
PB Python is a monthly-ish blog by Chris Moffitt ([@chris1610](https://github.com/chris1610/pbpython)) where he talks about how to apply Python in an everyday business setting. This is the best resource I've found for contextualizing how Python can be used as a powerful tool for enhancing or eliminating tasks that are normally done using Excel or Word. It's also a great place to get started with `pandas` (Python Data Analysis Library) for the first time, which should be of interest for Test/Instrumentation Engineers and Flight Test Analysts.

Head into the [PB Python Archive](http://pbpython.com/archives.html) and start with the article from 5 October 2014, ["Using Sets for Data Analysis"](http://pbpython.com/data-analysis-with-sets.html). As you move forward, go through the articles in chronological order. Chris does a fantastic job of building upon each one until you have a formidable set of tools to tackle a variety of problems!

**Note:** For planning purposes, each PBpy exercise can take 1-2 hours to get through, depending on the topic and your skill level.

#### <a name="regex101"></a>[Regular Expressions 101](https://regex101.com/) by Firas Dib
Regular expressions are a powerful tool, but can be hard to dive into while learning Python. This regex tester and repository is a great resource that can get the regex you need into your Python applications, while also explaining how the specific regex works.

#### <a name="learning-python"></a>"Learning Python, 5th Ed." by Mark Lutz
This text is perhaps the most comprehensive resource for beginner Python users, and covers some topics that aren't in any of the [Learning Python for the First Time](#learning-python) resources, such as interfacing Python with C/C++. This is of particular interest for engineers that work with embedded systems that require C/C++, or anyone that desires the computational power of C/C++ while keeping the ease of development in Python.

Since this book is an absolute behemoth of over 1,600 pages, I recommend it mainly as a companion reference for looking up concepts & examples that aren't explained thoroughly by any of the free resources. For even more exercises, Mark Lutz made his [live course materials](http://learning-python.com/training) available for free.

#### <a name="python-in-a-nutshell"></a>"Python in a Nutshell" by Martelli-Ravenscroft-Holden

---

### <a name="intermediate-advanced"></a>Intermediate-Advanced
By the time you've completed some programming projects on your own, you'll probably need some resources to reach the next skill level as a Python developer. The books in this section will help correct some of the bad habits you've undoubtedly picked up while learning Python, and fill in any knowledge gaps while also delving into more advanced programming methods. "Fluent Python" is a solid and frequently recommended text that you can't go wrong with, but each of these books has something different to offer depending on what your learning goals are.

#### <a name="fullstackpython"></a>[Full Stack Python](https://www.fullstackpython.com/introduction.html)
Full Stack Python is a landing point for intermediate Python learners looking for a specific focus or application. This open book includes a wealth of resources for getting into web development, data analysis, security, and application deployment, which can be helpful for coming up with projects and learning goals beyond mastering the language.

#### <a name="fluent-python"></a>"Fluent Python: Clear, Concise, and Effective Programming" by Luciano Ramalho

#### <a name="effective-python"></a>"Effective Python: 59 Specific Ways to Write Better Python" by Brett Slatkin

[From the author of "Effective Python" on the differences from "Python Cookbook"](https://www.reddit.com/r/Python/comments/31zjy5/book_effective_python_vs_python_cookbook_which/cq6nl66/):

> Author of Effective Python here. I think they're very different books! David Beazley is awesome and a wonderful educator. He's always the best speaker at PyCon. I'd say: the _Cookbook_ is a powerful and thorough reference, the _Effective_ books are short and scenario driven.

#### <a name="python-cookbook"></a>"Python Cookbook" by David Beazley and Brian K. Jones

#### <a name="high-performance-python"></a>"High Performance Python: Practical Performant Programming for Humans" by Micha Gorelick and Ian Ozsvald

#### <a name="hackers-guide-to-python"></a>"The Hacker's Guide to Python" by Julien Danjou

---
