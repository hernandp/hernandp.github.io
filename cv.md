---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
---

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
   "http://www.w3.org/TR/html4/strict.dtd">
<html>

<head>
<meta name="generator" content="HTML Tidy for Linux (vers 6 November 2007), see www.w3.org">
<meta http-equiv="Content-Type" content="text/html;charset=utf-8" >
<title>Hernan Di Pietro CV</title>
<style type="text/css">
@media screen {
	body { width: 800px; margin:auto; }
	}

</style>

</head>

<body>

<h4>CURRICULUM VITAE</h4>
<h2>DI PIETRO HERNAN</h2>
<h3>C/C++ Systems Development and Research</h3>
<address>Contact: hernan.di.pietro (AT) gmail.com</address>
<address>Facebook: /hernandipietro</address>
<hr>

<h2>Personal Information</h2>
<ul>
<li>Birth Date: May 28, 1979</li>
<li>Address: Calle 46 N 1477 3-B (1900) Bs.As. Argentina </li>
<li>Phone: +54 221 6192867</li>
</ul>

<h2>Formal Education</h2>
<p>Licenciatura Informatica, Universidad Nacional de La Plata 2004-2010 (unfinished).</p>

<h2>Strengths</h2>
<p>Self-taught, fast learning and research ability.
Software design and prototyping. Able to drive complex one-man projects, and/or
work in development groups. Excellent predisposition to learn new technologies and platforms. 
Very interested in following development and programming style standards. 

</p>

<h2>Skills</h2>
<ul>
<li><b>Languages: </b>C, C++, Objective-C, C#, VBA, VB6, VB.NET, X86 Assembly</li>
<li><b>Scripting/Other Dialects: </b>HTML/CSS, Javascript, AWK/Perl/Sed & Unix shells, DOS/NT batch</li>
<li><b>Platforms/Products: </b>Administration of Windows NT, Linux, FreeBSD systems; Microsoft compilers and development tools (e.g WinDbg), reversing tools (IDA), UNIX/Linux GNU/GCC toolchain</li>
<li><b>Technologies/Frameworks: </b>COM, ATL, WTL, .NET Framework/ASP.NET, NT Kernel-Mode Driver (WDM), Qt, Ultimate++, native Win32 API.</li>
<li><b>Programming Techniques/Fields: </b>Native x86/X64 Debugging, API spying and hooking, data and binary/executable formats reverse engineering, 
Windows kernel internals, x86/x64 CPU architecture, low-level systems programming.</li>
<li>Additional understanding of OpenGL graphics, relational databases, SQL, XML-related technologies (XQuery/XSLT/XPATH)
 and common computer software such as text processors and drawing programs.</li>
<li><b>Spoken languages: </b>Spanish native; Very good English literacy; spoken properly.</li>
</ul>

<h2>Experience</h2>
<h3>2008-Present: C/C++ Developer at Nektra S.A</h3>

<p>Research and development of several applications and native Windows components,
including:</p>

<h4>FSLogix Product Component Development</h4>

<p>
Developed enhancements to the FSLogix virtualization product user-mode components and it's Java filtering plugin (BHO) for Internet Explorer. FSLogix is a market leader in virtualization solutions for Windows platforms.

<a href="http://www.fslogix.com">http://www.fslogix.com</a>
</p>

<h4>Outlook Autocomplete Addin</h4>
<p>
A demo addin to customize the autocomplete stream on-the-fly, for Outlook 2007 (x86). 
<a href="https://github.com/nektra/outlook-autocomplete"> 
https://github.com/nektra/outlook-autocomplete </a>
</p>

<h4>XPS Print API Hooking</h4>

<p>
With Deviare hooking engine, intercepted XPS Print API objects/interfaces to add watermarks to printed documents. This technique can be applied to printing jobs on virtual or physical printing devices.

<a href="http://blog.nektra.com/main/2015/10/20/instrumenting-the-windows-xps-print-api/">http://blog.nektra.com/main/2015/10/20/instrumenting-the-windows-xps-print-api/</a>

</p>

<h4>Riverbend Kiosk Product</h4>

<p>
Developed C++ user-mode Windows DLL components interacting with a kernel-mode driver and a kiosk application; the final application was implemented in Adobe AIR+Native Extensions. Customer: Riverbend (Seattle).
</p>
<a href="http://www.riverbend.com">http://www.riverbend.com</a>

<h4>Fabusend Product Update</h4>

<p>Updated Fabusend OSX client source code and installer utility to run under newer OS X versions (10.8/10.9). </p>
<a href="http://www.fabusend.com">http://www.fabusend.com</a>

<h4>SQLServer engine query interception</h4>

Reverse engineered SQL Server 2012 components with the objective of developing an approximation to 
interception of all server queries. Later, added the possibility of query cancel by intercepting SQL internal calls.

<a href="http://blog.nektra.com/main/2013/06/26/sql-server-interception-and-sql-injection-attacks-prevention/">
http://blog.nektra.com/main/2013/06/26/sql-server-interception-and-sql-injection-attacks-prevention</a>

<a href="http://blog.nektra.com/main/2013/09/11/instrumenting-microsoft-sql-server-to-abort-dangerous-queries/">
http://blog.nektra.com/main/2013/09/11/instrumenting-microsoft-sql-server-to-abort-dangerous-queries
</a>

<h4>Direct3D Video Capture</h4>

<p>Implemented a D3D backbuffer video capture software in C++ and Nektra Deviare hooking platform, supporting
screenshot capture, frame capture with codec selection and frame-rate counter.</p>

<a href="http://blog.nektra.com/main/2013/07/23/instrumenting-direct3d-applications-to-capture-video-and-calculate-frames-per-second">
http://blog.nektra.com/main/2013/07/23/instrumenting-direct3d-applications-to-capture-video-and-calculate-frames-per-second
</a>

<h4>Windows Live Mail Internal Contacts API</h4>

Reverse engineering of the Windows Live Mail 2009/2011 internal Contacts API.
This allowed Nektra's LiveMail API product to be able to enumerate, add, modify and delete contacts for both
the online and offline database.

Used IDA 6.0.

<h4>Windows Ribbon Framework</h4>
<p>
For the <a href="http://www.nektra.com/products/wlmailapi-windows-live-mail-api-plugin/">
Windows Live Mail API 2.0</a> product, researched the SCBin format generated by the Ribbon 
markup compiler (UICC) and reverse-engineered it to be able to modify Windows ribbon UI dynamically at runtime. </p>

<p>Used C++, EasyHook, IDA 6, Windbg.</p>

<h4>Virtualization in User and Kernel Mode</h4>
<p>Implemented a kernel-mode device driver to virtualize (trap and potentially redirect or modify) registry
entries on WIndows NT systems using the SSDT-patch mechanism. User-mode component helped to translate API
calls to make possible to implement an emulation layer to execute old software on modern Windows versions. </p>
<p>Used C/x86 Assembly, Windows Driver SDK and Debugging Tools for Windows (windbg).</p>
<p>This was applied in a in-house product and for two projects for important companies involving protection and
security utilities, and a commercial virtualization package.</p>

<h4>Panorama Toolkit</h4>
<p>Design and implementation of <a href="http://mobile.nektra.com/mobile/products/nektra-panorama-windows-mobile-development-toolkit"
>Windows Mobile 6.x GUI toolkit</a> aimed at
rich applications with fast performance. Used native Win32 API and C++.
Offers On-screen keyboard, smooth scrolling list (iPhone-like), animation control,
flicker-free UI controls as advantages over the spartan Microsoft interface.

</p>

<p>Implemented Panorama ShowCase application to show the toolkit graphic capabilities.</p>

<h4>Media and Content Distribution System (ADPROACH)</h4>
<p>
Designed and developed this media distribution system which consisted in various
interoperating modules, using the following technologies:

C++/QT4.5, COM/ATL, alpha-transparent Flash movies hosted in Windows desktop,
IPC/Multithreading, HTTP client, interoperability with JSON/XML files, autoupdating,
Internet Explorer Addin (BHO), Mozilla Extension (C++/XPCOM-based). 
<br>Total Approximate size 50,000 LOC.
</p>

<h3>2008: C++ developer at Ministerio de Seguridad Provincia Bs.As</h3>

<p>Redesigned and implemented a new database system for tracking system and technical issues using
Ultimate++ framework plus PostgreSQL 8 backend.</p>

<h3>2005-2008: Linux/UNIX SysAdmin at Ministerio de Seguridad Provincia Bs.As.</h3>

<p>General administration and network management tasks with Linux/UNIX servers,
for large user base, including installation, monitoring, scripting with Shell/AWK/Perl,
and performance optimization of proxy (Squid), mail (sendmail), firewall,
and routing servers and devices.
</p>


<h3>1998-2004: Technical Support and Developer at
Ministerio de Seguridad Provincia Bs.As</h3>

<p>Solved technical issues at different offices, both in hardware and 
software aspects. Developed and mantained a database system for tracking 
issues operating at the technical support area using Access and VBA.
</p>

<h2>Freelance Work</h2>

<h3>Linkom C Command-line parsing library</h3>
<p>Development of a single-header C library to parse command line in Windows systems, with additional COM bindings to
support other languages and programming environments.</p>
<a href="https://github.com/hernandp/linkom">https://github.com/hernandp/linkom</a>

<h3>Web Sites</h3>
<ul>
<li><a href="http://www.hotelboiano.com.ar/">Hotel Boiano</a> Developed in C# / ASP.NET, includes database application.</li>
<li>Sentidos Catering: Developed with HTML + JQuery. No server-side code. [OFFLINE]</li>
</ul>

<h3>FreeBSD Ports</h3>
<p>Ported glexcess and AC3D from Linux to build a run under FreeBSD UNIX.</p>

<h2>Articles and Publications</h2>

<h4>C/C++ and Systems Development</h4>
<ul>
<li><a href="http://www.codeproject.com/KB/macros/wlmplugin.aspx">Windows Live Messenger Plugin Development Bible</a>: techniques to 
hook, reverse engineer and research Windows applications, applied to Live Messenger 8.5. Uses COM, MSAA (Accesibility), Win32 hooking,
window subclassing, resource management and several system/SDK tools.</li>
<li>
<a href="http://www.codeproject.com/KB/winsdk/msgcrackwizard.aspx">Message Cracker Wizard for Win32 developers</a>: a tool
to use in Win32/C projects to avoid large switch..case code in handling window messages, using the windowsx.h header</li>
<li><a href="http://indiocolifax86.wordpress.com/2010/05/22/a-scheme-for-automatic-build-numbers-in-cc-projects/">
A scheme for automatic build numbers in C/C++ projects</a> Designed for Qt(QMAKE)+MSVC toolchain
</li> 
</ul>

<h4>Virtualization Products Analysis</h4>

<ul>
<li><a href="http://usuarios.multimania.es/hernandp/articles/vmware45.html">VMWare Workstation 4.5 Review</a></li>
<li>Virtual PC 2004 vs. VMWare 4 Performance Review. <a href="http://usuarios.multimania.es/hernandp/articles/vpcvs.html">Part I</a><a href="http://usuarios.multimania.es/hernandp/articles/vpcvsII.html">Part II</a></li>
</ul>
<hr>
<p>
    <a href="http://validator.w3.org/check?uri=referer"><img
      src="http://www.w3.org/Icons/valid-html401" alt="Valid HTML 4.01 Strict" height="31" width="88"></a>
  </p>

</body>
</html>


