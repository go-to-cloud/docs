
# 用户管理

> 阅读时间大约需要1分钟

## 新建用户

![新建用户](/assets/authz_users_new.png)

:::details 角色
内置四个角色: `root`, `运维(ops)`, `研发(dev)`, `游客(guest)`，权限依次减少
:::

:::tip 多个角色
用户可以拥有多个角色，但建议为一个用户只配置角色
:::

## 用户管理

![用户列表](/assets/authz_users_list.png)

> 用户列表中可以管理所有用户，包括删除、重置密码以及配置用户所属组织

![所属组织](/assets/authz_users_belongs.png)

:::info
`组织管理`窗口左侧为当前用户未归属的有组织列表，选中后移入右侧列表并点击`更新`即可将当前用户归入这批组织
:::

## 重置密码

> 用户忘记密码无法登录时，可以帮助用户重置密码

:::info 
重置后系统会自动生成一串强密码并覆盖旧密码，推荐管理员将新的密码通过`邮件`等等方式告之用户
:::

![img.png](/assets/authz_users_resetpwd.png)
