@echo off
setlocal enabledelayedexpansion
for /l %%i in (1,1,10) do (
    set "folder=app_00%%i"
    md !folder!
)



