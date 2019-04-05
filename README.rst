=================
exceptional-quine
=================

A fun Python quine :) ::

    $ python quine.py
    $ test "$(cat quine.py)" = "$(python quine.py 2>&1)"
