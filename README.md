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
* copies generated otp to clipboard and auto types it to the current window (if run from terminal then only copies to clipboard) and keeps the generated otp for 45 seconds (modify line 17 for desired time)
