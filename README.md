<?xml version="1.0" encoding="GB2312" standalone="yes" ?>

<root desc="服务器列表" ver="1">

    <global>
        <data type="include" name="wtypes.h" desc="" />
        <data type="include" name="GlobalDefs.h" desc="公用函数" />
        <data type="include" name="ClassInfo.h" desc="类自生成所需" />
        <data type="includestd" name="string" desc="" />
        <data type="using" name="std::string" desc="使用std中的名字string" />
    </global>
    <class classfile="GameServerList.h" name="GameServerList" desc="">
        <group name="ServerList" desc="">
            <data type="vector" eref="string" name="m_ServerInfo" value="" desc="登录服务器列表">
            </data>
        </group>
        <group name="website" desc="网站">
            <data type="string" name="m_AreaID" value="" desc="区ID(资源文件夹名)" />
            <data type="string" name="m_GroupResDir" value="" desc="子文件夹(可以为空)" />
            <data type="string" name="m_MiniClientUrl" value="" desc="微端网址" />
            <data type="string" name="m_GameWebsite" value="" desc="游戏主页" />
            <data type="string" name="m_PayMoneyUrl" value="http://pay.hzyotoy.com./index.do" desc="元宝充值" />
            <data type="string" name="m_ContactUsUrl" value="" desc="联系客服" />
            <data type="string" name="m_RegisterUrl" value="" desc="注册账户" />
            <data type="string" name="m_ChgePswdUrl" value="" desc="修改密码" />
            <data type="string" name="m_FindPswdUrl" value="" desc="找回密码" />
            <data type="string" name="m_DownloadUrl" value="" desc="下载游戏" />
        </group>
    </class>
    
</root>
