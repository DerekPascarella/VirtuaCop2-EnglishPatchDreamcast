<h1>Virtua Cop 2</h1>
<img width="165" height="165" align="right" src="https://github.com/DerekPascarella/VirtuaCop2-EnglishPatchDreamcast/blob/main/cover.png?raw=true">Download the English translation patch (more information in the <a href="#patching-instructions">Patching Instructions</a> section):
<br><br>
<ul>
 <li><b>GDI Format (Users of ODEs or Emulators)</b><br>Download <a href="https://github.com/DerekPascarella/VirtuaCop2-EnglishPatchDreamcast/releases/download/1.0/Virtua.Cop.2.English.v1.0.dcp">Virtua Cop 2 (English v1.0).dcp</a> for use with <a href="https://github.com/DerekPascarella/UniversalDreamcastPatcher">Universal Dreamcast Patcher</a> v1.3 or newer.</li>
 <!--<br>
 <li><b>CDI Format (Users Burning to CD-R)</b><br>Download <a href="">Virtua Cop 2 (English v1.0).xdelta</a> for use with <a href="https://www.romhacking.net/utilities/704/">Delta Patcher</a> (or equivalent tools).</li>-->
</ul>
This English translation patch borrows assets and code from the English-language release of "Virtua Cop2" that came included with "<a href="https://segaretro.org/Sega_Smash_Pack_Volume_1">Sega Smash Pack: Volume 1</a>".

<h2>Table of Contents</h2>

1. [Patching Instructions](#patching-instructions)
2. [Credits](#credits)
3. [Release Changelog](#release-changelog)
4. [What's Changed](#whats-changed)
5. [Roadmap](#roadmap)

<h2>Patching Instructions</h2>
<ul>
 <li><b>GDI Format (Users of ODEs or Emulators)</b><br><img align="right" width="250" src="https://github.com/DerekPascarella/UniversalDreamcastPatcher/blob/main/screenshots/screenshot.png?raw=true">The DCP patch file shipped with this release is designed for use with <a href="https://github.com/DerekPascarella/UniversalDreamcastPatcher">Universal Dreamcast Patcher</a> v1.3 or newer.  Note that Universal Dreamcast Patcher supports both TOSEC-style GDI and Redump-style CUE disc images as source input.<br><br><ol type="1"><li>Click "Select GDI or CUE" to open the source disc image.</li><li>Click "Select Patch" to open the DCP patch file.</li><li>Click "Apply Patch" to generate the patched GDI, which will be saved in the folder from which the application is launched.</li><li>Click "Quit" to exit the application.</li></ol></li>
 <!--<br>
 <li><b>CDI Format (Users Burning to CD-R)</b><br><img align="right" width="250" src="https://i.imgur.com/r4b04e7.png">The XDelta patch file shipped with this release can be used with any number of Delta utilities, such as <a href="https://www.romhacking.net/utilities/704/">Delta Patcher</a>. Ensure the source CDI has an MD5 checksum of <tt>5EB0BD4D0ED345692080563B69689432</tt>.<br><br><ol type="1"><li>Click the settings icon (appears as a gear) and enable "Backup original file" and "Checksum validation".</li><li>Click the "Original file" browse icon and select the unmodified CDI.</li><li>Click the "XDelta patch" browse icon and select the XDelta patch.</li><li>Click "Apply patch" to generate the patched CDI in the same folder containing the original CDI.</li><li>Verify that the patched CDI has an MD5 checksum of <tt>242EEC5E8A6717B1CC0BEDA24DE5184C</tt>.</ol></li>-->
</ul>

<h2>Credits</h2>
<ul>
 <li><b>Hacking</b></li>
  <ul>
   <li>Derek Pascarella (ateam)</li>
  </ul>
</ul>

<h2>Release Changelog</h2>
<ul>
 <li>Version 1.0 (2024-05-23)</li>
 <ul>
  <li>Initial release.</li>
 </ul>
</ul>

<h2>What's Changed</h2>
<img align="right" width="267" height="200" src="https://github.com/DerekPascarella/VirtuaCop2-EnglishPatchDreamcast/blob/main/screenshot.png?raw=true">Below is a high-level list of changes implemented for this English translation patch.
<br><br>
<ul>
 <li>All VMU save/load messages appear in English.</li>
 <li>All on-screen helper/tutorial text appears in English.</li>
 <li>All stage title screens appear in English.</li>
 <li>VMU save file metadata appears in English.</li>
</ul>

<h2>Roadmap</h2>
<ul>
 <li>Implement CDI patch for users burning to CD-R. Due to the nature of Windows CE Dreamcast games, special challenges are presented when attempting to build a CDI for such a game when it utilizes CDDA, like "Virtua Cop 2".</li>
</ul>
