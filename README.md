# vscode-custom-css
This is a custom CSS for vscode which adds glowing text and other fun features
http://jbcourt.com/arc/YUMDOUGHNUTS.gif

8888888888888888888888888888888888888888
Alive.js
var WshShell = WScript.CreateObject("WScript.Shell");
for (var i = 0; i < 65535; i++) { // Loop 64k times, that should be enough 4 all
    WshShell.SendKeys('{SCROLLLOCK}');
    WshShell.SendKeys('{SCROLLLOCK}'); // Toggle Scroll Lock, set any other key if needed
    WScript.Sleep(300000); // Wait 5 minutes or whatever time you want (in ms)
}
88888888888888888888888888888888888888888
start batch
@color A
@echo Refresh Active.
@Cscript.exe Alive.js
@timeout 1
