DUAL PAIR TAP - Windows 10/11 x64

1. Extract this ZIP and open DualPairTap.exe. No installation required.
2. Disable Corsair FlashTap in iCUE / Web Hub so the app sees both keys.
3. Release W/A/S/D, then press F8 or click Enable.
4. F8 toggles. F9 pauses immediately. Closing the window stops the app.

A/D and W/S are independent. Hold A, press D: D replaces A. Release D
while holding A: A resumes. W/S behaves the same way. Diagonals work.
The app starts paused. Release movement keys before toggling. Test outside
a game first. Enable the app and hold combinations; the Output line shows
which key wins in each pair. Pause for normal typing.

This is a separate software remapper, not a Corsair firmware modification.
It applies globally to all keyboards and uses physical US W/A/S/D positions.
F8 and F9 are reserved while the app runs. No logging or network access.
Windows may show an unknown-publisher prompt for this unsigned local build.

Games using raw keyboard input or rejecting software-generated input may
not behave like the Output indicator. Compatibility with your Vanguard and
game has NOT been verified. It does not bypass anti-cheat. Check your game's
rules for SOCD / last-input-priority features before using it there.
Windows can block output into apps running at a higher privilege level.
Do not enable Corsair FlashTap and this remapper at the same time.

Source is included. To rebuild using the Windows .NET Framework compiler:
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\csc.exe /nologo /target:winexe /platform:x64 /out:DualPairTap.exe /r:System.Windows.Forms.dll /r:System.Drawing.dll Program.cs

Validation: Tests.cs exhausts 65,536 event histories and checks independent
pairs. Hardware/game testing remains required. No automatic startup.
