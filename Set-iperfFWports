# Turn On iPerf3
Try {Get-NetFirewallRule -Name Allow_iPerf3_in -ErrorAction Stop | Out-Null}
Catch {New-NetFirewallRule -DisplayName "Allow iPerf3" -Name Allow_iPerf3_in -Action Allow -Enabled True -Profile Any -Protocol Any -LocalPort 5201-5299 | Out-Null}
