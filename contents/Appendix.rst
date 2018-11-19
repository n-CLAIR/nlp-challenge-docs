Appendix
========

.. toctree::
    :maxdepth: 1
    :glob:

    appendix/*


Notification
------------

    session의 상태 변화를 email을 통해 알람을 받을 수 있습니다.

    https://hack.nsml.navercorp.com/settings/profile

    .. note:: **session의 상태가 zombie가 되는 조건**

        GPU를 할당받고 실행 중이지만 1시간 동안 사용량이 0 인 경우 상태가 zombie로 표시됩니다. (여러 대의 GPU를 할당 받고 하나의 GPU라도 사용량이 0일 때도 zombie가 됩니다. )


Policy
------

    - 한 유저가 동시에 실행 가능한 GPU의 최대 개수는 credit에 따라 달라집니다.
