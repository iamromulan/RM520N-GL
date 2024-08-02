---


---

<h1 id="rm520n-gl">RM520N-GL</h1>
<p>The Quectel RM520N-GL is 5G IoT module specially optimized for IoT/eMBB applications.</p>
<p>You will find Tools, Docs, and Firmware for it here, as well as a .exe (QuecDeploy) that installs everything for windows.</p>
<h2 id="quecdeploy">QuecDeploy:</h2>
<p><img src="https://github.com/user-attachments/assets/dc351b48-3682-4181-b33c-843136221d1c" alt="Screenshot 2024-07-31 130755"></p>
<p><strong><a href="https://github.com/iamromulan/rm520n-gl/releases">QuecDeploy DOWNLOAD</a></strong></p>
<p><strong>Note</strong></p>
<p>Unfortunately due to GitHub’s 100MB per file limit, Qflash and the firmware directory couldn’t be uploaded to the repository. It is however included in the latest <a href="https://github.com/iamromulan/rm520n-gl/releases">QuecDeploy</a> and by using their download links listed here.</p>
<p><strong>What this does</strong></p>
<p>It is a menu style Powershell script that will let you install Qflash and Qnav. adb abd fastboot are now automatically included with Qflash! It will also let you download firmware and view PDF for several modems. It heavily relies on megatools, a cli for downloading files from <a href="http://mega.nz">mega.nz</a><br>
All files installed/downloaded will go to C:\Quectel\</p>
<h1 id="table-of-contents">Table of Contents</h1>
<ul>
<li><a href="#quecdeploy">QuecDeploy</a></li>
<li><a href="#toolz">Toolz</a></li>
<li><a href="#firmware">Firmware</a></li>
<li><a href="#firmware-update-instructions">Firmware update instructions</a></li>
<li><a href="#how-to-use-qnavigator-to-send-at-commands">How to use Qnavigator to send AT commands</a></li>
<li><a href="#at-commands">AT commands</a></li>
<li><a href="#other-docs">Other Docs</a></li>
<li><a href="#description-of-antenna-connection">Description of antenna connection</a></li>
<li><a href="#specification">Specification</a></li>
</ul>
<h2 id="toolz">Toolz:</h2>

   Windows | View
<p><a href="https://mega.nz/file/zJd1CYbL#OuzK4SaghBZuQ_RLstw--I38179sZM7TkkktL2IIsm4">Quectel Windows USB Driver(Q) NDIS V2.7</a> (Recommended)</p>
<p><a href="https://mega.nz/file/7IEjESSB#5jj1v7F3WWVfy6cFzdvfCHxaoTENMgBW2v_94NtgpoA">Quectel Windows USB Driver(Q) ECM V1.0</a></p>
<p><a href="https://mega.nz/file/XRc0nZSQ#9hPjcrasgOQ9ej_tWQhvC6_NQC3iZMIdu0t17sz7AHE">Quectel Windows USB Driver(Q) MBIM V1.3</a></p>
<p><a href="https://mega.nz/file/vRN1ERaL#0zp9di4iFEaamkczsmw_Xaxr3fcWS7in9ODXZ73l8Lg">Quectel Windows USB Driver(Q) RNDIS V1.1</a></p>
<p><a href="https://mega.nz/file/bdUWiKSQ#7RPymUcm7Rgdjf9mRsWjuf9zXia5qxV7NZWMLruvb5A">QFlash V7.1 EN</a></p>
<p><a href="https://mega.nz/file/vdFH0LrB#lnrp3G4HEmgcwGTViQzpFm2iNxBYe5k_EkdGRvglJdA">QFlash V6.9 EN</a></p>
<p><a href="https://mega.nz/file/SB9C3JqR#1qrUfTIzL0n-Wwpsnz8MIDjH4rifp5V8Tshax5Te7Ho">QFlash_PCIE_V1.0</a></p>
<p><a href="https://mega.nz/file/2RMFAbCT#zq3r9TmEF8REXK6PkuAXFiuyPI5Tw4oqYnHGEiSmoD4">Qnavigator V1.6.10</a></p>
<p><a href="https://mega.nz/file/CVcFgQLI#b1AfPvmIq9N_MHQBi8MkZFphADdW3Af7Hc8kFH0LiW8">QCOM V1.8.2</a></p>


   Linux | View
<p><a href="https://mega.nz/file/HNdEHI5I#tbOhCRS5vNZ-J9eEVVD_ip-YrU2cIYeD9bLO0j24gz4">QFirehose V1.4.17</a></p>
<p><a href="https://mega.nz/file/fE8T1bRZ#U3WfgbiJZpui4rQ9zBuQnGuwLJu4FaQJsWYTvvPnHhI">Quectel Linux PCIE MHI Driver V1.3.3</a></p>
<p><a href="https://mega.nz/file/uBk3GDRA#3iILSy8HrFaC9Ug1xV1qmOlsz_UTfM6WD4_0lgFAZ30">Quectel Linux Android SPRD PCIE Driver V1.1.1</a></p>
<p><a href="https://mega.nz/file/LcsVzLjT#jBPdvFz00TBcNef3uQ1KxxnftkVl4qchZ_aTLQuY-2E">Quectel Linux Android QMI WWAN_Driver V1.2.1</a></p>
<p><a href="https://mega.nz/file/TZczXQxa#pEjC2KJoDJISxdgGyNyqOJ3Wf8eNViTdUa5snNL0G8c">Quectel Linux Android GobiNet Driver V1.6.3</a></p>

<h2 id="firmware">Firmware:</h2>

   Stock | View

<table>
<thead>
<tr>
<th>Date</th>
<th>Version</th>
<th>Link</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>2024-04-03</code></td>
<td><em>RM520NGLAAR01A08M4G</em></td>
<td><a href="https://mega.nz/file/ucclVCLT#chq0HzixUTPoNpG9G2duv5Xhj2JChz2ALa6QJpZJ3kY">Download</a></td>
</tr>
<tr>
<td><code>2024-02-01</code></td>
<td><em>RM520NGLAAR01A08M4G</em></td>
<td><a href="https://mega.nz/file/2NdzWKJJ#n4EbQkh17Pwfkfxzz-ZbjN5MFK6fJVRgLx6Chh43QRk">Download</a></td>
</tr>
<tr>
<td><code>2023-07-20</code></td>
<td><em>RM520NGLAAR01A08M4G</em></td>
<td><a href="https://mega.nz/file/SYMh0YwI#xLaLs8qeOMOmic1wHLROrZedZ3USmNzGrSkFddOiAzk">Download</a></td>
</tr>
<tr>
<td><code>2023-07-12</code></td>
<td><em>RM520NGLAAR01A07M4G</em></td>
<td><a href="https://mega.nz/file/LJd2yYxQ#lPdFog6G_5RFdKCltnpGKrblvEFOiW-Ctumz72LNMns">Download</a></td>
</tr>
<tr>
<td><code>2023-03-27</code></td>
<td><em>RM520NGLAAR01A07M4G</em></td>
<td><a href="https://mega.nz/file/bFdVlJAB#-vDBJ4ywc4aM68ECG2Sef2i-5VuCHk-is05Y5HRyUJM">Download</a></td>
</tr>
<tr>
<td><code>2023-01-20</code></td>
<td><em>RM520NGLAAR01A06M4G</em></td>
<td><a href="https://mega.nz/file/TJ8m1QoB#V7Gt1KHpbQIw8J66wo07PMqamGjQK1uXfu1etbjENvs">Download</a></td>
</tr>
<tr>
<td><code>2022-12-26</code></td>
<td><em>RM520NGLAAR01A06M4G</em></td>
<td><a href="https://mega.nz/file/7dVlmaRL#oGc7xp0BwjweSqACmxWHjlAZwVuBNtNa-v1z6ob43oQ">Download</a></td>
</tr>
</tbody>
</table>

   Certified | View

<table>
<thead>
<tr>
<th>Date</th>
<th>Version</th>
<th>Link</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>2024-03-28</code></td>
<td><em>RM520NGLAAR03A03M4G</em></td>
<td><a href="https://mega.nz/file/PcV0DDzA#aeQkP3V6WnzvO5BUPTw0Vm1Zdb5n9AA0Zb3ebSsHYlM">Download</a></td>
</tr>
<tr>
<td><code>2024-01-02</code></td>
<td><em>RM520NGLAAR03A01M4G</em></td>
<td><a href="https://mega.nz/file/fdE1iY4T#4q_gz03GbQZ6mR3-SdQVptelwNPrklVSPWa1VcH9pVo">Download</a></td>
</tr>
<tr>
<td><code>2023-11-26</code></td>
<td><em>RM520NGLAAR03A02M4GA</em></td>
<td><a href="https://mega.nz/file/uZsCkCyL#XxVYTEuPJJOxz1WrSHmkdTbNMvziU9LIDTPIbTh2rkg">Download</a></td>
</tr>
<tr>
<td><code>2023-07-25</code></td>
<td><em>RM520NGLAAR03A03M4G</em></td>
<td><a href="https://mega.nz/file/TJFSiBqJ#DVPT-QX60A7pSFVXxxukMDSXTZswTl39XlTEH_NWWpM">Download</a></td>
</tr>
<tr>
<td><code>2023-05-12</code></td>
<td><em>RM520NGLAAR03A01M4G</em></td>
<td><a href="https://mega.nz/file/yd8ATTCb#ZIbLL2GWnTG_j8RzMaHV4fN5P6v4zBKc1MLfGX5BXH0">Download</a></td>
</tr>
</tbody>
</table>

   Custom | View

<table>
<thead>
<tr>
<th>Date</th>
<th>Version</th>
<th>Link</th>
<th>Full Project</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>R01.00.04_2023-11-07</code></td>
<td><em>Arixolink RM520NGLAAR03A01M4G OCPU_BETA_20230419C</em></td>
<td><a href="https://mega.nz/file/fZcUjCLK#LOav6ZB9ZK15Vm8Nph1s6LpbmHTZNn0f8MsjvFcby1c">Download</a></td>
<td><a href="https://mega.nz/file/mRMVjSxB#EzL7rK5hy2VGXdj31R3jAWFDkncnvwxviaqVRzPcTY0">Download</a></td>
</tr>
</tbody>
</table>
<h2 id="firmware-update-instructions">Firmware update instructions:</h2>

   Windows | View
<p>Step 1.</p>
<blockquote>
<p>Install modem drivers <a href="https://mega.nz/file/GVMS1D7K#ogA1oLOwhkRlLWDDhisG9p0k1H_jhcAJOesHHV-XKUg">Quectel Windows USB Driver(Q) NDIS V2.6.0</a>  on your system. The <a href="#quecdeploy">QuecDeploy</a> tool will help you do this as well. If you don’t already have QFlash install it from the <a href="#quecdeploy">QuecDeploy</a> tool or the respective link in <a href="#toolz">Toolz</a></p>
</blockquote>
<p>Step 2.</p>
<blockquote>
<p>Connect modem to your computer, by usb</p>
</blockquote>
<p>Step 3.</p>
<blockquote>
<p>Go to device manager and check if the new COM ports are visible in the system. Restart your computer if the new COM ports are not visible.</p>
</blockquote>
<p><img src="https://github.com/iamromulan/quectel-rgmii-configuration-notes/blob/main/images/ports.png?raw=tru" alt=""></p>
<blockquote>
<p>Remember the number of the COM port described as “DM Port”.</p>
</blockquote>
<p>Step 4.</p>
<blockquote>
<p>Run QFlash<br>
Remember to avoid spaces in the path where QFlash is installed to and firmware location<br>
Example: C:\Quectel\Q flash is bad while C:\Quectel\Qflash is good</p>
</blockquote>
<blockquote>
<p>Select the COM port number as the DM port from earlier and set the baud rate to <code>460800</code></p>
</blockquote>
<p><img src="https://github.com/iamromulan/quectel-rgmii-configuration-notes/blob/main/images/portbauadqflash.png?raw=true" alt=""></p>
<p>Step 5.</p>
<blockquote>
<p>Load modem firmware (previously unpacked from the archive) into the program.</p>
</blockquote>
<p><img src="https://github.com/4IceG/Personal_data/blob/master/5G/fwinst/qfb.png?raw=true" alt=""></p>
<blockquote>
<p>In the new window, go to the <code>\update\firehose</code> folder and select file <code>partition_complete_p4K_b256K.mbn</code>. Then click the Open button.</p>
</blockquote>
<p><img src="https://github.com/4IceG/Personal_data/blob/master/5G/fwinst/qf2.png?raw=true" alt=""></p>
<p>Step 6.</p>
<blockquote>
<p>Start updating modem firmware.</p>
</blockquote>
<p><img src="https://github.com/4IceG/Personal_data/blob/master/5G/fwinst/qf3.png?raw=true" alt=""></p>


   Linux (OpenWrt) | View
<p>Step 1.</p>
<blockquote>
<p>Install the qfirehose package.<br>
In console, run commands.</p>
</blockquote>
<pre class=" language-bash"><code class="prism  language-bash">opkg update
opkg <span class="token function">install</span> qfirehose
</code></pre>
<p>Step 2.</p>
<blockquote>
<p>Using WinSCP, copy the extracted modem firmware to the \tmp folder on the router.</p>
</blockquote>
<p>Step 3.</p>
<blockquote>
<p>Start updating modem firmware.<br>
In console, run command.</p>
</blockquote>
<pre class=" language-bash"><code class="prism  language-bash">/usr/bin/qfirehose -f /tmp/RM520NGLAAR03A02M4GA
</code></pre>

<h2 id="how-to-use-qnavigator-to-send-at-commands">How to use Qnavigator to send AT commands</h2>

    View
<p>Connect your modem to your computer by USB. Either through a USB to m.2 B-key sled (should have a sim slot as well) from Amazon or by using an RGMII board’s USB C port.</p>
<h3 id="if-you-installed-by-using-the-autoinstaller">If you installed by using the autoinstaller:</h3>
<p>You should already have a desktop icon and start menu shortcut for Qnavigator.</p>
<h4 id="open-qnavagator-youll-be-presented-with-this-screen-just-press-escape-esc-to-skip-their-directions.">1. Open Qnavagator, you’ll be presented with this screen, just press escape (ESC) to skip their directions.</h4>
<p><img src="https://github.com/iamromulan/quectel-rgmii-configuration-notes/blob/main/images/qnavfirst.png?raw=true" alt="COM ports"></p>
<h4 id="uncheck-automatic-initialization-circled-in-red-and-click-the-com-plug-icon-circled-in-green">2. Uncheck Automatic initialization (circled in red) and click the COM plug icon (circled in green)</h4>
<p><img src="https://github.com/iamromulan/quectel-rgmii-configuration-notes/blob/main/images/qnavsec.png?raw=true" alt="COM ports"></p>
<h4 id="click-ok-the-correct-port-will-already-be-auto-selected">3. Click ok, the correct port will already be auto selected</h4>
<p><img src="https://github.com/iamromulan/quectel-rgmii-configuration-notes/blob/main/images/qnavport.png?raw=true" alt="qnavCOMport"></p>
<h4 id="click-connect-to-module-then-in-the-lower-right-type-your-at-command-and-press-send.-the-response-will-be-shown-above.">4. Click Connect to module, then in the lower right type your AT command and press send. The response will be shown above.</h4>
<p><img src="https://github.com/iamromulan/quectel-rgmii-configuration-notes/blob/main/images/qnavat.png?raw=true" alt="at"></p>

<h2 id="at-commands">AT commands:</h2>

   View

<table>
<thead>
<tr>
<th>Date</th>
<th>Version</th>
<th>Link</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>2024-02-07</code></td>
<td><em>RG520N&amp;RG525F&amp;RG5x0F&amp;RM5x0N&amp;RM521F Series</em></td>
<td><a href="https://mega.nz/file/2IlSVTAZ#y10u-uxWGo9afvAI54jO4JpMLLjpoFGLINVaUC49ZQY">View/Download</a></td>
</tr>
<tr>
<td><code>2023-07-31</code></td>
<td><em>RG520N&amp;RG525F&amp;RG5x0F&amp;RM5x0NSeries</em></td>
<td><a href="https://mega.nz/file/zEEmCYTb#Y_YVlSEWNn9tz9dpHvY1rSZuDR_gEB6XEVIQ0nGrCJQ">View/Download</a></td>
</tr>
<tr>
<td><code>2022-08-12</code></td>
<td><em>RG520N&amp;RG52xF&amp;RG530F&amp;RM520N&amp;RM530NSeries</em></td>
<td><a href="https://mega.nz/file/zIllzT7S#leMbHiKL_jmEy2LZMp1-3aI2BLW2m8vkNFl8ApT3FQw">View/Download</a></td>
</tr>
<tr>
<td><code>2021-08-09</code></td>
<td><em>RG50xQ&amp;RM5xxQ Series</em></td>
<td><a href="https://mega.nz/file/mVNRXZrI#FS1_8YIZgqEEcyjWG1__RMI5IeiTc6yrwU9xw6bCpsQ">View/Download</a></td>
</tr>
<tr>
<td><code>2020-10-09</code></td>
<td><em>RG50xQ&amp;RM5xxQ Series</em></td>
<td><a href="https://mega.nz/file/nIlhFBhS#QuJZIaN0EkBvLYqFhSUCv_qjx0aGsSG04VXUp1huATw">View/Download</a></td>
</tr>
</tbody>
</table>
<h2 id="other-docs">Other Docs</h2>

   General
<p><a href="https://www2.quectel.com/5GLTEAdvance">[NEW!] Quectel 5G&amp;LTE-Advanced Module Product Overview V7.1</a></p>
<p><a href="https://mega.nz/file/TI9yHTjL#iJVMKIMRH-gaIwoSZkUDgmAU3s9hjL3I1brFHeV0t-I">Quectel Product Brochure V7.4</a></p>
<p><a href="https://mega.nz/file/HMsgAI7Q#kVLf7ETrE13zrsUUmdq2NUe2d26ZSkbeqgmNXQ4offw">QCOM User Guide V1.1</a></p>
<p><a href="https://mega.nz/file/bQsw1YqS#c2j1rqAvUZRAhQUniaHfUD0CZZNvxtusW12eIgReDzI">QFlash User Guide V5.0 </a></p>
<p><a href="https://mega.nz/file/fRlBgSDb#zusk1tH29-4HGu9tJJfxkpARlbo-LBwz3h4Bqk9qTEI">[Updated!] Quectel RM520N-GL Hardware Design</a></p>
<p><a href="https://mega.nz/file/TcdFgJhQ#C6zNX0rSsrLOFy5bqUk5fnPZ-W7vFQBvh8gVyOxfNmk">[NEW!] Reference Design</a></p>
<p><a href="https://mega.nz/file/vAcmWAzK#3IkjR9WLL9BQjKV9SEvDsuNgp-g0Bbm-TcLtRqMR6H8">[NEW!] A/B System Update Guide</a></p>
<p><a href="https://mega.nz/file/zAcUEIDL#_qEpH1C3rmDpaKFTUyud4zQY88pUEKrHhN1-qzY21bE">[NEW!] DFOTA Upgrade Process</a></p>
<p><a href="https://mega.nz/file/Oc1C1DIQ#mucxYGBrauLJAhQUKDuIB9cb_ETuod743XE_eb-boqE">[NEW!] TCP/IP Application Note</a></p>
<p><a href="https://mega.nz/file/KV1XSYAT#sKN5N1HPjHETpk06zi7s_FXGNR2HaxIp4Qbw_cmy3Vc">[NEW!] Data Call Application Note</a></p>
<p><a href="https://mega.nz/file/CN1HQKyb#18bN9uZKJf6zInXDhsLWMW1mlP2tkM_QpC1X8i9r_v8">[NEW!] eSIM LPA Application Note 1.1</a></p>
<p><a href="https://mega.nz/file/KU1QWYzC#9CB5ikUD6-YtcUzjaACEeA3YobYJXUhddalFRZ1KTZ4">[NEW!] eSIM LPA Application Note 1.0</a></p>
<p><a href="https://mega.nz/file/aBkDSQAK#JMy2f4n-hMfDHoFbc6uQkOpr-lhc58v6Kqp0-NUH8rE">[NEW!] Voice Over ttyUSB Application Note</a></p>
<p><a href="https://mega.nz/file/KAkFyTJQ#GekOQec5Ma2THtbQRQWfsK9_z6pGpFHe1XYxS1wMw-g">[NEW!] External VoLTE stack Application Note</a></p>
<p><a href="https://mega.nz/file/jUEzlYaT#4ayxXXgZ62yr4qUPMneocvm_1ZhZ_N9y1mclvi5rrv4">[NEW!] File Application Note</a></p>
<p><a href="https://mega.nz/file/fY1w3QIK#XyrfW-cIHq30ZsLwFS7pJxc-6ZwAAP32Omh7IPLbSeY">[NEW!] GNSS Application Note</a></p>
<p><a href="https://mega.nz/file/nc810Jhb#gsnFEC8vhGYV_IY6boIKraz-aTnIr8oFOoAuph6lndM">[NEW!] HTTP(S) Application Note</a></p>
<p><a href="https://mega.nz/file/6cNWERgL#hNHEBKAbLoZzzUoBxdzHmyH_TR9cAV1gM5SCCyKLlHA">[NEW!] Software Thermal Management Guide</a></p>
<p><a href="https://mega.nz/file/bJE1zbDQ#gj1-4KrFbhLLbSUaoaKNhbVRz7M-X5beMXFcwwbyGss">[NEW!] Thermal Design Guide</a></p>
<p><a href="https://mega.nz/file/aIsWgKRB#n7YcwAsreFfCYTcTw0Vk06Y0EQk6yYwa8AwP1IMuRHQ">[NEW!] 5G Network Status Judgement Introduction</a></p>
<p><a href="https://mega.nz/file/HIMRkAwA#7O19pLJwHKF2cYRs_y68sKo2Vd7HmjRmmBrnUOFrSuo">[NEW!] CA Combos Spreadsheet</a></p>


   [NEW!] QuecOpen
<p><a href="https://mega.nz/file/LRVDDYCQ#VFARx9j_0g43LaBS_-4IPDjQwAR55dePl4eVgFQcGXY">DFOTA Generation Tool Directions </a></p>
<p><a href="https://mega.nz/file/qBt3jTBD#f7KaTzcHwtDhBO6pmucQUqjfUh2Ue91ywMasldNrCh4">[NEW!] FullFOTA Update Guide</a></p>
<p><a href="https://mega.nz/file/LNMUAarY#auGqgn3m-6_s1v3jOQ3W7YiqfKU_2Obn5mGMzbtPXzY">[NEW!] Virtual Port Programming for AT Command Sending and Receiving Guide</a></p>
<p><a href="https://mega.nz/file/nQdUlS5S#u9NCOPapYfc6LlCzC2SYSPKORokG3NGMwV7L7u_cjRM">[NEW!] Device Management and Cellular Network Development Guide</a></p>
<p><a href="https://mega.nz/file/3d1HlKYL#j3dEHFOHTpaMbogDgn2WCRSiilWNMzila21eZHwvmok">[NEW!] Linux System Time Synchronization Guide </a></p>
<p><a href="https://mega.nz/file/mdkU1b6A#gjq-N6__TMZrSTe4oXurworrwDlUsCDCCHJg-pQ2fXk">[NEW!] Open-Source Software Package Cross-Compilation Guide</a></p>
<p><a href="https://mega.nz/file/uQ0BkS5Z#uaSgFc8yEbHKuS0_vefbVeeZHEVsfJ27PhehivArQcw">[NEW!] SIM and SMS Development Guide</a></p>
<p><a href="https://mega.nz/file/6Q1Q0R5Z#WQyE8ab0PgTkFQDeV_g5qxDom-4KQB2vyvqARyEG09o">[NEW!] Upgrade via LAN Application Note</a></p>

<h2 id="description-of-antenna-connection">Description of antenna connection:</h2>

   View
<p><img src="https://github.com/4IceG/Personal_data/blob/master/5G/antenasmall.png?raw=true" alt=""><br>
<img src="https://github.com/4IceG/Personal_data/blob/master/5G/rm520n-gl.PNG?raw=true" alt=""></p>

<h2 id="specification">Specification:</h2>
<p><img src="https://github.com/4IceG/Personal_data/blob/master/5G/quectel_rm520n-gl_5g_specification_v1-0-0_preliminary_20210915-1.png?raw=true" alt=""><br>
<img src="https://github.com/4IceG/Personal_data/blob/master/5G/quectel_rm520n-gl_5g_specification_v1-0-0_preliminary_20210915-2.png?raw=true" alt=""></p>

