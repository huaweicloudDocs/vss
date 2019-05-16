# Windows主机授权<a name="vss_01_0110"></a>

## 操作场景<a name="section16543350162518"></a>

该任务指导用户通过漏洞扫描服务对已添加的华为云主机的Windows主机进行扫描授权。

## 前提条件<a name="section20902165162619"></a>

-   已获取管理控制台的登录帐号与密码。
-   登录用户只支持Administrator。
-   已添加华为云的Windows主机。

## 操作步骤<a name="section7792115993011"></a>

1.  登录管理控制台。
2.  单击页面上方的“服务列表“，选择“安全  \>  漏洞扫描服务“，在左侧导航树中，单击“资产列表“，进入“资产列表“界面。
3.  在“资产列表“页面，选择“主机“页签，勾选需要授权的Windows主机，在“批量操作“的下拉框中，单击“编辑“，如[图1](#fig1227015374407)所示。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >用户也可以单台主机授权，在目标主机所在行的“操作“列，单击“编辑“。  

    **图 1**  Windows主机授权<a name="fig1227015374407"></a>  
    ![](figures/Windows主机授权.png "Windows主机授权")

4.  在主机授权页面，批量选择需要授权的主机，单击“批量配置授权信息“，如[图2](#fig37091438195719)所示。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >-   用户也可以单台主机授权，在目标主机所在行的“操作“列，单击“配置授权信息“。  
    >-   如果需要修改主机名称，单击![](figures/编辑小图标-6.png)，在弹出的对话框中，进行修改。  

    **图 2**  批量授权<a name="fig37091438195719"></a>  
    ![](figures/批量授权-7.png "批量授权-7")

5.  在弹出的对话框中，选择已有Windows账号，或者单击“创建Windows账号“创建Windows账号，如[图3](#fig1851741671217)所示。

    **图 3**  配置授权信息<a name="fig1851741671217"></a>  
    ![](figures/配置授权信息.png "配置授权信息")

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >-   如果需要修改已有Windows账号，单击“编辑“，进行修改。  
    >-   如果需要删除已有Windows账号，单击“删除“，删除账号。  

    如果没有Windows账号，单击“创建Windows账号“创建账号，如[图4](#fig98124191127)所示，参数说明如[表1](#table1947303131)。

    **图 4**  创建Windows账号<a name="fig98124191127"></a>  
    ![](figures/创建Windows账号.png "创建Windows账号")

    **表 1**  参数说明

    <a name="table1947303131"></a>
    <table><thead align="left"><tr id="row184230161317"><th class="cellrowborder" valign="top" width="40.21%" id="mcps1.2.3.1.1"><p id="p4473011312"><a name="p4473011312"></a><a name="p4473011312"></a>参数名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="59.79%" id="mcps1.2.3.1.2"><p id="p17463001319"><a name="p17463001319"></a><a name="p17463001319"></a>参数说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row5453018135"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p1794185011135"><a name="p1794185011135"></a><a name="p1794185011135"></a>windows账号别称</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p24143021311"><a name="p24143021311"></a><a name="p24143021311"></a>自定义Windows账号名称。</p>
    </td>
    </tr>
    <tr id="row84203016138"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p6417306136"><a name="p6417306136"></a><a name="p6417306136"></a>选择加密密钥</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p6453081317"><a name="p6453081317"></a><a name="p6453081317"></a>选择已有的加密密钥，或者单击<span class="parmvalue" id="parmvalue9131153885917"><a name="parmvalue9131153885917"></a><a name="parmvalue9131153885917"></a>“创建密钥”</span>，创建新的密钥，具体方法请参考<a href="https://support.huaweicloud.com/usermanual-dew/zh-cn_topic_0034324884.html" target="_blank" rel="noopener noreferrer">创建密钥</a>。</p>
    </td>
    </tr>
    <tr id="row241230111310"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p1341830121316"><a name="p1341830121316"></a><a name="p1341830121316"></a>用户名</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p1441230161314"><a name="p1441230161314"></a><a name="p1441230161314"></a>默认为Administrator。</p>
    </td>
    </tr>
    <tr id="row981737121518"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p18831437101517"><a name="p18831437101517"></a><a name="p18831437101517"></a>密码</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p198363791511"><a name="p198363791511"></a><a name="p198363791511"></a>Windows系统登录密码。</p>
    </td>
    </tr>
    <tr id="row10729144117152"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p1272934119151"><a name="p1272934119151"></a><a name="p1272934119151"></a>账号域</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p16729541111510"><a name="p16729541111510"></a><a name="p16729541111510"></a>查看该Windows系统的账号域并填写到此处，该参数也可以为空，不填写。</p>
    </td>
    </tr>
    </tbody>
    </table>

6.  单击“确定“，完成Windows主机授权。

