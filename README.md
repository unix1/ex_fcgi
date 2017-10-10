ex_fcgi
=======

ex_fcgi is a straightforward [FastCGI](http://www.fastcgi.com/) client written
in Erlang.

This is a fork of [extend/ex_fcgi](https://github.com/extend/ex_fcgi) which is
no longer maintained in that repo. I have made minor updates for dialyzer so
it has a clean outpout for [cowboy_fcgi](https://github.com/unix1/cowboy_fcgi).

Goals
-----

ex_fcgi aims to implement the FastCGI protocol, more specifically the parts of
it actually used in the real world. As with
[cowboy](https://github.com/ninenines/cowboy), do not expect any evil
parameterized module or process dictionary.

This is a work in progress and suggestions are welcome; feel free to contribute
by reporting problems via issues or sending pull requests.
