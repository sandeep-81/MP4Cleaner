@echo off
setlocal enabledelayedexpansion
color A
E:
cd \hania\hania_x_maheer\reels\
set "count=0" 
for /d %%d in (*) do (
    set "a[!count!]=%%d"
    set /a count+=1
)


for /L %%x in (1,1,%count%) do (
    cd !a[%%x]!
    dir *mp4 /b
    move *.mp4 "E:\hania\hania_x_maheer\New folder\"
    cd ..
    rmdir /q /s !a[%%x]!
)

pause
