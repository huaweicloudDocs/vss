# 配置Windows主机授权<a name="vss_01_0110"></a>

## 操作场景<a name="section16543350162518"></a>

该任务指导用户通过漏洞扫描服务对已添加的Windows主机进行扫描授权。

## 前提条件<a name="section20902165162619"></a>

-   已获取管理控制台的登录账号与密码。
-   登录用户只支持Administrator。
-   已添加Windows主机。

## 操作步骤<a name="section7792115993011"></a>

1.  [登录管理控制台](https://console.huaweicloud.com/)。
2.  进入批量授权入口，如[图1](#vss_01_0072_fig1441123313521)所示。

    **图 1**  进入批量授权入口<a name="vss_01_0072_fig1441123313521"></a>  
    ![](figures/进入批量授权入口.png "进入批量授权入口")

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >用户也可以单台主机授权，在目标主机所在行的“操作“列，单击“编辑“。  

3.  在主机授权页面，批量选择需要授权的主机，单击“批量配置授权信息“，如[图2](#fig37091438195719)所示。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >-   用户也可以单台主机授权，在目标主机所在行的“操作“列，单击“配置授权信息“。  
    >-   如果需要修改主机名称，单击![](figures/编辑小图标-9.png)，在弹出的对话框中，进行修改。  

    **图 2**  批量授权<a name="fig37091438195719"></a>  
    ![](figures/批量授权-10.png "批量授权-10")

4.  在弹出的对话框中，选择已有windows授权，或者单击“创建windows授权“创建windows授权，如[图3](#fig1851741671217)所示。

    **图 3**  配置授权信息<a name="fig1851741671217"></a>  
    ![](figures/配置授权信息.png "配置授权信息")

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >-   如果需要修改已有windows授权，单击“编辑“，进行修改。  
    >-   如果需要删除已有windows授权，单击“删除“，进行删除。  

    如果没有windows授权，单击“创建windows授权“创建授权，如[图4](#fig98124191127)所示，参数说明如[表1](#table1947303131)。

    **图 4**  创建windows授权<a name="fig98124191127"></a>  
    ![](figures/创建windows授权.png "创建windows授权")

    **表 1**  参数说明

    <a name="table1947303131"></a>
    <table><thead align="left"><tr id="row184230161317"><th class="cellrowborder" valign="top" width="40.21%" id="mcps1.2.3.1.1"><p id="p4473011312"><a name="p4473011312"></a><a name="p4473011312"></a>参数名称</p>
    </th>
    <th class="cellrowborder" valign="top" width="59.79%" id="mcps1.2.3.1.2"><p id="p17463001319"><a name="p17463001319"></a><a name="p17463001319"></a>参数说明</p>
    </th>
    </tr>
    </thead>
    <tbody><tr id="row5453018135"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p1794185011135"><a name="p1794185011135"></a><a name="p1794185011135"></a>windows授权别称</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p24143021311"><a name="p24143021311"></a><a name="p24143021311"></a>自定义windows授权名称。</p>
    </td>
    </tr>
    <tr id="row84203016138"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p6417306136"><a name="p6417306136"></a><a name="p6417306136"></a>选择加密密钥</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p1996864217345"><a name="p1996864217345"></a><a name="p1996864217345"></a>为了保护主机登录密码或密钥安全，请您必须使用加密密钥，以避免登录密码或密钥明文存储和泄露风险。</p>
    <p id="p6453081317"><a name="p6453081317"></a><a name="p6453081317"></a>您可以选择已有的加密密钥，或者单击<span class="parmvalue" id="vss_01_0072_parmvalue4481414131918"><a name="vss_01_0072_parmvalue4481414131918"></a><a name="vss_01_0072_parmvalue4481414131918"></a>“创建密钥”</span>，在数据加密服务的<span class="wintitle" id="vss_01_0072_wintitle431673312219"><a name="vss_01_0072_wintitle431673312219"></a><a name="vss_01_0072_wintitle431673312219"></a>“密钥管理”</span>界面创建新的密钥。</p>
    <div class="notice" id="note14521044112515"><a name="note14521044112515"></a><a name="note14521044112515"></a><span class="noticetitle"> 须知： </span><div class="noticebody"><a name="vss_01_0072_ul37241450132619"></a><a name="vss_01_0072_ul37241450132619"></a><ul id="vss_01_0072_ul37241450132619"><li>使用数据加密服务需要单独计费，详细的服务资费和费率标准，请参见<a href="https://www.huaweicloud.com/pricing.html?tab=detail#/dew" target="_blank" rel="noopener noreferrer">价格详情</a>。</li><li>VSS支持以下区域的密钥：<a name="vss_01_0072_ul791718300011"></a><a name="vss_01_0072_ul791718300011"></a><ul id="vss_01_0072_ul791718300011"><li>华北-北京一</li><li>华南-广州</li><li>华东-上海二</li></ul>
    <p id="vss_01_0072_p122782719372"><a name="vss_01_0072_p122782719372"></a><a name="vss_01_0072_p122782719372"></a>请您选择这些区域已有的加密密钥或者在这些区域创建密钥。有关创建密钥的详细操作，请参见<a href="https://support.huaweicloud.com/usermanual-dew/zh-cn_topic_0034324884.html" target="_blank" rel="noopener noreferrer">创建密钥</a>。</p>
    </li></ul>
    </div></div>
    </td>
    </tr>
    <tr id="row241230111310"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p1341830121316"><a name="p1341830121316"></a><a name="p1341830121316"></a>用户名</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p1441230161314"><a name="p1441230161314"></a><a name="p1441230161314"></a>默认为Administrator。</p>
    </td>
    </tr>
    <tr id="row981737121518"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p18831437101517"><a name="p18831437101517"></a><a name="p18831437101517"></a>密码</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p198363791511"><a name="p198363791511"></a><a name="p198363791511"></a>windows系统登录密码。</p>
    </td>
    </tr>
    <tr id="row10729144117152"><td class="cellrowborder" valign="top" width="40.21%" headers="mcps1.2.3.1.1 "><p id="p1272934119151"><a name="p1272934119151"></a><a name="p1272934119151"></a>账号域</p>
    </td>
    <td class="cellrowborder" valign="top" width="59.79%" headers="mcps1.2.3.1.2 "><p id="p16729541111510"><a name="p16729541111510"></a><a name="p16729541111510"></a>查看该windows系统的账号域并填写到此处，该参数也可以为空，不填写。</p>
    </td>
    </tr>
    </tbody>
    </table>

5.  单击“确定“，完成Windows主机授权。

## 相关操作<a name="section789610521901"></a>

配置主机授权后，您可以取消主机授权，取消主机授权后，将不能完全扫描出主机的安全风险。有关取消主机授权的详细操作，请参见[取消主机授权](取消主机授权.md)。

