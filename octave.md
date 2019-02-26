#+STARTUP: showall
#+TITLE: Octave
#+AUTHOR: http://h4labs.com
#+HTML_HEAD: <link rel="stylesheet" type="text/css" href="/resources/css/myorg.css" />

Menu: [[file:bash.org][bash]] | [[file:compilers.org][Compilers]] | [[file:elixir.org][Elixir]] | [[file:fsharp.org][F#]] |[[file:go.org][Go]] | [[file:haskell.org][Haskell]] | [[file:ocaml.org][OCaml]] |  [[file:octave.org][Octave]] | [[file:perl.org][Perl]] | [[file:python.org][Python]] | [[file:r.org][R]] | [[file:scala.org][Scala]] | 

* Inbox
+ https://www.chemie.fu-berlin.de/chemnet/use/info/octave/octave_toc.html
+ http://orgmode.org/worg/org-contrib/babel/languages/ob-doc-octave-matlab.html

* Misc Commands
#+BEGIN_SRC octave
% Comments begin with percent sign: %
PS1('>> ') % Change prompt
pwd % Current directory
cd '/tmp' % Change working directory; Will load .m functions from here
help help
help plot
#+END_SRC

* Language Introduction

** If statement
#+BEGIN_SRC octave

#+END_SRC

** For loop
#+BEGIN_SRC octave

#+END_SRC

** Simple Function
#+BEGIN_SRC octave
% No parameters
% Invoke: hello() or hello
%
function hello()
  printf("Hello\n");

end

% Two parameters
% Invoke: mymax(1,2)
%
function mysum(x,y)
  a = x + y
  printf("Sum:%d\n", a);
end

% Two parameters
% Invoke: mysum(1,2)
%
function a = mysum(x,y)
  a = x + y

end
#+END_SRC

** Load and Save Data
#+BEGIN_SRC octave

#+END_SRC

** Plot statement
#+BEGIN_SRC octave

#+END_SRC

** Matrices
#+BEGIN_SRC octave
A = [1 2; 3 4; 5 6];
B = [1 2 3; 4 5 6];
zeros(1,3) % [0 0 0 0]
#+END_SRC

A = 
|1| 2|
|3|4|
|5|6|
#+BEGIN_SRC octave
A = [1 2; 3 4; 5 6];
#+END_SRC

B=
|1|2|3
|4|5|6
#+BEGIN_SRC octave
B = [1 2 3; 4 5 6];
#+END_SRC
*** Identity Matrix
#+BEGIN_SRC octave
eye(4) % 4x4 identity matrix
#+END_SRC
