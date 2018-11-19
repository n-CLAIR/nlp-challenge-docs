.. _nsml rm:

Delete a session
----------------

    Usage:
        .. code-block:: console

            nsml rm [Options] SESSION

        하나 또는 여러 개의 session 을 삭제합니다. 정규식의 * 와 ? 를 이용하면 여러 개의 session을 삭제할 수 있습니다.

    Example:
        .. code-block:: console

            nsml rm nsmlteam/NER/4

    Options:
        .. py:attribute:: -s, --skip

            NSML storage 에서 session 삭제하는 것을 skip 합니다.

        .. py:attribute:: -f, --force

            실행 중인 session 을 강제로 삭제합니다.
