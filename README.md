# magic_ball
Игрушка "Волшебный шар" при встряхивании и очередном вашем вопросе выдает ответ.

Программа magic_ball илюстрирует как работает игрушка "Волшебный шар".

Для этого
В реальности вы сами задаете вопрос

High performance Restful web-service library written in C++11 based on boost.ASIO and CRUD handlers

This library supports persistent connections to achieve highest throughput and utilizes optinally regex for enpoints

build 

Installing from GitHub
git clone https://github.com/venediktov/CRUD.git
Building on Linux
$ mkdir Release
$ cd Release
$ cmake -DCMAKE_BUILD_TYPE=Release -DCRUD_WITH_EXAMPLES=1 .. -G "Unix Makefiles"
$ make -j $(nproc) install
Building on Mac OS
$ mkdir Release
$ cd Release
$ cmake -DCMAKE_BUILD_TYPE=Release -DCRUD_WITH_EXAMPLES=1 .. -G "Unix Makefiles"
$ make -j $(sysctl -n hw.physicalcpu) install
Running examples
$ cd Release/examples
