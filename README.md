# ONDA-B460SD4-ITX-EFI

EFI文件是根据网上教程修改而来,借鉴了很多大佬的教程<br>

EFI是根据本人配置搭配,不一定适合所有人,任何问题自行承担<br>

请注意HDMI输出如果是闪黑屏就要调到2k @ 60Hz以下，最好选带DP的板子<br>

自行替换三码<br>

昂达B460SD4-itx主板的EFI文件<br>(Monterey升级后会出现运行卡顿，开机慢等问题，建议想升级的再等等)


## 电脑配置:

<table style="width:40%;text-align:center">
    <thead>
    <th>设备</th>
    <th>型号</th>
    </thead>
    <tbody>
    <tr><td>CPU</td><td>i5-10400</td></tr>
    <tr><td>主板</td><td>昂达B460sd4-ITX2.0全固板</td></tr>
    <tr><td>显卡</td><td>Inter UHD Graphics 630</td></tr>
    <tr><td>无线</td><td>Wi-Fi 6 AX200</td></tr>
    <tr><td>蓝牙</td><td>Wi-Fi 6 AX200</td></tr>
    </tbody>
</table>

## 引导/系统:

<table STYLE="width:40%;text-align:center">
    <thead>
        <th>项目</th>
        <th>版本</th>
    </thead>
    <tbody>
        <tr>
            <td>openCore</td>
            <td>0.7.5</td>
        </tr>
        <tr>
            <TD>MAC</TD>
            <TD>BigSur11.6.1</TD>
        </tr>
    </tbody>
</table>


## 改三码工具
<table>
    <thead>
        <th>软件</th>
        <th>地址</th>
    </thead>
    <tbody>
        <tr><td>GenSMBIOS</td><td>https://github.com/corpnewt/GenSMBIOS</td></tr>
        <tr><td>ProperTree</td><td>https://github.com/corpnewt/ProperTree</td>
    </tbody>
</table>

## 推荐 BIOS 设置
<ul><li><strong>禁用:</strong></li></ul>
<table><thead><tr><th style="text-align:center">英文</th><th style="text-align:center">中文</th></tr></thead><tbody><tr><td style="text-align:center">Fast Boot</td><td style="text-align:center">快速启动</td></tr><tr><td style="text-align:center">CFG Lock (MSR 0xE2 write protection)</td><td style="text-align:center">CFG 锁 (MSR 0xE2 写入保护)</td></tr><tr><td style="text-align:center">VT-d</td><td style="text-align:center"><a href="https://zhidao.baidu.com/question/495526512.html" target="_blank" rel="noopener">VT-d</a></td></tr><tr><td style="text-align:center">CSM</td><td style="text-align:center">兼容性支持模块</td></tr><tr><td style="text-align:center">Intel SGX</td><td style="text-align:center">Intel SGX</td></tr></tbody></table>
<hr style="height:3px;background-color:gray;">
<ul><li><strong>启用:</strong></li></ul>
<table><thead><tr><th style="text-align:center">英文</th><th style="text-align:center">中文</th></tr></thead><tbody><tr><td style="text-align:center">VT-x</td><td style="text-align:center"><a href="https://zhidao.baidu.com/question/495526512.html" target="_blank" rel="noopener">VT-x</a></td></tr><tr><td style="text-align:center">Above 4G decoding</td><td style="text-align:center">大于 4G 地址空间解码</td></tr><tr><td style="text-align:center">Hyper Threading</td><td style="text-align:center">处理器超线程</td></tr><tr><td style="text-align:center">Execute Disable Bit</td><td style="text-align:center">执行禁止位</td></tr><tr><td style="text-align:center">EHCI/XHCI Hand-off</td><td style="text-align:center">接手 EHCI/XHCI 控制</td></tr><tr><td style="text-align:center">OS type: Windows 8.1/10</td><td style="text-align:center">操作系统类型: Windows 8.1/10</td></tr><tr><td style="text-align:center">Legacy RTC Device</td><td style="text-align:center">传统 RTC 设备</td></tr></tbody></table>

## 主题
<b>来自：@blackosx https://github.com/blackosx/BsxM1</b>
<img src="https://cdn.jsdelivr.net/gh/blackosx/BsxM1@main/preview_ui.jpg">


