![renderBee](https://s3.amazonaws.com/public.philemonworks.com/renderbee/bee.png)

Package for creating HTML renderable components in Go.
Inspired by [renderSnake](http://rendersnake.org) and [seaside](http://www.seaside.st/).

[![Build Status](https://travis-ci.org/emicklei/renderbee.png)](https://travis-ci.org/emicklei/renderbee)

## Basics

- Encapsulate a Go template and its data into a component, called a fragment
- Use a Map or Composite to encapsulate a Go template and multiple fragments
- Render fragments and containers on a HtmlCanvas (io.Writer)

Read the [full documentation](http://godoc.org/github.com/emicklei/renderbee) and try [the examples](https://github.com/emicklei/renderbee/tree/master/examples) or explore it on [Sourcegraph](https://sourcegraph.com/github.com/emicklei/renderbee).

(c) 2013, http://ernestmicklei.com. Apache v2 License
