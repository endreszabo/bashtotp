# bashtotp
OTP authentication with bash + dmenu [+gpg]

# requirements
* [oath-toolkit](http://www.nongnu.org/oath-toolkit/)
* [gnupg](https://www.gnupg.org/) (for encrypting/decrypting secrets)
* [xclip](https://github.com/astrand/xclip) (for clipboard operations)
* [dmenu](http://tools.suckless.org/dmenu/) (for selecting secret)

# notes
* gpg encrypt your otp secrets into a folder and replace \<FULLPATH> in line 4
* assign a shortcut
* auto types the generated otp to the current window and keeps the generated otp for 45 seconds (modify line 8 for desired time)
