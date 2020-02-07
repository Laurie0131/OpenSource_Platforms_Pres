---?image=assets/images/gitpitch-audience.jpg
@title[Title-UEFI Overview]
<br><br>
<span style="font-size:0.75em" >This slide deck has moved to:  https://gitpitch.com/tianocore-training/OpenSource_Platforms_Pres/master#/</span>
<br><br><br>
## <span class="gold"   >&nbsp;UEFI & EDK II Training</span>

####  &nbsp;&nbsp;Open Source UEFI Platforms
<br>
<span style="font-size:0.75em" >&nbsp;&nbsp;&nbsp;<a href='http://www.tianocore.org'>tianocore.org</a></span>
Note:
  PITCHME.md for UEFI / EDK II Training EDK II Open Source Platforms

  Copyright (c) 2020, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.



---  
@title[Lesson Objective]
<br>
### <p align="center"<span class="gold"   >Lesson Objective </span></p><br>
<br><br>
<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
 @fa[certificate gp-bullet-green]<span style="font-size:0.9em">&nbsp;&nbsp;Chart the organization of the Tianocore.org repositories </span><br><br>
 @fa[certificate gp-bullet-yellow]<span style="font-size:0.9em">&nbsp;&nbsp;Recognize the various Open Source UEFI Platforms </span><br><br>


---?image=/assets/images/slides/Slide3.JPG
<!-- .slide: data-transition="none" -->		  
@title[Web Tianocore.org]
<p align="right"><span style="font-size:1.0em" > &nbsp;&nbsp;&nbsp;<font color="#e49436"><a href='http://www.tianocore.org'>Tianocore.org</a></font></span></p>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<p style="line-height:50%"><span style="font-size:0.5em" >Platforms on tianocore.org :
<a href='https://github.com/tianocore/edk2/blob/master/EmulatorPkg/Readme.md'>Emulator</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/OvmfPkg'>OVMF</a>, 
<a href='https://github.com/tianocore/edk2/tree/master/ArmVirtPkg'>ArmVirt</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MdePkg'>MdePkg</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/EDK-II-Platforms'>HW Platforms</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MinnowBoardMax'>Max/Turbot</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/IntelAtomProcessorE3900'>Up<sup>2</sup></a> and
<a href='https://github.com/tianocore/tianocore.github.io/wiki/Galileo'>Intel® Galileo</a>
</span>	</p>


Note:

+++?image=/assets/images/slides/Slide4.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[Web Tianocore.org 02]
<p align="right"><span style="font-size:1.0em" > &nbsp;&nbsp;&nbsp;<font color="#e49436"><a href='http://www.tianocore.org'>Tianocore.org</a></font></span></p>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<p style="line-height:50%"><span style="font-size:0.5em" >Platforms on tianocore.org :
<a href='https://github.com/tianocore/edk2/blob/master/EmulatorPkg/Readme.md'>Emulator</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/OvmfPkg'>OVMF</a>, 
<a href='https://github.com/tianocore/edk2/tree/master/ArmVirtPkg'>ArmVirt</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MdePkg'>MdePkg</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/EDK-II-Platforms'>HW Platforms</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MinnowBoardMax'>Max/Turbot</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/IntelAtomProcessorE3900'>Up<sup>2</sup></a> and
<a href='https://github.com/tianocore/tianocore.github.io/wiki/Galileo'>Intel® Galileo</a>
</span>	</p>


Note:

---?image=/assets/images/slides/Slide5.JPG
@title[github tianocore]
<p align="left"><span style="font-size:1.1em" >
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[github gp-bullet-white]&nbsp;<b>GitHub</b></span>
<span style="font-size:.60em" ><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<font color="#e49436"><a href='https://github.com/tianocore'>github/tianocore</a></font></span></p>

@snap[north-west span-60 ]
<br>
<br>
<br>
<br>
<ul style="list-style-type:disc; line-height:0.7;">
  <li class="fragment"><span style="font-size:0.7em;" >Main development -<br>    @color[yellow](edk2)</span></li>
  <li class="fragment"><span style="font-size:0.7em;" >Online Infor & Help (Wiki) -<br>   @color[yellow](tianocore.github.io)</span></li>
  <li class="fragment"><span style="font-size:0.7em;" >Other Platforms -<br>    @color[yellow](edk2-platforms )</span></li>
  <li class="fragment"><span style="font-size:0.7em;" >"C" library for Apps -<br>    @color[yellow](edk2-libc)</span><br><br></li>
  <li class="fragment"><span style="font-size:0.7em;" >To Download use   "@color[#A8ff60](git clone)" then<br> "@color[#A8ff60](git checkout)" </span></li>
</ul>
@snapend

Note:


---?image=/assets/images/slides/Slide6.JPG
@title[Platforms github tianocore]
<br>
<p align="left">@fa[github gp-bullet-gold]<span style="font-size:1.0em" > <font color="#e49436">GitHub <a href='https://github.com/tianocore'>tianocore.org</a></font></span></p>

<p align="left"><span style="font-size:.70em" > <a href='https://github.com/tianocore'>edk2</a> - Platforms on edk2 <B>- CORE</b></span></p>

<p style="line-height:50%"><span style="font-size:.60em" > 
    &nbsp;&nbsp;EmulatorPkg <br>
	&nbsp;&nbsp;OvmfPkg<br>
<br>
<br>
See Readme.md files
</span></p>


Note:


---?image=/assets/images/slides/Slide7.JPG
@title[Emulation Dir ]
<p align="right"><span class="gold" >@size[1.1em](<b>Emulation Directory Structure </b>)</span>
<span style="font-size:0.75em;" >  </span></p>
<br>
<div class="right">
    <ul style="list-style-type:none; line-height:0.8;">
        <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EmulatorPkg files </p><br>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&check;&nbsp;EmulatorPkg.dsc</p>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&check;&nbsp;EmulatorPkg.dec</p>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&check;&nbsp;EmulatorPkg.fdf</p>
    </ul>
</div>

Note:


---?image=/assets/images/slides/Slide8.JPG
@title[Running  Emulation ]
<p align="right"><span class="gold" >Running Emulator with </span>@fa[windows gp-bullet-cyan]<span style="font-size:.90em" >&nbsp;&nbsp;Windows</span></p>
Note:
Emulation works on top of  Windows* environment
Disadvantage - Limited (or no) access to actual hardware

---?image=/assets/images/slides/Slide9.JPG
@title[Open Virtual Machine Firmware  ]
<p align="right"><span class="gold" >@size[1.1em](<b>&nbsp;&nbsp;&nbsp;Open Virtual Machine Firmware &lpar;OVMF&rpar;</b>) </span></p>
<br>
@snap[north-west span-60 ]
<br>
<br>
<br>
<br>
<ul style="list-style-type:disc; line-height:0.7;">
  <li><span style="font-size:.70em" >Uses EDK II to support firmware in the OvmfPkg platform package</span></li>
  <li><span style="font-size:.70em" >Supports UEFI:  Helps develop/ debug drivers & applications </span></li>
  <li><span style="font-size:.70em" >QEMU VM; emulates IA32 (x86)/ X64 (x86-64) based system  </span></li>
  <li><span style="font-size:.70em" >Exit condition &rarr; UEFI Shell </span></li>
  <li><span style="font-size:.70em" >Tool Chain/OS Support </span></li>
  <li><span style="font-size:.70em" >Information <a href='https://github.com/tianocore/tianocore.github.io/wiki/OVMF'>OVMF wiki </a>,<br>  Tianocore.org </span></li>
</ul>
@snapend

Note:
- Support firmware for VM using EDK II
- EDK II Package Directory – OvmfPkg
- Enable support for UEFI within VM to help develop/debug UEFI drivers & applications
- QEMU1 VM supported to emulate IA32 (x86) or X64 (x86-64) based system  
- OVMF is a sample platform for how VM firmware can be built with EDK II to boot EFI/UEFI Shell & OS in the VM

- 1 QEMU - Open source processor emulator virtual machine using dynamic translation to achieve good emulation speed 


- Tool chain support
- Microsoft Visual Studio*, WINDDK*, Intel ‘C’ Compiler (ICC), GCC Linux and GCC Windows (under CYGWIN*)
- OVMF also requires an ASL compiler to be installed on the system. Intel ASL is available from http://www.acpica.org. 
- More Information available at TianoCore.org
 
---?image=/assets/images/slides/Slide10.JPG
@title[Open Virtual Machine Firmware  ]
<p align="right"><span class="gold" >@size[1.1em](<b>OVMF BIOS w/ QEMU  </b>)</span><br>
<span style="font-size:0.75em;" >Boots to UEFI Shell  </span></p>





---?image=/assets/images/slides/Slide11.JPG
@title[EDK II EADK]
<br>
#### <p align="left"><span class="gold" >EDK II EADK</span></p>

<span style="font-size:.80em" >EDK II Application Development <br>
Kit (EADK) includes the Standard <br>
“C” Libraries in UEFI Shell <br>
Applications 
</span>

- <span style="font-size:.70em" >Link: <a href='https://github.com/tianocore/tianocore.github.io/wiki/EDKII-EADK'>wiki EADK</a></span>
- <span style="font-size:.70em" >Github: <a href='https://github.com/tianocore/edk2-libc'> edk2-libc</a></span>


Note:

---
@title[EDK II EADK Components]
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;EDK II EADK Components</span></p>
<p style="line-height:80%"><span style="font-size:.85em" >EDK II Application Development Kit includes the Standard C Libraries in UEFI Shell Applications  </span></p>
@fa[circle gp-bullet-green]<span style="font-size:1.0em" >&nbsp;&nbsp;&nbsp;&nbsp;Components</span>
- <span style="font-size:.70em" >@color[#87E2A9](Utilities &lpar;Python 2.7.2, & 2.7.10 etc.&rpar; )</span>
- <span style="font-size:.70em" >@color[yellow](C Library)</span>
- <span style="font-size:.70em" >@color[#87E2A9](BSD Socket Library)</span>
- <span style="font-size:.70em" >@color[yellow](Network Socket Library – Ipv4 / Ipv6)</span>
<br><br>
@fa[circle gp-bullet-gold]<span style="font-size:1.0em" >&nbsp;&nbsp;&nbsp;&nbsp;Packages&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span> <span style="font-size:.650em" >@color[#FFC000](<font face="Consolas">/AppPkg</font>)
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; @color[#FFFF99](<font face="Consolas">/StdLib</font>)</span>


Note:


---

@title[EDK II EADK ANSI C]
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;EDK II EADK – Standard ANSI C Library</span></p>
<span style="font-size:.90em" ><b>FreBSD Port </b>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;@color[#FFFF99](<b>ANSI/POSIX compliant</b>)</span>

<table id="recTable">
	<tr>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="white"><b>System I/O</b>  </font></span></p></td>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="white">- <font face="Consolas">open(), read(), write(), close(), stat()</font>  </font></span></p></td>
	</tr>
	<tr>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="orange"><b>Standard I/O</b>  </font></span></p></td>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="orange">- <font face="Consolas">fopen(), printf(), gets(), getchar(),</font>. . . </font></span></p></td>
	</tr>
	<tr>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="white"><b>String/Char</b>  </font></span></p></td>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="white">- <font face="Consolas">strcmp(), isascii(), atoi(),</font> . . .  </font></span></p></td>
	</tr>
	<tr>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="orange"><b>Memory</b>  </font></span></p></td>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="orange">- <font face="Consolas">malloc(), free(), realloc(),</font>. . . </font></span></p></td>
	</tr>

	<tr>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="white"><b>Time/Date</b>  </font></span></p></td>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="white">- <font face="Consolas">time(), asctime(), ctime(),</font> . . .  </font></span></p></td>
	</tr>
	<tr>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="orange"><b>Math</b> </font></span></p></td>
		<td><p style="line-height:10%"><span style="font-size:0.65em" ><font color="orange">- <font face="Consolas">sqrt(), pow(), sin(), log(),</font> . . .  </font></span></p></td>
	</tr>

</table>

Note:


---?image=/assets/images/slides/Slide14.JPG
@title[Platforms Tianocore.org]
<p align="left"><span class="gold" ><br>@size[1.1em](<b>Platforms Tianocore.org  </b>)</span> <span style="font-size:0.75em;" >  </span></p>

<span style="font-size:.8em" >Platforms on branches - <br><a href='https://github.com/tianocore/edk2-platforms'>edk2-platforms</a> 
</span>
<ul style="list-style-type:disc; line-height:0.7;">
 <li><span style="font-size:.70em" ><a href='https://github.com/tianocore/edk2-platforms/tree/devel-IntelAtomProcessorE3900'>devel-IntelAtomProcessorE3900</a><br> - Leaf Hill, Up Squared (Apollo Lake) </span> </li>
 <li><span style="font-size:.70em" ><a href='https://github.com/tianocore/edk2-platforms/blob/master/Platform/Intel/Vlv2TbltDevicePkg/Readme.md'> MinnowBoardMax</a><br> - BayTrail-I  </span></li>
 <li><span style="font-size:.70em" ><a href='https://github.com/tianocore/edk2-platforms/blob/master/Platform/Intel/Readme.md'> MinPlatformPkg</a> - (W/ FSP)<span style="font-size:.70em" ><br>&nbsp;&nbsp;&nbsp; - 
  KabylakeOpenBoardPkg <br>&nbsp;&nbsp;&nbsp; - 
  WhiskeylakeOpenBoardPkg</span>
</span></li>
<br>
<p style="line-height:50%"><span style="font-size:.60em" > How to build <br>- See the Readme.md files</span></p>


Note:

---?image=/assets/images/slides/Slide15.JPG
@title[Slim Bootloader SBL]
<p align="right"><span class="gold" ><br>@size[1.1em](<b>Slim BootLoader &lpar;SBL&rpar; Project &nbsp;&nbsp;&nbsp;</b>)</span> <span style="font-size:0.75em;" >  </span></p>

<span style="font-size:.8em" >Fast & Secure Open source boot solution for IoT Use Cases<br>
@size[.8em](Github:  https://github.com/slimbootloader )
</span>

<span style="font-size:.70em" >Supported Hardware</span>
<ul style="list-style-type:none; line-height:0.6;">
  <li><span style="font-size:0.6em;" >QEMU    </span></li>
  <li><span style="font-size:0.6em;" >UP2 Board    </span></li>
  <li><span style="font-size:0.6em;" >Apollo Lake CRB    </span></li>
  <li><span style="font-size:0.6em;" >Whisky Lake   Lake CRB   </span></li>
  <li><span style="font-size:0.6em;" >Coffee Lake Refresh  Lake CRB   </span></li>
  <li><span style="font-size:0.6em;" >UP Xtreme Board   </span></li>
</ul>
<br>
<span style="font-size:0.6em;" >Documentation: <a href="https://slimbootloader.github.io/index.html"> Slim Bootloader Project</a>


---?image=/assets/images/slides/Slide16.JPG
@title[Intel® FSP Repository]
<p align="left"><span class="gold" ><br>@size[1.1em](<b>Intel® FSP Repository&nbsp;&nbsp;&nbsp;</b>)</span> <span style="font-size:0.75em;" >  </span></p>

@snap[north-west span-60 ]
<br>
<br>
<br>
<br>
<p style="line-height:65%" align="left" ><span style="font-size:0.7em;" >
Intel Developer Zone <a href="https://www.intel.com/content/www/us/en/intelligent-systems/intel-firmware-support-package/intel-fsp-overview.html">Overview</a><br><br>
Repository of Intel FSP binaries posted by Intel<br>
Includes documentation on how to integrate with various platforms<br>
https://github.com/IntelFsp/FSP <br><br>
Wiki: https://github.com/IntelFsp/FSP/wiki <br>
  &nbsp; &nbsp;&nbsp;- current specs
</span></p>
@snapend

---?image=/assets/images/slides/Slide17.JPG
@title[Staging Tianocore.org]
<br>
#### <p align="left"><span class="gold" >Staging Tianocore.org</span></p>

<span style="font-size:.75em" >Implementations not yet Ready for <br> EDK II Main - <a href='https://github.com/tianocore/edk2-staging'>edk2-staging</a> </span>

<span style="font-size:.75em" >Projects on branches </span>
<ul style="line-height:0.7;">
  <li><span style="font-size:.550em" >Host-based FW analysis (HBFA)  </span></li>
  <li><span style="font-size:.550em" >edk2-host-test </span></li>
  <li><span style="font-size:.550em" >FceFmmt (FW Utils) </span></li>
  <li><span style="font-size:.550em" >UEFI_PCI_ENHANCE-2 </span></li>
  <li><span style="font-size:.550em" >EdkRepo </span></li>
  <li><span style="font-size:.550em" >Cpu/6-level </span></li>
  <li><span style="font-size:.550em" >HTTPS-TLS </span></li>
  <li><span style="font-size:.550em" >RICS-V </span></li>
  <li><span style="font-size:.550em" > . . .</span></li>
</ul>
<br>
<span style="font-size:.60em" > See the Readme.md files</span>


Note:


<!---  Summary Same as Objectives
-->

---  
@title[Lesson Summary]
 
<br>
### <p align="center"<span class="gold"   >Summary</span></p><br>
<br><br>
<!---  Add bullets using https://fontawesome.com/cheatsheet certificate
-->
 @fa[certificate gp-bullet-green]<span style="font-size:0.9em">&nbsp;&nbsp;Chart the organization of the Tianocore.org repositories </span><br><br>
 @fa[certificate gp-bullet-yellow]<span style="font-size:0.9em">&nbsp;&nbsp;Recognize the various Open Source UEFI Platforms </span><br><br>
 

<!---  END OF SLIDES
-->

---?image=assets/images/gitpitch-audience.jpg
@title[Questions]
<BR>
![Questions](/assets/images/questions.JPG =10x) 


---
@title[return to main]
<p align="center"><span class="gold"   >@size[1.2em](<b>Return to Main Training Page</b>)</span></p>
<br>
<br>
<br>
<br>
<br>
<p align="center"><span style="font-size:0.9em">Return to Training Table of contents for next presentation <a href="https://github.com/tianocore-training/Tianocore_Training_Contents/wiki#schedule--outline">link</a></span></p>

@snap[north span-30 ]
<br>
<br>
<br>
<a href="https://github.com/tianocore-training/Tianocore_Training_Contents/wiki#schedule--outline">
![trainingLogo](/assets/images/returnTrainingLogo.png)</a>
@snapend


---?image=assets/images/gitpitch-audience.jpg
@title[Logo Slide]
<BR><BR><BR>
![Logo Slide](/assets/images/TianocoreLogo.png =10x)

---
@title[Acknowledgements]
<br>
#### <p align="center"<span class="gold"   >Acknowledgements</span></p>

```c++
/**
Redistribution and use in source (original document form) and 'compiled' forms (converted
to PDF, epub, HTML and other formats) with or without modification, are permitted provided
that the following conditions are met:

Redistributions of source code (original document form) must retain the above copyright 
notice, this list of conditions and the following disclaimer as the first lines of this 
file unmodified.

Redistributions in compiled form (transformed to other DTDs, converted to PDF, epub, HTML
and other formats) must reproduce the above copyright notice, this list of conditions and 
the following disclaimer in the documentation and/or other materials provided with the 
distribution.

THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR IMPLIED 
WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND 
FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL TIANOCORE PROJECT BE 
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES 
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, 
DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, 
WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) 
ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF ADVISED OF THE POSSIBILITY 
OF SUCH DAMAGE.

Copyright (c) 2020, Intel Corporation. All rights reserved.
**/

```

---  
@title[Backup]
<br><br><br><br><br>
### <p align="center"<span class="gold"   >Backup </span></p>


---?image=/assets/images/slides/Slide23.JPG
@title[Intel® Quark]

#### <p align="center"><span class="gold" >&nbsp;&nbsp;Intel® Quark SoC  X1000 Platform<br> &nbsp;&nbsp;Project EDK II&nbsp;&nbsp;&nbsp;&nbsp;</span></p>
<br>

- <span style="font-size:.70em" >Uses EDK II to support firmware</span>

- <span style="font-size:.70em" >QuarkPlatformPkg </span> <br><span style="font-size:.70em" >&nbsp;&nbsp;- &nbsp;Intel® Galileo Gen2</span>
<br>
- <span style="font-size:.70em" >How to Build: <br><a href='https://github.com/tianocore/edk2/blob/master/QuarkPlatformPkg/Readme.md'>Quark Readme.md</a></span>

Note:

