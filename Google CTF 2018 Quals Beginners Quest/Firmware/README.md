# Firmware

> https://ctftime.org/writeup/10328

This time we got an ext4 file. 7-zip supports a lot of formats (including virtual machines disks and filesystem images) and ext4 is one of them.
In the root directory there is a file `.mediapc_backdoor_password.gz`. When you unpack it you get `.mediapc_backdoor_password` file which contains flag.

Flag: `CTF{I_kn0W_tH15_Fs}`
