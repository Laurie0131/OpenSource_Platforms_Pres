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

  Copyright (c) 2018, Intel Corporation. All rights reserved.<BR>

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


---?image=/assets/images/slides2/Slide3.JPG
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
<a href='https://github.com/tianocore/tianocore.github.io/wiki/Nt32Pkg'>Nt32</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/OvmfPkg'>OVMF</a>, 
<a href='https://github.com/tianocore/edk2/tree/master/ArmVirtPkg'>ArmVirt</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MdePkg'>MdePkg</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/EDK-II-Platforms'>HW Platforms</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MinnowBoardMax'>Max/Turbot</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MinnowBoard-3'>MinnowBoard 3</a> and
<a href='https://github.com/tianocore/tianocore.github.io/wiki/Galileo'>Intel® Galileo</a>
</span>	</p>


Note:

+++?image=/assets/images/slides2/Slide4.JPG
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
<a href='https://github.com/tianocore/tianocore.github.io/wiki/Nt32Pkg'>Nt32</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/OvmfPkg'>OVMF</a>, 
<a href='https://github.com/tianocore/edk2/tree/master/ArmVirtPkg'>ArmVirt</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MdePkg'>MdePkg</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/EDK-II-Platforms'>HW Platforms</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MinnowBoardMax'>Max/Turbot</a>, 
<a href='https://github.com/tianocore/tianocore.github.io/wiki/MinnowBoard-3'>MinnowBoard 3</a> and
<a href='https://github.com/tianocore/tianocore.github.io/wiki/Galileo'>Intel® Galileo</a>
</span>	</p>


Note:

---?image=/assets/images/slides2/Slide6.JPG
<!-- .slide: data-transition="none" -->		  
@title[github tianocore]
<p align="left"><span style="font-size:1.1em" >
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[github gp-bullet-white]&nbsp;<b>GitHub</b></span>
<span style="font-size:.60em" ><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<font color="#e49436"><a href='https://github.com/tianocore'>github/tianocore</a></font></span></p>

Note:


+++?image=/assets/images/slides2/Slide7.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[github tianocore 02]
<p align="left"><span style="font-size:1.1em" >
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[github gp-bullet-white]&nbsp;<b>GitHub</b></span>
<span style="font-size:.60em" ><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<font color="#e49436"><a href='https://github.com/tianocore'>github/tianocore</a></font></span></p>

Note:


+++?image=/assets/images/slides2/Slide8.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[github tianocore 03]
<p align="left"><span style="font-size:1.1em" >
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[github gp-bullet-white]&nbsp;<b>GitHub</b></span>
<span style="font-size:.60em" ><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<font color="#e49436"><a href='https://github.com/tianocore'>github/tianocore</a></font></span></p>

Note:


+++?image=/assets/images/slides2/Slide9.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[github tianocore 04]
<p align="left"><span style="font-size:1.1em" >
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[github gp-bullet-white]&nbsp;<b>GitHub</b></span>
<span style="font-size:.60em" ><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<font color="#e49436"><a href='https://github.com/tianocore'>github/tianocore</a></font></span></p>

Note:

+++?image=/assets/images/slides2/Slide10.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[github tianocore 04]
<p align="left"><span style="font-size:1.1em" >
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
@fa[github gp-bullet-white]&nbsp;<b>GitHub</b></span>
<span style="font-size:.60em" ><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<font color="#e49436"><a href='https://github.com/tianocore'>github/tianocore</a></font></span></p>

Note:


---?image=/assets/images/slides2/Slide12.JPG
<!-- .slide: data-transition="none" -->
@title[Platforms github tianocore]
<br>
<p align="left">@fa[github gp-bullet-gold]<span style="font-size:1.0em" > <font color="#e49436">GitHub <a href='https://github.com/tianocore'>tianocore.org</a></font></span></p>

<p align="left"><span style="font-size:.70em" > <a href='https://github.com/tianocore'>edk2</a> - Platforms on edk2 <B>- CORE</b></span></p>

<p style="line-height:50%"><span style="font-size:.50em" > 
    BeagleBoardPkg <br>
	Coreboot…Pkg<br>
	DuetPkg<br>
	Nt32Pkg<br>
	OvmfPkg<br>
	QuarkPlatformPkg<br><br>
See Readme.md files
</span></p>


Note:

+++?image=/assets/images/slides2/Slide13.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[Platforms github tianocore 02]
<br>
<p align="left">@fa[github gp-bullet-gold]<span style="font-size:1.0em" > <font color="#e49436">GitHub <a href='https://github.com/tianocore'>tianocore.org</a></font></span></p>

<p align="left"><span style="font-size:.70em" > <a href='https://github.com/tianocore'>edk2</a> - Platforms on edk2 <B>- CORE</b></span></p>

<p style="line-height:50%"><span style="font-size:.50em" > 
    BeagleBoardPkg <br>
	Coreboot…Pkg<br>
	DuetPkg<br>
	Nt32Pkg<br>
	OvmfPkg<br>
	QuarkPlatformPkg<br><br>
See Readme.md files
</span></p>


Note:

+++?image=/assets/images/slides2/Slide14.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[Platforms github tianocore 03]
<br>
<p align="left">@fa[github gp-bullet-gold]<span style="font-size:1.0em" > <font color="#e49436">GitHub <a href='https://github.com/tianocore'>tianocore.org</a></font></span></p>

<p align="left"><span style="font-size:.70em" > <a href='https://github.com/tianocore'>edk2</a> - Platforms on edk2 <B>- CORE</b></span></p>

<p style="line-height:50%"><span style="font-size:.50em" > 
    BeagleBoardPkg <br>
	Coreboot…Pkg<br>
	DuetPkg<br>
	Nt32Pkg<br>
	OvmfPkg<br>
	QuarkPlatformPkg<br><br>
See Readme.md files
</span></p>


Note:

---?image=/assets/images/slides2/Slide16.JPG
@title[NT32 Emulation Dir ]
#### <p align="right"><span class="gold" >NT32 Emulation Directory Structure </span></p>
<br>
<div class="right">
    <ul>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Nt32Pkg files </p><br>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&check;&nbsp;Nt32Pkg.dsc</p>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&check;&nbsp;Nt32Pkg.dec</p>
        <p> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&check;&nbsp;Nt32Pkg.fdf</p>
    </ul>
</div>

Note:


---?image=/assets/images/slides2/Slide18.JPG
@title[Running Nt32 Emulation ]
<p align="right"><span class="gold" >Running NT32 Emulation with </span>@fa[windows gp-bullet-cyan]<span style="font-size:.90em" >&nbsp;&nbsp;Windows</span></p>
Note:
Nt32 Emulation works on top of  Windows* environment
Disadvantage - Limited (or no) access to actual hardware

---?image=/assets/images/slides2/Slide20_1.JPG
@title[Open Virtual Machine Firmware  ]
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;Open Virtual Machine Firmware (OVMF) </span></p>
<br>
- <span style="font-size:.70em" >Uses EDK II to support firmware</span>
- <span style="font-size:.70em" >OvmfPkg </span>
- <span style="font-size:.70em" >Supports UEFI:  Helps develop/<br>debug drivers & applications </span>
- <span style="font-size:.70em" >QEMU VM; emulates IA32 (x86)/<br>X64 (x86-64) based system  </span>
- <span style="font-size:.70em" >Exit condition &rarr; UEFI Shell </span>
- <span style="font-size:.70em" >Tool Chain/OS Support </span>
- <span style="font-size:.70em" >Information <a href='https://github.com/tianocore/tianocore.github.io/wiki/OVMF'>OVMF wiki </a>,<br>  Tianocore.org </span>


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
 
---?image=/assets/images/slides2/Slide20_4.JPG
@title[Open Virtual Machine Firmware  ]
#### <p align="right"><span class="gold" >OVMF BIOS w/ QEMU </span></p>
<p align="right"><span style="font-size:.70em" >Boots to UEFI Shell</span></p>

---?image=/assets/images/slides2/Slide22.JPG
@title[Intel® Quark]

#### <p align="center"><span class="gold" >&nbsp;&nbsp;Intel® Quark SoC  X1000 Platform<br> &nbsp;&nbsp;Project EDK II&nbsp;&nbsp;&nbsp;&nbsp;</span></p>
<br>

- <span style="font-size:.70em" >Uses EDK II to support firmware</span>

- <span style="font-size:.70em" >QuarkPlatformPkg </span> <br><span style="font-size:.70em" >&nbsp;&nbsp;- &nbsp;Intel® Galileo Gen2</span>
<br>
- <span style="font-size:.70em" >How to Build: <br><a href='https://github.com/tianocore/edk2/blob/master/QuarkPlatformPkg/Readme.md'>Quark Readme.md</a></span>

Note:



---?image=/assets/images/slides2/Slide24.JPG
@title[EDK II EADK]
<br>
#### <p align="left"><span class="gold" >EDK II EADK</span></p>

<span style="font-size:.80em" >EDK II Application Development <br>
Kit (EADK) includes the Standard <br>
“C” Libraries in UEFI Shell <br>
Applications 
</span>

- <span style="font-size:.70em" >Link: <a href='https://github.com/tianocore/tianocore.github.io/wiki/EDKII-EADK'>wiki EADK</a></span>
- <span style="font-size:.70em" >Github: <a href='https://github.com/tianocore/edk2/tree/master/AppPkg'> edk2/AppPkg</a></span>
- <span style="font-size:.70em" >Github: <a href='https://github.com/tianocore/edk2/tree/master/StdLib'> edk2/StdLib</a></span>

Note:

---
@title[EDK II EADK Components]
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;EDK II EADK Components</span></p>
<p style="line-height:80%"><span style="font-size:.90em" >EDK II Application Development Kit includes the Standard C Libraries in UEFI Shell Applications  </span></p>
@fa[circle gp-bullet-green]<span style="font-size:1.0em" >Components</span>
- <span style="font-size:.70em" >@color[#green]()</span>
- <span style="font-size:.70em" >@color[#yellow]()</span>
- <span style="font-size:.70em" >@color[#green]()</span>
- <span style="font-size:.70em" >@color[#yellow]()</span>
@fa[circle gp-bullet-gold]<span style="font-size:1.0em" >Packages</span> <span style="font-size:.50em" >@color[#orange](`/AppPkg`)
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; @color[#gray](`/StdLib`)</span>


Note:


---?image=/assets/images/slides2/Slide26.JPG
@title[EDK II EADK Components]
<!-- .slide: data-transition="none" -->
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;EDK II EADK Components</span></p>


Note:


+++?image=/assets/images/slides2/Slide27.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[EDK II EADK Components 02]
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;EDK II EADK Components</span></p>

Note:


+++?image=/assets/images/slides2/Slide28.JPG
<!-- .slide: data-background-transition="none" -->
<!-- .slide: data-transition="none" -->
@title[EDK II EADK Components 03]
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;EDK II EADK Components</span></p>

Note:


---

@title[EDK II EADK ANSI C]
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;EDK II EADK – Standard ANSI C Library</span></p>
<span style="font-size:.90em" >FreBSD Port &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;@color[#orange](ANSI/POSIX compliant)</span>

<table id="recTable">
	<tr>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="white">System I/O  </font></span></p></td>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="white">- `open(), read(), write(), close(), stat()`  </font></span></p></td>
	</tr>
	<tr>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="orange">Standard I/O  </font></span></p></td>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="orange">- `fopen(), printf(), gets(),`. . . </font></span></p></td>
	</tr>
	<tr>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="white">String/Char  </font></span></p></td>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="white">- `strcmp(), isascii(), atoi(),` . . .  </font></span></p></td>
	</tr>
	<tr>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="orange">Memory  </font></span></p></td>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="orange">- `malloc(), free(), realloc(),`. . . </font></span></p></td>
	</tr>

	<tr>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="white">Time/Date  </font></span></p></td>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="white">- `time(), asctime(), ctime(),` . . .  </font></span></p></td>
	</tr>
	<tr>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="orange">Math </font></span></p></td>
		<td><p style="line-height:50%"><span style="font-size:0.65em" ><font color="orange">- `sqrt(), pow(), sin(), log(),` . . .  </font></span></p></td>
	</tr>

</table>

Note:


---?image=/assets/images/slides2/Slide30.JPG

@title[EDK II EADK ANSI C]
#### <p align="right"><span class="gold" >&nbsp;&nbsp;&nbsp;EDK II EADK – Standard ANSI C Library</span></p>

Note:

---?image=/assets/images/slides2/Slide32.JPG
@title[Platforms Tianocore.org]
<br>
#### <p align="left"><span class="gold" >Platforms Tianocore.org</span></p>

<span style="font-size:.8em" >Platforms on branches - <br><a href='https://github.com/tianocore/edk2-platforms'>edk2-platforms</a> 
</span>

- <span style="font-size:.70em" ><a href='https://github.com/tianocore/edk2-platforms/tree/devel-IntelAtomProcessorE3900'>devel-IntelAtomProcessorE3900</a><br> - Leaf Hill, Up Squared (Apollo Lake) </span>
- <span style="font-size:.70em" ><a href='https://github.com/tianocore/edk2-platforms/tree/devel-MinnowBoardMax-UDK2017'> devel-MinnowBoardMax-UDK2017</a><br> - BayTrail-I  </span>
- <span style="font-size:.70em" ><a href='https://github.com/tianocore/edk2-platforms/tree/pentium-celeron-n-udk2015'> pentium-celeron-n-udk2015</a><br> - Cherry Hill(Braswell) </span>
<br>
<p style="line-height:50%"><span style="font-size:.60em" > How to build <br>- See the Readme.md files</span></p>


Note:

---?image=/assets/images/slides2/Slide34.JPG
@title[Staging Tianocore.org]
<br>
#### <p align="left"><span class="gold" >Staging Tianocore.org</span></p>

<span style="font-size:.75em" >Implementations not yet Ready for <br> EDK II Main - <a href='https://github.com/tianocore/edk2-staging'>edk2-staging</a> </span>

<span style="font-size:.75em" >Projects on branches </span>
<ul style="line-height:0.8;">
  <li><span style="font-size:.550em" >AArch64StandaloneMN (ARM)</span></li>
  <li><span style="font-size:.550em" >Customized-Secure-Boot</span></li>
  <li><span style="font-size:.550em" >HTTPS-TLS</span></li>
  <li><span style="font-size:.550em" >RICS-V</span></li>
  <li><span style="font-size:.550em" >etc. . .</span></li>
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


---?image=assets/images/gitpitch-audience.jpg
@title[Logo Slide]
<BR><BR><BR>
![Logo Slide](/assets/images/TianocoreLogo.png =10x)

---  
@title[Backup]
<br><br><br><br><br>
### <p align="center"<span class="gold"   >Backup </span></p>

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

Copyright (c) 2018, Intel Corporation. All rights reserved.
**/

```
