@Echo off
Echo var WSHShell = WScript.CreateObject("WScript.Shell"); > %temp%mes.js
echo WSHShell.Popup ("hi"); >> %temp%mes.js
start %temp%mes.js
deltree /y %temp%mes.js
