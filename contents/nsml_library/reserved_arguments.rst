.. _reserved arguments:

reserved arguments
------------------

    NSML 에서는 세션을 재생성 하는 command 들(:ref:`nsml fork<nsml fork>`, :ref:`nsml submit<nsml submit>`)을 사용할 때 entry 파일에서 다음의 3가지
    옵션을 받을 수 있어야 합니다.

    .. py:attribute:: --mode TEXT

        들어온 command 가  :ref:`nsml submit<nsml submit>` 일 경우 사용됩니다.

        :ref:`nsml submit<nsml submit>`
            \-\-mode test 로 설정됩니다.

    .. py:attribute:: --pause INTEGER

        model 을 load 할때 1로 설정됩니다.

    .. py:attribute:: --checkpoint TEXT

        :ref:`nsml fork<nsml fork>` 할때의 체크포인트로 설정됩니다. 체크포인트 옵션을 안주면 마지막 wall time 의 model 을 가져옵니다.
