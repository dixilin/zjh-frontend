## 炸金花(三张牌)小游戏前端

ice.js + react + socket.io

后端源码地址：https://github.com/dixilin/zjh-backend

线上地址：http://81.68.107.230:5678

### 游戏规则

支持开设多房间，支持最多 8 人同房竞技。首轮无法比牌，必须下注或弃牌。未看牌最大下注为 5 倍，已看牌最大下注为 10 倍（可自行调整）。
炸弹（豹子）> 顺金（同花顺）> 同花 > 顺子 > 对子 > 单牌；不比花色，只比牌大小，若都相同，谁开牌谁输。(235 > 炸弹，概率太小遂不做处理，可自行添加该逻辑)
