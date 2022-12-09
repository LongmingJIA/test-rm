# test-rm
It so hard but i am tring to record some problem i meet and solve it,and write down in this file

Linux cmake上遇到的大小事
用cmake一定要更改.vscode文件特别注意task.json
command ："mkdir build; cd./build;make",

launch.json 更改"program" :"${worksoaceFolder}/build/你的二进制文件"
断点测试在cmake加上
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
断点调试可能会有一个文件打不开
安装这个文件并且把这个文件拖进那个打不开的文件夹里。
