# [Crack The Hash](https://www.tryhackme.com/room/crackthehash)

## [Task 1] Level 1

1 48bb6e862e54f2a795ffc4e541caed4d
	john --wordlist=/usr/share/wordlists/rockyou.txt --format=raw-md5 1.hash
> easy

2 CBFDAC6008F9CAB4083784CBD1874F76618D2A97
	john --wordlist=/usr/share/wordlists/rockyou.txt --format=raw-sha1 2.hash
> password123

3 1C8BFE8F801D79745C4631D09FFF36C82AA37FC4CCE4FC946683D7B336B63032
	john --wordlist=/usr/share/wordlists/rockyou.txt --format=raw-sha256 3.hash
> letmein


4 $2y$12$Dwt1BZj6pcyc3Dy1FWZ5ieeUznr71EeNkJkUlypTsgbX1H68wsRom
> bleh

5 279412f945939ba78ce0758d3fd83daa
> Eternity22


## [Task 2] Level 2

1 F09EDCB1FCEFC6DFB23DC3505A882655FF77375ED8AA2D1C13F640FCCC2D0C85
	john 2-1.hash --format=raw-sha256
> paule

2 Hash: 1DFECA0C002AE40B8619ECF94819CC1B
> n63umy8lkf4i

3 Hash: $6$aReallyHardSalt$6WKUTqzq.UQQmrm0p/7MPpMbGNnzXPMAXi4bJMl9be.cfi3/qxIf.hsGpS41BqMhSrHVXgMpdjS6xeKZAs02.
	Salt: aReallyHardSalt
	Rounds: 5
> waka99

4 Hash: e5d8870e5bdd26602cab8dbe07a942c8669e56d6
	Salt: tryhackme
> 481616481616


### Written By : wh0am1

### GitHub : [wh0th3h3llam1](https://github.com/wh0th3h3llam1)

<!-- ### TryHackMe : ![wh0am1](http://tryhackme-badges.s3.amazonaws.com/wh0am1.png "wh0am1") -->

### TryHackMe : [wh0am1](https://tryhackme.com/p/wh0am1)
