cd\
md TEST123
cd TEST123
md AAA
md BBB
md CCC
cd BBB
md DDD
cd..
cd CCC
dir C:\Windows >list.txt
cd\
del /Q /S TEST123
cd TEST123
cd BBB
rmdir /Q DDD
cd..
rmdir /Q AAA
rmdir /Q BBB
rmdir /Q CCC
cd..
rmdir /Q TEST123