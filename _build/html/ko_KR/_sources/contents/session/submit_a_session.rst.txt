.. _nsml submit:

Submit a session
----------------

    Usage:
        +------------------------------------------------------+
        | **nsml submit** *Options* SESSION_NAME *CHECKPOINT*  |
        +------------------------------------------------------+

        session 을 submit 하여서 leaderboard 에 점수를 제출합니다. 하루에 submit 횟수는 제한이 없습니다. 다만 submit을 한 번 했다면 1시간 후에 다시 submit이 가능합니다. 즉, submit 시간 간격은 1시간이 넘어야 합니다. (단, -t 옵션을 사용하는 submit은 submit 시간 간격 카운트에 포함되지 않습니다.)

    Example:
        .. code-block:: console

            nsml submit nsmlteam/NER/4 32

        .. code-block:: console

            nsml submit -t nsmlteam/NER/4 32

    Options:

        -t, --test

            실제로 점수를 제출하기 전, 데이터의 포맷 오류나 기타 버그들을 찾기 위해
            
            지원하는 debug 모드(test 모드)로 session 을 제출합니다.

            test 모드로 제출 후 session이 새로 생기면 :ref:`logs<nsml logs>` 를 보고

            debugging 을 할 수 있습니다.
