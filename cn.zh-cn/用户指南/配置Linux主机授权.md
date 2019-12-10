# 配置Linux主机授权<a name="vss_01_0072"></a>

## 操作场景<a name="section12982110131912"></a>

该任务指导用户通过漏洞扫描服务对已添加的Linux主机进行扫描授权。

## 前提条件<a name="section1476173172214"></a>

-   已获取管理控制台的登录账号与密码。
-   已添加Linux主机。

## 操作步骤<a name="section038111403433"></a>

1.  [登录管理控制台](https://console.huaweicloud.com/)。
2.  进入批量授权入口，如[图1](#fig1441123313521)所示。

    **图 1**  进入批量授权入口<a name="fig1441123313521"></a>  
    ![](figures/进入批量授权入口.png "进入批量授权入口")

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >用户也可以单台主机授权，在目标主机所在行的“操作“列，单击“编辑“。  

3.  在主机授权页面，批量选择需要授权的主机，单击“批量配置授权信息“，如[图2](#fig37091438195719)所示。

    >![](public_sys-resources/icon-note.gif) **说明：**   
    >-   用户也可以单台主机授权，在目标主机所在行的“操作“列，单击“配置授权信息“。  
    >-   如果需要修改主机名称，单击![](figures/编辑小图标.png)，在弹出的对话框中，进行修改。  

    **图 2**  批量授权<a name="fig37091438195719"></a>  
    ![](figures/批量授权.png "批量授权")

4.  选择授权方式进行主机授权。
    -   方式一：SSH授权登录

        **图 3**  SSH授权登录<a name="fig24694146195"></a>  
        ![](figures/SSH授权登录.png "SSH授权登录")

        >![](public_sys-resources/icon-note.gif) **说明：**   
        >-   如果需要修改已有SSH授权，单击“编辑“，进行修改。  
        >-   如果需要删除已有SSH授权，单击“删除“，进行删除。  

        选择已有SSH授权，或者单击“创建SSH授权“创建SSH授权，如[图4](#fig19477214111918)所示，参数说明如[表1](#table1448281421911)所示。

        **图 4**  创建SSH授权<a name="fig19477214111918"></a>  
        ![](figures/创建SSH授权.png "创建SSH授权")

        **表 1**  参数说明

        <a name="table1448281421911"></a>
        <table><thead align="left"><tr id="row6478214131913"><th class="cellrowborder" valign="top" width="38.07%" id="mcps1.2.3.1.1"><p id="p184781147195"><a name="p184781147195"></a><a name="p184781147195"></a>参数名称</p>
        </th>
        <th class="cellrowborder" valign="top" width="61.92999999999999%" id="mcps1.2.3.1.2"><p id="p147851411916"><a name="p147851411916"></a><a name="p147851411916"></a>参数说明</p>
        </th>
        </tr>
        </thead>
        <tbody><tr id="row14793148194"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p34791614161911"><a name="p34791614161911"></a><a name="p34791614161911"></a>SSH授权别称</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p1747971441910"><a name="p1747971441910"></a><a name="p1747971441910"></a>自定义SSH授权名称。</p>
        </td>
        </tr>
        <tr id="row44799142191"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p13479111431913"><a name="p13479111431913"></a><a name="p13479111431913"></a>登录端口</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p14878244164012"><a name="p14878244164012"></a><a name="p14878244164012"></a>SSH授权登录的端口号。</p>
        <p id="p147971413192"><a name="p147971413192"></a><a name="p147971413192"></a>请确保安全组已添加该端口，以便主机可通过该端口访问VSS。</p>
        </td>
        </tr>
        <tr id="row144819141191"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p347911413194"><a name="p347911413194"></a><a name="p347911413194"></a>选择登录方式</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><a name="ul6480181481912"></a><a name="ul6480181481912"></a><ul id="ul6480181481912"><li><span class="parmvalue" id="parmvalue54801414191913"><a name="parmvalue54801414191913"></a><a name="parmvalue54801414191913"></a>“密码登录”</span></li><li><span class="parmvalue" id="parmvalue1548001451911"><a name="parmvalue1548001451911"></a><a name="parmvalue1548001451911"></a>“密钥登录”</span></li></ul>
        <p id="p2481514121911"><a name="p2481514121911"></a><a name="p2481514121911"></a>选择<span class="parmvalue" id="parmvalue34805144196"><a name="parmvalue34805144196"></a><a name="parmvalue34805144196"></a>“密钥登录”</span>时，需要<span class="parmvalue" id="parmvalue144801614131910"><a name="parmvalue144801614131910"></a><a name="parmvalue144801614131910"></a>“创建私钥”</span>。</p>
        </td>
        </tr>
        <tr id="row174811414131910"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p1248191401910"><a name="p1248191401910"></a><a name="p1248191401910"></a>选择加密密钥</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p6310449102613"><a name="p6310449102613"></a><a name="p6310449102613"></a>为了保护主机登录密码或密钥安全，请您必须使用加密密钥，以避免登录密码或密钥明文存储和泄露风险。</p>
        <p id="p0481214191913"><a name="p0481214191913"></a><a name="p0481214191913"></a>您可以选择已有的加密密钥，或者单击<span class="parmvalue" id="parmvalue4481414131918"><a name="parmvalue4481414131918"></a><a name="parmvalue4481414131918"></a>“创建密钥”</span>，在数据加密服务的<span class="wintitle" id="wintitle431673312219"><a name="wintitle431673312219"></a><a name="wintitle431673312219"></a>“密钥管理”</span>界面创建新的密钥。</p>
        <div class="notice" id="note1049461015267"><a name="note1049461015267"></a><a name="note1049461015267"></a><span class="noticetitle"> 须知： </span><div class="noticebody"><a name="ul37241450132619"></a><a name="ul37241450132619"></a><ul id="ul37241450132619"><li>使用数据加密服务需要单独计费，详细的服务资费和费率标准，请参见<a href="https://www.huaweicloud.com/pricing.html?tab=detail#/dew" target="_blank" rel="noopener noreferrer">价格详情</a>。</li><li>VSS支持以下区域的密钥：<a name="ul791718300011"></a><a name="ul791718300011"></a><ul id="ul791718300011"><li>华北-北京一</li><li>华南-广州</li><li>华东-上海二</li></ul>
        <p id="p122782719372"><a name="p122782719372"></a><a name="p122782719372"></a>请您选择这些区域已有的加密密钥或者在这些区域创建密钥。有关创建密钥的详细操作，请参见<a href="https://support.huaweicloud.com/usermanual-dew/zh-cn_topic_0034324884.html" target="_blank" rel="noopener noreferrer">创建密钥</a>。</p>
        </li></ul>
        </div></div>
        </td>
        </tr>
        <tr id="row1548161491918"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p34811214141919"><a name="p34811214141919"></a><a name="p34811214141919"></a>Root权限是否加固</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p114811514141910"><a name="p114811514141910"></a><a name="p114811514141910"></a>打开该权限后，不可以用root账号直接登录，而只能通过普通用户登录，然后才能切换到root用户。</p>
        </td>
        </tr>
        <tr id="row9481214121910"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p148117142197"><a name="p148117142197"></a><a name="p148117142197"></a>sudo用户名</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p0481191441916"><a name="p0481191441916"></a><a name="p0481191441916"></a>默认为root。</p>
        </td>
        </tr>
        <tr id="row148281481916"><td class="cellrowborder" valign="top" width="38.07%" headers="mcps1.2.3.1.1 "><p id="p174824143190"><a name="p174824143190"></a><a name="p174824143190"></a>sudo密码</p>
        </td>
        <td class="cellrowborder" valign="top" width="61.92999999999999%" headers="mcps1.2.3.1.2 "><p id="p1148261416194"><a name="p1148261416194"></a><a name="p1148261416194"></a>设置sudo用户对应的密码，单击<span class="uicontrol" id="uicontrol048281411190"><a name="uicontrol048281411190"></a><a name="uicontrol048281411190"></a>“加密保存”</span>，对密码进行加密保存。</p>
        </td>
        </tr>
        </tbody>
        </table>

    -   方式二：授权脚本执行。

        >![](public_sys-resources/icon-note.gif) **说明：**   
        >-   如果您选择“授权脚本执行“进行主机授权，由于该方式无法将是否已授权的信息传回到VSS，所以虽然主机已完成授权，但“授权信息“状态仍然为“暂未授权“。  
        >-   用户也可以在“主机“页面，单击“扫描授权“，通过授权脚本执行完成主机授权。  

        **图 5**  授权脚本执行<a name="fig17484131491910"></a>  
        ![](figures/授权脚本执行.png "授权脚本执行")

        1.  单击界面上的“复制“，复制开通授权的命令。
        2.  使用远程管理工具（例如：“Xshell“、“SecureCRT“、“PuTTY“），通过弹性IP地址登录到待开通授权的弹性云服务器。

            >![](public_sys-resources/icon-note.gif) **说明：**   
            >也可使用弹性云服务器的“远程登录“功能，登录服务器。  

        3.  执行复制的命令（这里用“SecureCRT“工具登录），结果如[图6](#fig13487814121911)所示，即执行成功。

            **图 6**  执行结果<a name="fig13487814121911"></a>  
            ![](figures/执行结果.png "执行结果")


5.  单击“确定“，完成Linux主机授权。

## 相关操作<a name="section18590144455814"></a>

配置主机授权后，您可以取消主机授权，取消主机授权后，将不能完全扫描出主机的安全风险。有关取消主机授权的详细操作，请参见[取消主机授权](取消主机授权.md)。

