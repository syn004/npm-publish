# npm 是 JavaScript 世界的包管理工具,并且是 Node.js 平台的默认包管理工具

# 目前是web2.0工程化时代，难免离不开npm的各种依赖，用着别人的npm包爽炸天，自己也想发布一次，所以markdow一次npm包发布的过程，方便以后发布包。

# 假如我们没有npm发布账号,请登录 ‘https://www.npmjs.com/’ 进行账户注册。

# 如demo文件夹里面是一个将要发布的 '包'。请按以下步骤:

# npm adduser  添加npm的账户名、密码和邮箱

# npm login 登陆自己的账户

# npm publish 推送自己的包(注意: 推送的时候务必保证在当前包里运行)

# 推送成功的话,证明包没问题。推送失败的原因大部分都是包的名字已经存在了,更换下名字就ok了。

# 更新版本号,执行 npm version patch（patch：小版本号，minor：次版本号，major：主版本号）

# 执行npm publish进行更新

# 删除发布过的包,使用npm unpublish 项目名字@版本

# 以后可以开发自己的包包啦～～
