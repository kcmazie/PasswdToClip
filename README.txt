# PasswdToClip

          File Name : PasswdToClip.ps1
    Original Author : Kenneth C. Mazie (kcmjr AT kcmjr.com)
                    :
        Description : Generates a random/semi-random password and outputs it as specified.
                    : Use for one-click passwords when creating new user accounts.
                    :
              Notes : This is best used when added to the Windows task bar via a shortcut.
                    : Create a shortcut using the following parameters.
                    : Target = C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe -noninteractive -NoProfile -WindowStyle Hidden -nologo -file "C:\passwdtoclip.ps1"
                    : Start in = C:\Windows\System32\WindowsPowerShell\v1.0
                    : Run = Minimized
                    : Shortcut name = Generate Password
                    : Shortcut icon = %SystemRoot%\System32\changepk.exe
                    : Once created pin the shortcut to the Windows taskbar. A single click will generate a password and
                    : deposit it where specified. If clipboard is selected you then simply paste (CTRL-P) to apply.
                    :
          Arguments : Command line options:
                    : None
                    :
           Warnings : None
                    :
              Legal : Public Domain. Modify and redistribute freely. No rights reserved.
                    : SCRIPT PROVIDED "AS IS" WITHOUT WARRANTIES OR GUARANTEES OF
                    : ANY KIND. USE AT YOUR OWN RISK. NO TECHNICAL SUPPORT PROVIDED.
                    :
            Credits : Code snippets and/or ideas came from many sources including but
                    : not limited to the following:
                    :
     Last Update by : Kenneth C. Mazie
    Version History : v1.00 - 02-06-18 - Original
     Change History : v1.01 - 05-25-14 - Minor edits. Added headers for upload to gallery.
                    : v1.02 - 00-00-00 -
