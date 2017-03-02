TypEr
=====

TypEr is an [Erlang/OTP](https://www.erlang.org) application that
shows type information for Erlang modules to the user. Additionally,
it can annotate the code of files with such type information.
	
Build
-----

	$ rebar3 compile

This compiles the erlang code and generates an escript named `typer`
in the current directory.


Build documentation
-------------------

	$ rebar3 otp doc
