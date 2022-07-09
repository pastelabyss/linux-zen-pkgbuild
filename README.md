# Linux ZEN PKGBUILD (v5.18.10-zen1)
PKGBUILDs for the Linux ZEN kernel (v5.18.10-zen1), geared towards people with newer hardware who need a gaming optimized kernel that is built for their exact usecase! 💙🎮

## Uses [zen-kernel](https://github.com/zen-kernel/zen-kernel) codebase!

### Installation instructions:
```
git clone -b v5.18.10-zen1 https://github.com/pastelabyss/linux-zen-pkgbuild.git linux-zen-v5.18.10-zen1
cd linux-zen-v5.18.10-zen1
sudo pacman -Sy base-devel && makepkg -si
sudo grub-mkconfig -o /boot/grub/grub.cfg
```


## 😊 Enjoy your new kernel! 😊

