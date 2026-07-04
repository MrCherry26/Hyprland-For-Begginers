I will asume your using arch
before install, install kitty and waybar before system install
when in hyprland, complete welcome screen and hit win + q
run command "Waybar & disown"
connect to wifi using the 4 bars icon on bar at top of screen
install browser in pacman repo (Suggested firefox)
run commands untill blank line;
sudo pacman -S --needed base-devel git
git clone https://aur.archlinux.org/yay.git
cd yay
makepkg -si

After that install your apps using yay -S app-name
Then read basic customizeation
