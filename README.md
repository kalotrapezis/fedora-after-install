# fedora-after-install
The steps I follow to restore a fedora installation

Affter I restore the settings I use Picka Backup to backup my files
https://flathub.org/apps/details/org.gnome.World.PikaBackup

* In oeder of the flatpak steam client to have access to external hard drives you need to execute this command
flatpak override --user --filesystem=/mnt/hard-drive-name com.valvesoftware.Steam

New!!!!!!
The "up" script is an updating script that updates the system and the applications without the need for "sudo". Just give it executable permissions and it will show a progress bar while updating the system. The UI was ment for KDE I don't know if it works on GNOME. It's basicly 2 commands
"rpm-ostree update and flatpak update -y" run it automaticaly on system startup and that's that.
