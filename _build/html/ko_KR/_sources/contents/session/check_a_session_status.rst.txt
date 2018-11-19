.. _nsml ps:

Check a session status
----------------------

    Usage:
        .. code-block:: console

            nsml ps [Options]

        session 들의 목록을 보여줍니다.

    Example:
        .. code-block:: console

            nsml ps -n 10


    Options:
        .. py:attribute:: -n, --last

            가장 최근 생성된 n 개의 session 들을 보여줍니다.

        .. py:attribute:: -a, --all

            종료된 session 까지 포함하여 보여줍니다.

        .. py:attribute:: -j, --json-return

            json format 으로 출력합니다.

        .. py:attribute:: -d, --data

            session 을 dataset 으로 filtering 하여 보여줍니다. ex) nsml ps -d NER

        .. py:attribute:: -s, --search

            해당하는 session 만 보여줍니다. ex) nsml ps -s SESSION
