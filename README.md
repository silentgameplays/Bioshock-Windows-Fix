# Bioshock-Windows-Fix
How to get the original Bioshock without the annoying 2k launcher running on Windows 10/11


0. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support and just in case install DirectX 9.0c:

https://www.microsoft.com/en-us/download/details.aspx?id=8109

1. Install Bioshock

2. Go to Steam>Properties>General>Launch Options 

3. Enter: -dx9 -windowed 

4. Go to C:\Program Files (x86)\Steam\common\Bioshock\Builds\Release

5. Find Bioshock.exe

6. Select Properties > Compatibility

7. Select Compatibility Mode Windows XP3

8. Select Run This program as an Administrator 

9. Click Apply>Ok

10. Laucnh Bioshock.

11. Go into Settings set Resolution to your monitor resolution 1080p is supported

12. Set Fullscreen

13. Exit 

14. Again go to Steam>Properties>Launch Options 

15. Remove: -windowed 

16. Play the game.

17. For Audio Fix drop the openal32.dll file from this repo into your C:\Program Files (x86)\Steam\common\Bioshock\Builds\Release folder

18. Disable reverb in Audio Settings. 

# NB! DX10 support for this game is borked, so use at your own risk! 

# NB2! If you experience crashes due to enabled Steam Overlay then

# Disable Steam Overlay:
Steam > Properties > Under the General tab > Uncheck Enable the Steam Overlay.

# You are good,enjoy the classic.
# silentgameplays
Don't forget to subscribe to my YouTube channel.
https://www.youtube.com/@silentgameplays

