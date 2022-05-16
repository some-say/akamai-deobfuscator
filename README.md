# akamai-deobfuscator

## This project is now in an archived state and will not be receiving updates. 

Apologies, this project is now in an archived state and will not be receiving updates.

This started as a fun learning and teaching project but I feel it likely only benefits those with malicious intent (credential stuffers) and those looking to make a profit from open source projects without giving back.

I have the code for deobfuscating current Akamai but I will not be releasing it for the reasons listed above.


=======================================================

A tool to help you to recover function and property names to better reverse-engineer Akamai scripts.

#### Before Deobfuscation
![Before deobfuscation](https://i.imgur.com/mfDpFCy.png)

#### After Deobfuscation
![After deobfuscation](https://user-images.githubusercontent.com/25884226/132633792-efd918ab-d43e-4939-bd37-3be4368af91f.png)
### Usage
Install the dependencies  start the script.

```sh
$ cd akamai-deobfuscator
$ npm install
$ npn run start <url>
```

The output is in `/out/output.js`
