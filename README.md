# snow-crash
 cyber security project

## How to start
1. move `SnowCrash.iso` to current directory.
```
cp /path/to/iso/SnowCrash.iso .
```
2. install `QEMU`
```
brew install qemu
```
* install `homebrew` if you don't have one.
3. run `run.sh`
```
sh run.sh
```
4. access with ssh (in different terminal)
```
ssh level00@localhost -p 4242

Are you sure you want to continue connecting (yes/no/[fingerprint])?  yes
	   _____                      _____               _
	  / ____|                    / ____|             | |
	 | (___  _ __   _____      _| |     _ __ __ _ ___| |__
	  \___ \| '_ \ / _ \ \ /\ / / |    | '__/ _` / __| '_ \
	  ____) | | | | (_) \ V  V /| |____| | | (_| \__ \ | | |
	 |_____/|_| |_|\___/ \_/\_/  \_____|_|  \__,_|___/_| |_|

  Good luck & Have fun

          10.0.2.15 fec0::94e:a3d2:6197:6277 fec0::5054:ff:fe12:3456
level00@localhost's password:
level00@SnowCrash:~$
```
now you are in VM!