git clone https://github.com/Forbidden-Darkness/BC-250-Bazzite-Setup-Scripts.git

cd BC-250-Bazzite-Setup-Scripts/

chmod +x *.sh

sudo ./BC-250 CPU&CU Overclock-Live Manager.sh

or

sudo ./Install-Blue-Red-Pill-16or32GB-ACPI_Fix-Option.sh

or

sudo ./enable_wol.sh

or


sudo ./New-BC250 Overclock-Live-Manager.sh

or

sudo ./New-Enable_WOL.sh

or

sudo ./New-Install-Blue-Red-Pill-ACPI-Fix.sh

bc250-gfxclk-fix created by Punsh:

Corrects GPU frequency reporting on the AMD BC-250 (Cyan Skillfish / gfx1013) board when all 8 physical CPU cores are enabled, on Bazzite / SteamOS-style image-based (immutable) distros where rebuilding `amdgpu.ko` isn't practical.
