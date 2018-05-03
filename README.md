gen_fsm_compat
=====

This is a copy of erlangs (19.3) gen_fsm. With `gen_fsm` being deprecated this will allow projects that use it to go forward without problems and backwards compatibility issues.

Usage
-----

* Add `gen_fsm_compat` to your rebar3 dependencies.
* Add it to your applications in the `.app.src`.
* Use `gen_fsm_compat` where `gen_fsm` was used.

Build
-----

    $ rebar3 compile
