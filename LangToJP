Install-Language ja-JP -CopyToSettings
Set-SystemPreferredUILanguage ja-JP
Set-WinUILanguageOverride -Language ja-JP
Set-WinCultureFromLanguageListOptOut -OptOut $False
Set-TimeZone -Id "Tokyo Standard Time"
Set-WinHomeLocation -GeoId 0x7A
Set-WinSystemLocale -SystemLocale ja-JP
Set-WinUserLanguageList -LanguageList ja-JP,en-US -Force
Set-WinDefaultInputMethodOverride -InputTip "0411:00000411"
Copy-UserInternationalSettingsToSystem -WelcomeScreen $true -NewUser $true

Restart-Computer
