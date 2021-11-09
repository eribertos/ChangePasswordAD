Import-Module ActiveDirectory
$newPass=(ConvertTo-SecureString -AsPlainText -String "NovaSenha" -force)
Get-Content D:\UserAD.txt | Set-ADAccountPassword -NewPassword  $newPass -Reset
