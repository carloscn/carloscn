<!--
**carloscn/carloscn** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
** img.shields.io

<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>
* RISC-V: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=RISC-V&color=blue"></a> 
* ARMv8: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=ARMv8&color=blue"></a> 
* ARMv7: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=ARMv7&color=blue"></a> 
* Linux: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=Linux&color=orange"></a>
* ELF: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=ELF&color=green"></a>
* Kernel: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=Kernel&color=red"></a>
* Compiler: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=Compiler&color=lightgrey"></a>
* OPTEE: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=OPTEE&color=green"></a>
* Security: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=Security&color=DC143C"></a>
* Embedded: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=Embedded&color=1dcc66"></a>
* RUST: <a><img height="16" src="https://img.shields.io/static/v1?label=blog&message=RUST&color=green"></a>
---
-->

Note，This account's content is solely for personal learning records, sourced from AI, the internet, books, and official documents, and may not be reproduced, distributed, or plagiarized without authorization; for any copyright or legal issues, please contact me via email, and I will promptly address and remove the relevant content. Thank you for your cooperation.

#### Updating：
* [[IMX6] High Assurance Boot (HAB) for dummies](https://github.com/carloscn/blog/issues/232) [2024-07-26]
* [[Yocto] 03_Creating a Custom Yocto Layer ](https://github.com/carloscn/blog/issues/227) [2024-06-10]
* [[Yocto] 02_Builds without an Internet Connection](https://github.com/carloscn/blog/issues/226) [2024-06-10]
* [[Yocto] 01_Building Yocto Images using a Docker Container ](https://github.com/carloscn/blog/issues/225) [2024-06-10]
* [[Linux] 简析Linux镜像生成过程](https://github.com/carloscn/blog/issues/209) [2024-03-01]
* [[armv8-m] TrustZone Tech Description](https://github.com/carloscn/blog/issues/199) [2023-11-17]
* [[armv8-m] TrustZone Tech Overview](https://github.com/carloscn/blog/issues/197) [2023-11-07]
* [[IMX6] Defining A U-Boot Command](https://carloss-organization-4.gitbook.io/tech/ecus/imx6-8_documents/imx6-defining-a-u-boot-command) [2023-09-14]
* [wip] [02_SYS_RUST_文件IO](https://github.com/carloscn/blog/issues/190) [2023-05-24]
* [8.0_Security_pkcs7(CMS)_embedded](https://github.com/carloscn/blog/issues/186) [2023-05-17]
* [02_ARMv7-M_编程模型与模式](https://github.com/carloscn/blog/issues/123) [2023-05-10]
* [10_ELF文件_ARM的镜像文件(.bin/.hex/.s19)](https://github.com/carloscn/blog/issues/184) [2023-04-28]
* **[参考全部博客： https://github.com/carloscn/blog](https://github.com/carloscn/blog/blob/main/README.md)**
-----------------

  
<!--
<img width="200" alt="image" src="https://user-images.githubusercontent.com/16836611/163514037-fb7cc845-c7d2-41ae-acbc-8a202f2f9016.png">
</div>

<img src="https://komarev.com/ghpvc/?username=carloscn&style=flat-square&color=blue" alt=""/>
<div id="header" align="left">
<a><img alt="open-source" src="https://img.shields.io/badge/git-%23F05033.svg?logo=git&logoColor=white&style=flat"></a>
<a><img alt="open-source" src="https://img.shields.io/badge/github-%23121011.svg?logo=github&logoColor=white&style=flat"></a>
<a><a href="https://t.me/zzzzzmle"><img alt="open-source" src="https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white&style=flat"></a>
<a href="https://github.com/carloscn/blog"><img alt="open-source" src="https://img.shields.io/website-up-down-green-red/https/lbesson.bitbucket.io.svg"></a>
<a href="https://github.com/wifialan/ARMv8-A_Reference_Manual"><img alt="open-source" src="https://img.shields.io/website-up-down-green-red/http/myfakewebsitethatshouldnotexist.at.least.i.hope.svg"></a>
</div>

-----------------

#### 仓库入口：
* [参考文献入口 ：https://github.com/carloscn/doclib](https://github.com/carloscn/doclib)
* [个人博客入口 ：https://github.com/carloscn/blog](https://github.com/carloscn/blog)
* [架构集训入口 ：https://github.com/carloscn/armv8-train](https://github.com/carloscn/armv8-train)
* [数据结构入口 ：https://github.com/carloscn/structstudy](https://github.com/carloscn/structstudy)
* [Linux的内核 ：https://github.com/carloscn/raspi-linux](https://github.com/carloscn/raspi-linux)
* [uboot的入口 ：https://github.com/carloscn/raspi-uboot](https://github.com/carloscn/raspi-uboot)
* [安全套件源代 ：https://github.com/carloscn/raspi-aft](https://github.com/carloscn/raspi-aft)
* [安全系统源代 ：https://github.com/carloscn/user-optee-os](https://github.com/carloscn/user-optee-os)
* [安全应用实例 ：https://github.com/carloscn/optee_examples](https://github.com/carloscn/optee_examples)
* [配置文件综合 ：https://github.com/carloscn/config](https://github.com/carloscn/config)

-->

