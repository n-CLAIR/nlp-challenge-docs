
.. _nsml logs:

Get a log from session
----------------------

    Usage:
        .. code-block:: console

            nsml logs [Options] SESSION

        session 에서 만들어진 log 를 보여줍니다.

    Example:
        .. code-block:: console

            nsml logs -f nsmlteam/NER/4

    Options:
        .. py:attribute:: -f, --follow

            session 이 종료될 때까지 log 를 streaming 합니다.
