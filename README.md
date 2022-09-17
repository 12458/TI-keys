# Texas Instruments OS Signing Cryptographic Keys
- [Cryptographic Keys](#cryptographic-keys)
  - [Texas Instruments cryptographic keys](#texas-instruments-cryptographic-keys)
  - [Raw key information](#raw-key-information)
    - [01: TI-92 Plus OS signing key](#01-ti-92-plus-os-signing-key)
    - [02: TI-73/Explorer OS signing key](#02-ti-73explorer-os-signing-key)
    - [03: TI-89 OS signing key](#03-ti-89-os-signing-key)
    - [04: TI-83 Plus / Silver Edition OS signing key](#04-ti-83-plus--silver-edition-os-signing-key)
    - [08: Voyage 200 OS signing key](#08-voyage-200-os-signing-key)
    - [09: TI-89 Titanium OS signing key](#09-ti-89-titanium-os-signing-key)
    - [0A: TI-84 Plus / TI-84 Plus Silver Edition OS signing key](#0a-ti-84-plus--ti-84-plus-silver-edition-os-signing-key)
    - [0101: TI-92 Plus Flash application signing key](#0101-ti-92-plus-flash-application-signing-key)
    - [0102: TI-73/Explorer Flash application signing key](#0102-ti-73explorer-flash-application-signing-key)
    - [0103: TI-89 Flash application signing key](#0103-ti-89-flash-application-signing-key)
    - [0104: TI-83 Plus Flash application signing key](#0104-ti-83-plus-flash-application-signing-key)
    - [0108: Voyage 200 Flash application signing key](#0108-voyage-200-flash-application-signing-key)
    - [0109: TI-89 Titanium Flash application signing key](#0109-ti-89-titanium-flash-application-signing-key)
    - [010A: TI-84+ / TI-84 Silver Flash application signing key](#010a-ti-84--ti-84-silver-flash-application-signing-key)
    - [010F: TI-84 Plus C Silver Edition Flash application signing key](#010f-ti-84-plus-c-silver-edition-flash-application-signing-key)
    - [Date-stamp signing key for:](#date-stamp-signing-key-for)
  - [.key signing files](#key-signing-files)
  - [how to use .key files](#how-to-use-key-files)
## Texas Instruments cryptographic keys
Texas Instruments uses a series of RSA cryptographic keys in their line of graphing calculators to digitally sign Flash applications and operating system upgrades. This is necessary to transfer and store first- and third-party Flash applications and operating systems on these calculators.

TI has kept nearly all of these keys a secret to prevent us from using our calculators the way we want to use them, but we have recently discovered what they are and have begun using them to create viable replacements for TI's OS (or AMS, if you have a 68k model) as well as Flash applications for every model from the TI-73/Explorer to the Voyage 200.

As a user, these keys are not very important, but for developers, these are an important step in distributing your application or OS. I have included the raw key information, the .key files for use with signing utilities, and instructions on how to use them. Hopefully this helps someone out there.

## Raw key information
### 01: TI-92 Plus OS signing key
```
n=AD49CA3CFEF1F2DE400B5D3790813BF3822CB0BD83E3F565CE81B3A6CEF36FB8
33D932596D0E979615BAB6811ABE68834CA7CEBF46145C1DD1920AA4E9558DF7
p=331792FFBB24450379CD2FA4F562961625E0EF737006A375CB9ABEA2C9D4E251
q=3644570912C38CD2D25322B5C2074DC9C40B774873F4BCEF8E1D2526237DE51C7
e=11
d=7020B00959AB9D2665AD0014E50853F7EAD19F89AFB19EC9678119E467CAB1B1
19F600276590FBF65BE2A49E214A26963A827242F8231EBC9EEABFA3B3FFA391
```
### 02: TI-73/Explorer OS signing key
```
n=F3FA1D8F06918D7CAA2A3D1EE76563E96F9FD0D6068647A7C17CFE427F8B0BE1
B8347669EFDD16EE9EE8D02738DC1E44C961FE1F8230FA49C99B98C0556D3981
p=1ECCBA67FE2BFB6A29EFF138C2B55224FAE7D9ADBBAC2FE93422AB5745FDA6E1
q=7EBE11E729ADCBEE93031F5EE347E414F064E225169B9D389F3B499DC04BE06A1
e=11
d=396806F47A04214A82644A9DDC17DB45FC259A8CB63DB681D32C780FA58A20E7E
C982512AB04CA7EE301A03C4BAF2FB8A791E261F7B74923715B5EF4028420F1
```
### 03: TI-89 OS signing key
```
n=8976D4B5045A8988FB2BBAF8BADAFAFA4C5F8ABD5A9453D46790B33A03F6C225
AAF31500E8246E63498D85A1C7C8240E0630331F1291F6F4F21611BD661FC2E7
p=4EEC590226B160EB0C00C1A5FE84011BC04947EDB01EB434C3581CC2D901223
q=1BDE307D27AD9ED6CF7ABB0D8F16F6E42175446D065B478CB248726E6C7F5F6E6D
e=11
d=7134AF2BA93B8052B0BA99FA034AECCE20C726F64A984509463AEDF38ACB36626
85416968C52104F822D49DB8DED0EF07318BF6FA659D1FF7A1E75F4D4BE54C1
```
### 04: TI-83 Plus / Silver Edition OS signing key
```
n=82EF4009ED7CAC2A5EE12B5F8E8AD9A0AB9CC9F4F3E44B7E8BF2D57A2F2BEACE
83424E1CFF0D2A5A7E2E53CB926D61F347DFAA4B35B205B5881CEB40B328E58F
p=B709D3A0CD2FEC08EAFCCF540D8A100BB38E5E091D646ADB7B14D021096FFCD
q=B7207BD184E0B5A0B89832AA68849B29EDFB03FBA2E8917B176504F08A96246CB
e=11
d=4D0534BA8BB2BFA0740BFB6562E843C7EC7A58AE351CE11D43438CA239DD9927
6CD125FEBAEE5D2696579FA3A3958FF4FC54C685EAA91723BC8888F292947BA1
```
### 08: Voyage 200 OS signing key
```
n=8307B022CEC848E14CA5D57C0C148A4803FEB19F7EEEC4493C860DF89594250E
8F0F80B7AB18CF03C27A07C1BA41B5ED4368261F4427BBE200A3B017EE100511
p=8FAEE8D84AB6F0AE8FCED849C52A5E5E63366D2484CE172685BADE4D908EE7B
q=E974B04EBBCA3F5AF86576CEEF637470F2AA78B84BE3784613861349DB70F4AE3
e=11
d=2689CA64972BD93334A93ECA21ABB0334C78161FDA09FD7EF3AEF50CE0B319F0
EBE0ED4E979597BB36929C6247EAC2A35A2987B35D6C467CB2CB69A466EE8735
```
### 09: TI-89 Titanium OS signing key
```
n=D65139FA0ADA452B80CD35C0F9ACA3604EFE1915F0D3A4232C2C3B1FFEDDF2D7
B0A4572A12B0F86C92D7E69F9DB102B1C27A551AD128BB6AF9321784FD8EAFD1
p=F39D6276648A571322729F44E84C895EF33AF37FB70FD498588CC6B414639C1
q=E13689E94702FEAE752C61F9F793739B1C64E13AFF7B1D526A68118A517575A11
e=11
d=97486528F89A12B54BDC25F1A12E917128B35D006DC291FAB5C4DE70F02432E8
A079CD0284DC85B3CD968CF94BBC004ADBFAC18D516D9565BDFE41BBBFB940F1
```
### 0A: TI-84 Plus / TI-84 Plus Silver Edition OS signing key
```
n=EF5FEF0B0AB6E22731C17539658B2E91E53A59BF8E00FCC81D05758F26C1791C
D35AF6101B1E3543AC3E78FD8BB8F37FC8FE85601C502EABC9132CEAD4711CB1
p=94489014C63CC9E1E1ADB192DBBDD1F78F90A630DA9C86EFC4CBCA44E5B4D54D
q=19D431AF2794229620B884E3750D622D1C74F2E4569DC15486FC8D5A3BCDFE2F5
e=11
d=2A3E1B2010F318D9BD7C7E19300980B055A0E2A9554B77E7142E23CDF7C7CA13
C233A3D462FDFC968B1F9CEAF2AC2CF305147992AD9E834192ACEBB517DB9941
```
### 0101: TI-92 Plus Flash application signing key
```
n=BC747C4065E96E3B79B9BCC1A441BC3692E264CF681C9962B763C19824D84FB0
474D567CF2FE55473378A18DB2E875BCE87F0022B6B9CC1E1FD455D9FACD0461
p=C5F79C13DFAC64548AFFDAF9106D5495C7D1562E7E070B8CD11D94740DCF1F1D
q=F3B309023180214F8872DD036434BACAD21D6DBF7CD656D4F10044B85800A315
e=11
d=376D8DF4D2AE115CC972DD29E504466A676FC34C0F8FF0E0CC86C0780AD6358D
B12FD9D2F71F976C369853C14E8D2D2A35397B1E919B2E2857CC42C9A44A7CE1
```
### 0102: TI-73/Explorer Flash application signing key
```
n=FCBE6045900704759799BE325EA9B0E74C6541FDB9BEE21A55A8D2C85D370EC8
CC0F42718C1265FF8C6ED77E9B3A23DD1C96A5924CDE5F87841B5910F81FF185
p=548E4172D99E319EC8EC3B97D23AE6F3954F1648604EE17F77786D27D3CB07AB
q=2FD344E1A66F486766C39065E5ADD604DFFCA71BE4098558CA0A398525196FB8F
e=11
d=DF0254F215ABD6C21C5A7AA4EA1D41BD072C2B2B2B6C30EA0F58B9FC16036762
F370DA14BB164E291FD783F0D9A5684CFF140B02C4E923B8321D85FD8CC5B425
```
### 0103: TI-89 Flash application signing key
```
n=916BDE593CC9F21B07F72033A92D6DC6DCCE8622705E9F7B4C4235A00B0A0DEA
4F9827960CF2676C3F25F987C4BACD38A8F849A5CFCEC188BA0C8B3DFD3602ED
p=55418FD1803B562C7E0ED13B7A774F0A1B9794F626691A22C963117013C8169B
q=1B4A8C75455E0F8CDF2EE1E5E4627304521EAD549FF1DAE5944E524230E162117
e=11
d=33533F6ACA292845C69374C6F06A62FAE485204863E5293A9362A983C7A93215
BE3D58A0135A9F3739B4219F4CBEB21625ED5DE7A582D05ED3363C5A6B8865D9
```
### 0104: TI-83 Plus Flash application signing key
```
n=878E894D2CBA39ED8191EFB30A0DF25B4DC3E5E585A80D8AEDBCD73B74167CEA
5F19DAFE59BA36FFB70A33DD94571147D8A34F15A361AC5E17E49722DA3124AD
p=1CC2C1433A79A5D734F9F5F1FF1BC43F3F87D378142693CE26FEC1B5E9542E5B
q=04B697D56EA14013042B11939BBAA1ED3BAB09496DBF208785739B07947B70F797
e=11
d=7F9535EE4836CD1BC53E0EC6A00D2055EED67E0532800CBEFDDEE8B06D42576E
A1A4F4FCB2D3498B9D2BEB9673632CFD1C4D5C693C553D370C82A39E8CA1E0B1
```
### 0108: Voyage 200 Flash application signing key
```
n=B53225EE518E9EAE0239DE47B9C3BB7F1D2647A3BB95AC6BA3E2B0FB21116BE4
7FDA55F33F01B046A201800526DF4712E17F1AA7DF15447549D5A317F954077F
p=49306D3448E68EDCD746D258BBD11B5E1FF5B3A56E99C9320A9A4E1A5A936B97
q=279C8CB2099364B22B6CB7402FDA38EAD5C6018574DEB37C775577D430D7D6059
e=11
d=8A8FC2A72F4EF1D05C0E22731595AD7F5286AF40F8DBDE343207B483CDFE4370
6342BC4BECAEFE365A89C2AEBD154AE789980EFB56AA8DF5400895E905ABE241
```
### 0109: TI-89 Titanium Flash application signing key
```
n=85421ED0805812E8255F7F8565D86CE20F35C3D6676797C9D73EB7CF1FF03AAF
0180A6FBBE8DA95F246E8B08BC4E6DC93EA27BEB7BA5BA9F4485699DA6C1145D
p=1DC6E97D025CABDC33F94A63FB4E7A08093C788C68DF9F9E9431F4157165E0B
q=479A7429046095EB8C679D13A21E90268813AC8A76FBDB46B5BB51603A3A04A037
e=11
d=468C6AAA9E4CBEB722D83473CC81A30E4449A3E9FA82232E9F2134225C33E2AF
3591EA056932EA1A29C5B447B95041AF6943072271200451AF07128A83EE842D
```
### 010A: TI-84+ / TI-84 Silver Flash application signing key
```
n=8F44CF7BA748D305139C11560ED3CF4D80212FA135AA5B32B7FE142EDD3B17E1
DF3309DE483F353A60FE81417F3D0C95897CB23140A0FF83C914AA8584EBD105
p=29D8D93667BB609DDA0E1C9F43774BFC1AE31E8D1FD3A7E897E53E226EDCE8B
q=36C72E64900AF24D617F2C6FD68BAD1A4200E07789C34D2F7796811E18E126E0AF
e=11
d=6521836657F72B8B1CE6A2D355C2B072F1085DDB34F0B8D881E086B7AB38C569
B4C13DED4C576E7402F58B083BC5FE4A32116F95A61F0027C2A59152B279BD81
```
### 010F: TI-84 Plus C Silver Edition Flash application signing key
```
n=82E918E2C1AB456E7008B88C15B92510E8E4D7C8B8D1DB8108E8484131F0FC57
B3E9921F1E9FDB8DC504F572314AE3084B980BD06E6C6B81BEACD4FACD9C26A5
p=4338D2F2E7D505F826B71316E4D7B0D0C056791EBB76F03FC0D1DAEFF877B3FB
q=1F28B37DEB78A1416538E05B3DDFC3C133943ED3CC2914CC90AEC2913BE75EDDF
e=11
d=3D9ADE88D39BE47034B8CF50FB29F353406BB0D6ED8FEED34F7C5E3CCC352B73
86A83FABFFA600B45F6958C7430ACE2F35A48A18E9988E5708E8DACEA1431151
```
### Date-stamp signing key for:

- TI-73 / Explorer
- TI-83 Plus / TI-83 Silver Edition
- TI-84 Plus / TI-84 Silver Edition
- TI-84 Plus C Silver Edition
- TI-89 / TI-89 Titanium
- TI-92 Plus
- Voyage 200

```
n=A3E337A7BB1A47198D79FC393AB0A7898FFD714E1FC80314FB61CE71481B8B40
B51BFF332E7594A6AC847AE38354C74D022E0971D7DFB70D252F144105D11E15
p=3D7316BFF85539DAE08FAF040631F952EB7DB77EC824F52613ECDB523FD4745
q=2AAC2314B2992A3DAE35CB3106001D972C134E4F08FCEF53E1BCFAD84200C8C091
e=11
d=60678A266E0F751E16FC763FC82BADD872D151B57C1B4D1B66B200F75797BB3A
2122E55767292F2657EF3D7C81A9EB9D8017741540F57516405422C20BE86771
```

## .key signing files
A zip file containing all the .key files you would need for a signing utility (such as RabbitSign, Build8XU, or resign68k) is [here](/keys/).

## How to use .key files
To sign a Flash application or operating system upgrade, you need two things:

- A signing utility (such as RabbitSign, Build8XU, or resign68k
- The appropriate key file

The key file you use is determined by the key ID. Each model and key type has its own key ID as above. For example, if you want to sign a Flash application for the TI-89 Titanium, use the 0109 key.

If you are re-signing an existing Flash application or OS upgrade, you may need to check the OS header to determine which key to use.\
As an example, suppose there is an 89Ti Flash application you want to re-sign. Because the TI-89 Titanium can accept both 89-signed and 89Ti-signed Flash applications, there's no way to know which key it was signed with unless you check the OS header. If you open the 89K file with a hex editor, you'll see the application header at the beginning. Field 8010h or 8110h will contain the key ID. In this case, it would be either 0103 or 0109.

The readme for each signing utility can provide more details.
