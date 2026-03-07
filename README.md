### Shortcuts

---

**Open file explorer:**
- Win + E

<br>

**Search in file explorer:**
- F3

<br>

**Rename the selected file:**
- F2

<br>

**Create new folder:**
- Ctrl + Shift + N

<br>

**Import or open a file:**
- Ctrl + O

<br>

**Copy instead of move and vice versa:**
- Hold Ctrl or Shift while drag and dropping your file

<br>

**Select text with mouse (more easily):**
- Double click on a word and continue the motion (thanks MHF)

<br>

**Select text with keyboard:**
- Shift + Arrows

<br>

**Go to desktop:**
- Win + D
- Click at the bottom right of the screen

<br>

**Move windows:**
- Win + Arrows

<br>

**Lock computer:**
- Win + L

<br>

**Open task manager:**
- Win + Shift + Esc

<br>

**Open settings:**
- Win + I

<br>

**Open any software that's pinned on the taskbar:**
- Win + position number on the taskbar

<br>

**Open emojis panel:**
- Win + ;

<br>

**Open or Enable clipboard:**
- Win + V (this one is amazing)

<br>

**Reopen closed tabs:**
- Ctrl + Shift + T (this one too)

<br>

**Create new tab:**
- Ctrl + T

<br>

**Switch between tabs:**
- Ctrl + Tab

<br>

**Open link in new tab:**
- Scrollwheel click on the link
- Ctrl + click on the link

<br>

**Delete tab:**
- Scrollwheel click on the tab

<br>

**Quit current window:**
- Ctrl + W (closes tabs first)
- Alt + F4

<br>

**Close window from the taskbar:**
- Scrollwheel click on the preview

<br>

**Open new window from the taskbar:**
- Scrollwheel click on the icon

<br>

**Search on current webpage or document:**
- Ctrl + F

<br>

**Redo:**
- Ctrl + Y
- Ctrl + Shift + Z (when Ctrl + Y doesn't work)

<br>

**Make text bold:**
- Ctrl + B
- Ctrl + Shift + B (when Ctrl + B doesn't work)

<br>

**Delete full word:**
- Ctrl + Del

<br>

**Delete full line:**
- Ctrl + Shift + Del

<br>

**Delete in the other direction:**
- Del (the button that says "Del", not the backspace key..)

<br>

**'Reload' GPU drivers:**
- Ctrl + Shift + Win + B

<br>

**Write É:**
- Alt + 144

<br>

**Write Ç:**
- Alt + 128

<br>

**Write œ:**
- Alt + 0156

<br>

**Write Œ:**
- Alt + 0140

<br>

**Open an admin CMD terminal:**
- Win + X then A (the second letter might vary depending on your OS language)

<br>

**Cancel an shutdown or restart:**
- If on the loading screen, spam ESC

<br>
<br>
<br>

### Web

---

**To know if you got caught torrenting:**
- https://iknowwhatyoudownload.com

<br>

**To check if you are anonymized online:**
- https://amiunique.org/fingerprint
- https://fingerprint.com/

<br>

**To find absolutely any media or website, old or not, for free:**
- https://fmhy.net
- https://cybermania.ws
- https://reddit.com/r/Piracy/wiki/megathread
- https://archive.org
- https://cinepulse.lol
- https://yopflix.my/
- https://movix.website/
- https://vimm.net/vault
- https://myrient.erista.me/files

<br>

**To quickly send files:**
- https://filebin.net
- https://transfer.zip
- https://www.swisstransfer.com/

<br>

**To transform and edit pdf files:**
- https://ilovepdf.com (tysm MHF)

<br>

**Use temporary email addresses:**
- https://temp-mail.org
- https://yopmail.com

<br>

**Humanize LLM texts (remove non keyboard tokens):**
- https://humanize-ai.click

<br>

**To get rid of ads:**
- Download uBlock Origin extension

<br>

**To automatically fill captchas:**
- Download Buster Captcha extension

<br>

**To get rid of sponsorships on youtube:**
- Download SponsorBlock extension

<br>

**To download any image with the filetype you want:**
- Download SaveAs extension

<br>

**In Google login prompts:**
- You can type your Gmail address without @gmail.com, thank me later

<br>
<br>
<br>

### Softwares

---

**To search anywhere instantly on your PC:**
- Download Everything (do it)

<br>

**To run LLMs:**
- Download GPT4All
- Download Ollama

<br>

**To generate images locally:**
- Download Stable Diffusion (with A1111)
- Download FLUX.1-schnell (with ComfyUI)

<br>

**To cut videos without quality loss and export them instantly:**
- Download LosslessCut

<br>

**To manage all your RGB devices at once:**
- Download SignalRGB

<br>

**To recover deleted files:**
- Download Recuva (having 2 disks is highly recommended)

<br>

**Control your android phone (useful if your screen is broken):**
- Download scrcpy

<br>

**To precisely identify a file type:**
- Download TrID

<br>

**To look at a file at the lowest level (hexadecimal):**
- Download HxD

<br>

**To visualize every file and their respective sizes:**
- Download TreeSize

<br>

**To basically do absolutely anything you want on your system:**
- Download Winaero Tweaker
- Download PowerToys
- Use Arch (nah)

<br>

**To do sophisticated network scans:**
- Download Zenmap

<br>
<br>
<br>

### Commands

---

**Clear cli:**
- `cls`
- `clear` (bash)

<br>

**Clean corrupted or incomplete storage or volume:**
- `diskpart`

<br>

**To activate your windows license:**
- `irm https://get.activated.win | iex` (MHF <3)

<br>

**Restart in BIOS:**
- `shutdown /r /fw` (you can make it a shortcut on the desktop, just like every command or web url, you can also add the parameter `/t 0` if you don't want to wait for the cooldown)

<br>

**Program a restart or shutdown:**
- `shutdown /r /t 3600` or `shutdown /s /t 3600` (the number is in seconds, here the action will take place in an hour, you can also cancel with `shutdown /a`)

<br>

**Force deletion of a file:**
- `del /F /Q "C:\Path\to\file"`

<br>

**Change a password:**
- `net user yourusername yournewpassword`

<br>

**Get info about your pc:**
- `systeminfo`

<br>

**Give admin rights to current account:**
- `control userpasswords2`

<br>

**Check and fix corrupted disk partitions:**
- `chkdsk`

<br>

**Check and fix corrupted system files:**
- `sfc /scannow`

<br>

**APT alternative for windows:**
- `winget`

<br>
<br>
<br>

### Settings

---

**Disable windows data collection (no more Windows updates after that):**
- System32 > drivers > etc > in host file paste:
```
127.0.0.1 localhost
::1 localhost
127.0.0.1 data.microsoft.com
127.0.0.1 msftconnecttest.com
127.0.0.1 azureedge.net
127.0.0.1 activity.windows.com
127.0.0.1 bingapis.com
127.0.0.1 msedge.net
127.0.0.1 assets.msn.com
127.0.0.1 scorecardresearch.com
127.0.0.1 edge.microsoft.com
127.0.0.1 data.msn.com
```

<br>

**Stay safe when plugging in a device:**
- Turn off Autoplay

<br>

**Get a bit of privacy on private networks:**
- Use random hardware addresses (this randomizes your MAC address)

<br>

**Make NumLock be on by default at boot:**
- Enable Bootup Numlock State in bios settings

<br>

**Prevent broken mouse:**
- Turn on Mouse Keys

<br>

**Teleport mouse on buttons on dialog boxes:**
- Mouse settings in control panel

<br>

**Turn off Windows updates (don't):**
- Win + R > services.msc > disable "windows update"

<br>

**Disable mouse acceleration:**
- Turn off enhance mouse movement

<br>

**Disable Alt + Shift changing the keyboard layout:**
- Advanced keyboard settings > Input language hotkeys > Change keys sequence
- Also disable Win + Space if you have PowerToys

<br>

**Disable sticky keys:**
- Sticky keys in settings

<br>

**To have more stable fps:**
- Disable HAGS in settings

<br>

**Disable windows automatic backup:**
- Backup settings > turn off

<br>

**Where to manage backups history:**
- appdata > local > microsoft > windows > file history

<br>

**Where to manage recent activity ("items"):**
- AppData\Roaming\Microsoft\Windows\Recent Items

<br>

**To find any windows setting:**
- Search in Windows settings
- Search in Control Panel
- Create a folder and name it "GodMode.{ED7BA470-8E54-465E-825C-99712043E01C}"

<br>

**To achieve a clean Windows install:**
- Add custom answer file to the bootable usb (Rufus)
- Install a custom version, like tiny11

<br>
<br>
<br>

### Troubleshoot

---

**Pc not connecting to network:**
- Win + R > ncpa.cpl > properties of the network card > double click on ipv4 (MHF told me)

<br>

**Gpu fans going crazy:**
- Switch the BIOS button on the GPU

<br>

**Diagonal lines on screen sometimes:**
- Change contrast slightly on the screen physical buttons

<br>

**Microsoft Store not downloading anything:**
- Regedit > Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\AppXSvc > "Start" = 2
- Who downloads things from microsoft store anyway ?

<br>

**Help troubleshoot booting issues:**
- Enable EZ debug led in BIOS

<br>

**Prevent data loss or viruses:**
- Do regular backups PLEASE, use FreeFileSync or something

<br>

**Preventing PC from getting slower:**
- Do NOT download antiviruses or cleaners. Please. Do not.

<br>

**Pc doesn't turn on after power outage:**
- Remove motherboard CMOS battery for 5 minutes and put it back
- Replace motherboard CMOS battery (if the above doesn't work)
