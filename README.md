# Simple Web

The Simple Web framework is a framework I have built and used for mostly small applications. At this time, I am completely rebuilding the framework. I will update this list as often as I can, based on what I can accomplish in my free time.

If you'd like to contribute to this repository, please don't hesitate to message me.

## Completed

1. Importation Utility and Setup

    > This system uses two different types of loading: Autoloaders and Imports. Autoloaders are core classes that are loaded by the bootstrapper or added to the SPL autoload register. Imports are libraries that are only loaded on demand and may have functionality specific to a script.

2. Unit Testing Classes

    > This system is a very simple, HTML-based renderer that also processes tests. It has been built based on the declarative syntax of Jasmine.

3. Rules Engine

    > This system is a very simple business rules engine or expert system. It only supports single rules (and groups of rules).

4. Template Engine

    > This system is a very simple templating engine. There are no fancy tags or functionality: It is simply a find/replace type of templating engine.

## In Progress



1. REST API endpoint system.
2. Better documentation/comments.
3. Clean up SimpleTest.

## Special Thanks

I'd like to thank Jamie Matthews for [Idiorm](https://github.com/j4mie/idiorm) and [Paris](https://github.com/j4mie/paris) which I use in this framework to handle database abstraction. It serves 90% of use cases that I have come across in the wild. And realistically, anything beyond what this system can handle should probably use a DBA anyways. I have modified this implementation of Idiorm/Paris to be in its own namespace.
