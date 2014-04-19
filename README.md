# BFS (Go)

<img src="http://upload.wikimedia.org/wikipedia/commons/3/33/Breadth-first-tree.svg" alt="Breadth First Search" align="right" height="140"/>

### [Breadth First Search][bfs] implementation in Go

This is part of a series of exercises to help me improve my understanding of programming languages and styles.<br/>
Implementation as described by [Prof. Erik Demaine][demaine] in a [recorded lecture][bfs-video] at MIT.<br/>
The graph constructed in the test is represented in the diagram shown on the right.

```bash
$ go build -o bfs
$ ./bfs
[1 2 3 4 5 6 7 8 9 10 11 12]
```
If you have [Vagrant][vagrant] installed, you can build a simple dev environment. The repository will be mounted in `/srv`.
```bash
$ curl -O https://raw.github.com/adlawson/vagrantfiles/master/go/Vagrantfile
$ vagrant up
$ vagrant ssh
```

<table>
    <thead>
        <tr>
            <th>Elixir</th>
            <th>Erlang</th>
            <th>Go</th>
            <th>JavaScript</th>
            <th>Julia</th>
            <th>Lua</th>
            <th>Python</th>
        </tr>
    <thead>
    <tbody>
        <tr>
            <td align="center"><a href="https://github.com/adlawson/dfs.ex">dfs.ex</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.erl">dfs.erl</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.go">dfs.go</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.js">dfs.js</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.jl">dfs.jl</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.lua">dfs.lua</a></td>
            <td align="center"><a href="https://github.com/adlawson/dfs.py">dfs.py</a></td>
        </tr>
        <tr>
            <td align="center"><a href="https://github.com/adlawson/bfs.ex">bfs.ex</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.erl">bfs.erl</a></td>
            <td align="center">bfs.go</td>
            <td align="center"><a href="https://github.com/adlawson/bfs.js">bfs.js</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.jl">bfs.jl</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.lua">bfs.lua</a></td>
            <td align="center"><a href="https://github.com/adlawson/bfs.py">bfs.py</a></td>
        </tr>
    </tbody>
</table>

```
The MIT License (MIT)

Copyright (c) 2014 Andrew Lawson <http://adlawson.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

[bfs]: http://en.wikipedia.org/wiki/Breadth-first_search
[demaine]: http://en.wikipedia.org/wiki/Erik_Demaine
[bfs-video]: http://www.youtube.com/watch?v=s-CYnVz-uh4
[vagrant]: http://vagrantup.com
