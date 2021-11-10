# ONDA-B460SD4-ITX-EFI

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

## BIOS 设置

关闭CFG Lock,Fast Boot

开启Above 4G MMIO BIOS assignment

EFI文件是根据网上教程修改而来,借鉴了很多大佬的教程

EFI是根据本人配置搭配,不一定适合所有人,任何问题自行承担

请注意HDMI输出如果是闪黑屏就要调到2k @ 60Hz以下，最好选带DP的板子

自行替换三码


## 主题
<b>来自：@blackosx https://github.com/blackosx/BsxM1</b>
<img src="https://cdn.jsdelivr.net/gh/blackosx/BsxM1@main/preview_ui.jpg">
