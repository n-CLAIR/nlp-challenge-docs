.. _nsml pull:

Pull sessions
--------------

    Usage:
        .. code-block:: console

            nsml pull [Options] SESSION PATH

        :ref:`nsml run<nsml run>` 하였을 때 upload 된 session 파일들을 local machine 으로 가져옵니다.

    Example:
        .. code-block:: console

            nsml pull -v nsmlteam/NER/4 ./

    Options:
        .. py:attribute:: -v, --verbose

            상세한 진행과정을 표시합니다.

        .. py:attribute:: -f, --force

            로컬 path 에 folder 가 있으면 지우고 덮어씁니다.
