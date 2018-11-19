.. _nsml model pull:

Pull models
-----------

    Usage:
        .. code-block:: console

            nsml model pull [Options] SESSION CHECKPOINT PATH

        :ref:`nsml.save<nsml.save()>` 로 저장된 모델들을 local로 가져옵니다. :ref:`nsml model ls<nsml model ls>` 로 모델 목록을 확인할 수 있습니다.

    Example:
        .. code-block:: console

            nsml model pull nsmlteam/NER/4 24 ./
