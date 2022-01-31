# kurame-scoop-bucket
Scoopのbucket

- ハッシュはzipの方の値を指定する

ハッシュ値は以下で取れる。
```powershell
Get-FileHash app_file | % { $_.Hash } | Set-Clipboard
```

