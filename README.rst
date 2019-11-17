httpcodes
=====

Http codes is a minimal package the literally maps the status-message to a status-code.
The only use-case of this package is to increase readability in your code.

Installing
----------

Install and update using `pip`_:

.. code-block:: text

    pip install -U httpcodes

A Simple Example
----------------

.. code-block:: python

    import httpcodes

    print(httpcodes.OK)
    print(httpcodes.NOT_FOUND)
    print(httpcodes.IM_A_TEAPOT)

