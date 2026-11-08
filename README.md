# Skybound Adventure Online v2 — 10 关双人合作

## 新功能
- 10 关，难度逐渐提升；第 3、6、9 关有 Boss，需要跳到 Boss 头上多次才能过关。
- 道具：蓝色 ◆ 护盾（抵挡一次伤害）；紫色 ⇧ 二段跳（空中再跳一次）；红色 ♥ 生命（最多 5）。
- 合作救援：生命耗尽后倒地，队友靠近 110 像素内按住 E（手机按“救援”）可救活，恢复 1 条生命。两人都倒地才游戏结束。
- 修复悬崖边缘：只要角色身体与陆地有任何正宽度重叠，就能站立，不再要求双脚都在地面。

## 更新现有 GitHub / Render
1. 解压 ZIP，将 `server.js`、`client.js`、`index.html`、`package.json`、`README.md` 五个文件上传到原 GitHub 仓库根目录，覆盖旧文件。
2. GitHub 提交 Commit changes；Render 自动重新部署。
3. 等 Render 显示 Live，两个玩家都刷新游戏网页，重新创建房间并加入。

## 本地运行
Node.js 18+；在项目文件夹运行 `npm install` 和 `npm start`，浏览器访问 http://localhost:3000。

注意：房间保存在服务器内存中，Render 免费实例休眠/重启会清除房间。游戏服务器权威同步位置、道具、Boss 和关卡。
