# Erlang UI Experiment

The purpose of this project is to experiment with building a UI using [Erlang].
I've had some ideas around building a text editor that would require strong
concurrency features. Erlang excels at concurrency and has bindings to
[wxWidgets], so I figured this would be a good place to start testing ideas.

Other goals of this project are to refresh my Erlang knowledge and build a UI on
a platform other than a web browser. I love UI programming and have very little
experience developing on platforms other than the web.

**It is unlikely that this project will ever result in either stable or useful
software.** You have been warned ;)

## Concurrent UI Ideas

The rough idea is to have separate aspects of a text editor be completely
isolated from one another. ie: if syntax highlighting crashes, it has no effect
on any other part of the editor.

The genesis of this idea comes from Google Chrome's [tab isolation] and UX
frustrations with the [Atom] editor. While I applaud the design and engineering
effort behind Atom, I can't help but think that using web technologies as a
platform for a text editor is a bizarre case of [Stockholm syndrome] from web
developers with limited exposure to other languages and platforms. Hopefully
this project will provide some clarity as to whether or not this belief is
justified.

## Development

TODO: write me

## License

[ISC License]


[Erlang]:http://www.erlang.org/
[wxWidgets]:http://www.erlang.org/doc/apps/wx/chapter.html
[tab isolation]:https://www.chromium.org/developers/design-documents/site-isolation
[Atom]:https://atom.io/
[Stockholm syndrome]:https://en.wikipedia.org/wiki/Stockholm_syndrome
[ISC License]:LICENSE.md
