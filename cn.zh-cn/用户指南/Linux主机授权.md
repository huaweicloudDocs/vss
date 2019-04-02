# Linux主机授权<a name="vss_01_0072"></a>

## 操作场景<a name="section12982110131912"></a>

该任务指导用户通过漏洞扫描服务对已添加的Linux主机进行扫描授权。

## 前提条件<a name="section1476173172214"></a>

-   已获取管理控制台的登录帐号与密码。
-   已添加Linux主机。

## 操作步骤<a name="section038111403433"></a>

1.  登录管理控制台。
2.  单击页面上方的“服务列表“，选择“安全  \>  漏洞扫描服务“，在左侧导航树中，单击“资产列表“，进入“资产列表“界面。
3.  在“资产列表“页面，选择“主机“页签，勾选需要授权的Linux主机，在“批量操作“的下拉框中，单击“编辑“，如[图1](#fig6288185203910)所示。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >用户也可以单台主机授权，在目标主机所在行的“操作“列，单击“编辑“。  

    **图 1**  主机授权<a name="fig6288185203910"></a>  
    ![](figures/主机授权.png "主机授权")

4.  在主机授权页面，批量选择需要授权的主机，单击“批量配置授权信息“，如[图2](#fig37091438195719)所示。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >-   用户也可以单台主机授权，在目标主机所在行的“操作“列，单击“配置授权信息“。  
    >-   如果需要修改主机名称，单击![](figures/编辑小图标-3.png)，在弹出的对话框中，进行修改。  

    **图 2**  批量授权<a name="fig37091438195719"></a>  
    ![](figures/批量授权.png "批量授权")

5.  选择授权方式进行主机授权。
    -   方式一：SSH账号登录。

        **图 3**  SSH账号登录<a name="fig1851741671217"></a>  
        ![](figures/SSH账号登录.png "SSH账号登录")

        >![](public_sys-resources/icon-note.gif) **说明：**   
        >-   如果需要修改已有SSH帐号，单击“编辑“，进行修改。  
        >-   如果需要删除已有SSH帐号，单击“删除“，删除账号。  

        选择已有SSH账号，或者单击“创建SSH账号“创建SSH账号，如[图4](#fig134721333142710)所示，参数说明如[表1](#table12871221122820)所示。

        **图 4**  创建SSH账号<a name="fig134721333142710"></a>  
        ![](figures/创建SSH账号.png "创建SSH账号")

        **表 1**  参数说明

        <a name="table12871221122820"></a>
        <table><thead align="left"><tr id="row12287122117282"><th class="cellrowborder" valign="top" width="38.07%" id="mcps1.2.3.1.1"><p id="p10288172111283"><a name="p10288172111283"></a><a name="p10288172111283"></a>参数名称</p>
        </th>
        <th class="cellrowborder" valign="top" width="61.92999999999999%" id="mcps1.2.3.1.2"><p id="p15288521162815"><a name="p15288521162815"></a><a name="p15288521162815"></a>参数说明</p>
        </th>
        </tr>
        </thead>
        <tbody><tr id="row1628810219289"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p9288021102816"><a name="p9288021102816"></a><a name="p9288021102816"></a>SSH账号别称</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p828815217282"><a name="p828815217282"></a><a name="p828815217282"></a>自定义SSH账号名称。</p>
        </td>
        </tr>
        <tr id="row1728872118288"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p1928802116285"><a name="p1928802116285"></a><a name="p1928802116285"></a>登录端口</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p5288152113281"><a name="p5288152113281"></a><a name="p5288152113281"></a>SSH账号登录的端口号。</p>
        </td>
        </tr>
        <tr id="row14288152112812"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p1928822192813"><a name="p1928822192813"></a><a name="p1928822192813"></a>选择登录方式</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><a name="ul3981151617322"></a><a name="ul3981151617322"></a><ul id="ul3981151617322"><li><span class="parmvalue" id="parmvalue1228913315397"><a name="parmvalue1228913315397"></a><a name="parmvalue1228913315397"></a>“密码登录”</span></li><li><span class="parmvalue" id="parmvalue16071033203911"><a name="parmvalue16071033203911"></a><a name="parmvalue16071033203911"></a>“密钥登录”</span><p id="p1968010472398"><a name="p1968010472398"></a><a name="p1968010472398"></a>选择<span class="parmvalue" id="parmvalue355656123910"><a name="parmvalue355656123910"></a><a name="parmvalue355656123910"></a>“密钥登录”</span>时，需要<span class="parmvalue" id="parmvalue293813064011"><a name="parmvalue293813064011"></a><a name="parmvalue293813064011"></a>“创建私钥”</span>。</p>
        </li></ul>
        </td>
        </tr>
        <tr id="row1288102142812"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p928812182810"><a name="p928812182810"></a><a name="p928812182810"></a>选择加密密钥</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p18288142122810"><a name="p18288142122810"></a><a name="p18288142122810"></a>选择已有的加密密钥，或者单击<span class="parmvalue" id="parmvalue9131153885917"><a name="parmvalue9131153885917"></a><a name="parmvalue9131153885917"></a>“创建密钥”</span>，创建新的密钥，具体方法请参考<a href="https://support.huaweicloud.com/usermanual-dew/zh-cn_topic_0034324884.html" target="_blank" rel="noopener noreferrer">创建密钥</a>。</p>
        </td>
        </tr>
        <tr id="row1928862112289"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p10288202152813"><a name="p10288202152813"></a><a name="p10288202152813"></a>Root权限是否加固</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p122881521182816"><a name="p122881521182816"></a><a name="p122881521182816"></a>打开该权限后，不可以用root账号直接登录，而只能通过普通用户登录，然后才能切换到root用户。</p>
        </td>
        </tr>
        <tr id="row10585441122919"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p2058664116297"><a name="p2058664116297"></a><a name="p2058664116297"></a>sudo用户名</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p16586134115296"><a name="p16586134115296"></a><a name="p16586134115296"></a>默认为root。</p>
        </td>
        </tr>
        <tr id="row15830114516295"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p883010451293"><a name="p883010451293"></a><a name="p883010451293"></a>sudo密码</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p1283013457293"><a name="p1283013457293"></a><a name="p1283013457293"></a>设置sudo用户对应的密码，单击<span class="uicontrol" id="uicontrol1229145943713"><a name="uicontrol1229145943713"></a><a name="uicontrol1229145943713"></a>“加密保存”</span>，对密码进行加密保存。</p>
        </td>
        </tr>
        </tbody>
        </table>

    -   方式二：授权脚本执行。

        >![](public_sys-resources/icon-note.gif) **说明：**   
        >用户也可以在“主机“页面，单击“扫描授权“，通过授权脚本执行完成主机授权。  

        **图 5**  授权脚本执行<a name="fig1967013143333"></a>  
        ![](figures/授权脚本执行.png "授权脚本执行")

        1.  单击界面上的“复制“，复制开通授权的命令。
        2.  使用远程管理工具（例如：“Xshell“、“SecureCRT“、“PuTTY“），通过弹性IP地址登录到待开通授权的弹性云服务器。

            >![](public_sys-resources/icon-note.gif) **说明：**   
            >也可使用弹性云服务器的“远程登录“功能，登录服务器。  

        3.  执行复制的命令（这里用“SecureCRT“工具登录），结果如[图6](#fig1567291413332)所示，即执行成功。

            **图 6**  执行结果<a name="fig1567291413332"></a>  
            ![](figures/执行结果.png "执行结果")



6.  单击“确定“，完成Linux主机授权。

