.. _nsml download:

Download a session data
-----------------------

    Usage:
        .. code-block:: console

            nsml download [Options] SESSION PATH

        session 이 진행되면서 만들어 output 파일들을 local로 다운로드 받습니다.

    Options:
        .. py:attribute:: -f, --file

            1개의 파일 또는 directory 를 가져옵니다.

        .. py:attribute:: --overwrite

            directory 가 있다면 덮어씁니다.

        .. note:: -f 로 파일을 가져올 경우, '/app/'의 경로를 붙여주셔야 합니다.

            .. code-block:: console

                nsml download SESSION PATH -f '/app/main.py'

        .. warning:: file 이름이나 path 에 아래에 기입된 문자 외에 다른 문자가 있을 경우 에러가 납니다.


            .. code-block:: console

                A B C D E F G H I J K L M N O P Q R S T U V W X Y Z
                a b c d e f g h i j k l m n o p q r s t u v w x y z
                0 1 2 3 4 5 6 7 8 9 . _ -
                + [ ] { } ( ) '
                Space
