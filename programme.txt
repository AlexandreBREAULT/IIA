@echo off
title programme1
md C:\temp
Cd C:\temp
md C:\temp\IIA
md C:\temp\IIA\BTS
md C:\temp\IIA\BTS\A1
md C:\temp\IIA\BTS\A2
echo ligne1 > test.txt
echo ligne2 >> test.txt
type test.txt
pause
echo ligne0 > test.txt
type test.txt
pause
tree
pause
