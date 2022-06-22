# Goldman_Sachs_Internship


## Password Cracking and Security 

### Overview 
As a governance analyst it is part of your duties to assess the level of protection offered by implemented controls and minimize the probability of a successful breach. You often need to know the techniques used by hackers to circumvent implemented controls and propose uplifts to increase the overall level of security in an organization. Gaining valid credentials gives the attackers access to the organization’s IT system, thus circumventing most of perimeter controls in place.

## Project Objectuve
`What type of hashing algorithm was used to protect passwords?`

`What level of protection does the mechanism offer for passwords?`

`What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?`

`What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?`

`What would you change in the password policy to make breaking the passwords harder? `


After the conducted analysis it was determined that organization uses an outdated password hashing algorithm (MD5) which offers very little protection in the event of a password database leaking. It was also determined that the current password policy is not aligned with industry best practices allowing users to have short passwords (6 characters) and reuse usernames as part of passwords. 

As a result of the analysis the following uplifts are proposed to increase the overall level of password protection:  

•	It is advised to educate users on creating safe and easy to remember passwords. Having a password policy requiring long passwords with a number of special characters results in user writing passwords down or constantly resetting them. The best way to create a strong and user-friendly password is using passphrases (e.g.  mygrannyschairhadstaples). The best way to create such passwords is to combine a couple of completely random word. It’s also advised to use some special characters and numbers as easy to remember substitutions to expand the key space (e.g. mYgranny$cha1rhadstaples)

•	Educate users on the benefits of passwords managers. Having a password manager allows having very long and completely random passwords (e.g. M>?{tk6Cfep6BrZ4J)KZWQ8j) without the need to remember/write down. A strong passphrase is still required as a master key for to access the password manager.

# Project Report and Observations 
Completing this task assigned by Goldman Sachs, MD5 and SHA were the two algorithms that I came across. Analysing the passwords and their respective security algorithms used, I narrowed down my observations into this report.

## Project Report
```
Sir/Madam,
The leaked hashes uses MD5 hashing algorithm, which according to my observation is providing very little protection in case of database leaking.
The hashing algorithms like MD5 and SHA-family of algorithms are the standard one's but not that strong.

After trying to crack the passwords I came across certain drawbacks of company's policy.
1. The passwords were using very common combinations and there was no specific rules on their creation.
2. The length was short which in case of cracking could be an advantage for the hackers.
3. Salting was not implemented as it creates a strong hash value.
4. Strong hashing algorithms were not used.

The changes I would suggest in the password policy are:
1. Creating combination of letters, numbers and symbols is the best approach to begin with.
2. Don't let users use common words, their username, personal information or combination of that as a password.
3. The length should be increased.
4. Hashing algorithms like bcrypt, scrypt or PBKDF2 can be used. It is ought to increase the time in cracking.


Thanking you, 
Rishaw Kumar
```
## Observations:
```
Security Algorithms used : MD5

experthead:e10adc3949ba59abbe56e057f20f883e
interestec:25f9e794323b453885f5181f1b624d0b
ortspoon:d8578edf8458ce06fbc5bb76a58c5ca4
reallychel:5f4dcc3b5aa765d61d8327deb882cf99
simmson56:96e79218965eb72c92a549dd5a330112
bookma:25d55ad283aa400af464c76d713c07ad
popularkiya7:e99a18c428cb38d5f260853678922e03
eatingcake1994:fcea920f7412b5da7be0cf42b8c93759
heroanhart:7c6a180b36896a0a8c02787eeafb0e4c
edi_tesla89:6c569aabbf7775ef8fc570e228c16b98
liveltekah:3f230640b78d7e71ac5514e57935eb69
blikimore:917eb5e9d6d6bca820922a0c6f7cc28b
johnwick007:f6a0cb102c62879d397b12b62c092c06
flamesbria2001:9b3b269ad0a208090309f091b3aba9db
oranolio:16ced47d3fc931483e24933665cded6d
spuffyffet:1f5c5683982d7c3814d4d9e6d749b21e
moodie:8d763385e0476ae208f21bc63956f748
nabox:defebde7b6ab6f24d5824682a16c3ae4
bandalls:bdda5f03128bcbdfa78d8934529048cf

Cracked Passwords:
e10adc3949ba59abbe56e057f20f883e:123456
e99a18c428cb38d5f260853678922e03:abc123
d8578edf8458ce06fbc5bb76a58c5ca4:qwerty
96e79218965eb72c92a549dd5a330112:111111
3f230640b78d7e71ac5514e57935eb69:qazxsw
fcea920f7412b5da7be0cf42b8c93759:1234567
f6a0cb102c62879d397b12b62c092c06:bluered
25d55ad283aa400af464c76d713c07ad:12345678
5f4dcc3b5aa765d61d8327deb882cf99:password
8d763385e0476ae208f21bc63956f748:moodie00
```
Complete Report:
(https://github.com/rishawsingh/Goldman_Sachs_Internship/blob/main/Goldman%20Sachs%20Internship%20Report.pdf)

### RESOURCES:
https://arstechnica.com/information-technology/2013/05/how-crackers-make-minced-meat-out-of-your-passwords/

https://howsecureismypassword.net/

https://en.wikipedia.org/wiki/Password_cracking#Software

https://en.wikipedia.org/wiki/Salt_(cryptography)

https://hashcat.net/hashcat/
