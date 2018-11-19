.. _nsml submit:

Submit a session
----------------

    Usage:
        .. code-block:: console

            nsml submit [Options] SESSION CHECKPOINT

        session 을 submit 하여서 leaderboard 에 점수를 제출합니다.

    Example:
        .. code-block:: console

            nsml submit -t nsmlteam/NER/4 32

    Options:

        .. py:attribute:: -t, --test

            실제로 점수를 제출하기전 test 모드로 session 을 제출합니다. test 모드로 제출후 session 이 새로 생기면 :ref:`logs<nsml logs>` 를 보고
            debugging 을 할 수 있습니다.
