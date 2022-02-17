#微信公众号:搞鸡玩家
#更新时间 2022/2/17

hostname = www.babybooks.top,vip.0818km.cn,vni.kwaiying.com,passport.beva.com,gateway.ergedd.com,api.ggmza.cn,api.rr.tv,musicpay.kuwo.cn, vip1.kuwo.cn, audiobookpay.kuwo.cn, tingshu.kuwo.cn, buy.itunes.apple.com



#汉堡儿童睡前故事（解锁永久VIP）
^https:\/\/www\.babybooks\.top\/v0\/profile url script-response-body https://gjds.vip/QX/pojie/sqgs.js


#二蛋影视（解锁永久VIP）
^http:\/\/vip\.0818km\.cn\/login\/login\/veifys\.html.+ url script-response-body https://gjds.vip/QX/pojie/ed.js


#bigshot（解锁永久VIP）
^https:\/\/vni\.kwaiying\.com\/api\/v1\/user\/profile url script-response-body https://gjds.vip/QX/pojie/bigshot.js

#贝瓦儿歌（解锁永久VIP）
^http:\/\/passport\.beva\.com\/passport\/v1\/sdk\/getuserinfo url script-response-body https://gjds.vip/QX/pojie/bweg.js

#儿歌点点（解锁永久VIP）
^http:\/\/gateway\.ergedd\.com\/dduser\/user\/center\/set url script-response-body https://gjds.vip/QX/pojie/egdd.js


#瑶池lsp（解锁永久VIP）
^http:\/\/api\.ggmza.cn\/api\/user\/info url script-response-body https://gjds.vip/QX/pojie/yaochi.js


#多多视频 永久VIP
^https?:\/\/api\.rr\.tv\/.*?Version url reject
https://api.rr.tv/v3plus/index/channel\?pageNum=1&position=CHANNEL_INDEX url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https?:\/\/api\.rr\.tv\/app\/config\/h5NativeBar url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https?:\/\/api\.rr\.tv\/v3plus\/index\/channel\?pageNum=1&position=CHANNEL_MY url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https:\/\/api\.rr\.tv\/user\/privilege\/list url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https:\/\/api\.rr\.tv\/ad\/getAll url script-response-body https://gjds.vip/QX/pojie/ddsp.js
^https:\/\/api\.rr\.tv\/drama\/app\/get_combined_drama_detail url script-response-body https://gjds.vip/QX/pojie/ddsp.js
https://api.rr.tv/watch/v4 url script-response-body https://gjds.vip/QX/pojie/ddsp.js
https://api.rr.tv/user/profile url script-response-body https://gjds.vip/QX/pojie/ddsp.js

#酷我音乐（可下载 永久VIP 解锁听书看书VIP）
^https?:\/\/audiobookpay\.kuwo\.cn/a\.p url script-response-body https://gjds.vip/QX/pojie/kuwoks.js
^https?:\/\/tingshu\.kuwo\.cn/v2\/api\/user\/ url script-response-body https://gjds.vip/QX/pojie/kuwotingshu.js
^https?:\/\/musicpay\.kuwo\.cn\/music\.pay\?newver=\d url script-request-body https://gjds.vip/QX/pojie/kuwoxz.js
^https?:\/\/vip1\.kuwo\.cn\/(vip\/v2\/user\/vip|vip\/spi/mservice) url script-response-body https://gjds.vip/QX/pojie/kuwohy.js

#视频剪辑大师（解锁永久VIP）
^https:\/\/ajj\.fuguizhukj\.cn\/api\/UserProfile\/BasicUserInfo url script-response-body https://gjds.vip/QX/pojie/spjj.js

#Picsew（解锁付费订阅）
^https:\/\/buy\.itunes\.apple\.com\/verifyReceipt url script-response-body https://gjds.vip/QX/pojie/Picsew.js
