## 简介
- 微信云支付智能 POS App 已经上架到商米、百富、世麦智能、旺 POS、星 POS 的应用商店，App 的全称为**微信云支付**，请商户自行搜索下载使用。
- 微信云支付智能 POS App 提供登入、收银、小票打印、语音播报、交易明细、交易汇总、交接班和会员卡充值等功能。

## 配置商户及设备
使用微信云支付智能 POS App 之前，需要进行商户及设备的配置。
>!此步骤仅商户管理员可以操作。

### 创建设备
1. 进入腾讯云支付微信公众号，选择【管理后台】>【商户后台】。
2. 选择相应的商户及门店，添加相关设备，填写对应的设备名称，并选择设备类型为【智能POS】。
![](https://main.qcloudimg.com/raw/512c82a23855d1613a49a28d77b06182.png)

>!设备类型一定要选【智能POS】，否则后续智能 POS 配置会失败。

### 生成配置二维码
新建设备后，在设备列表中选择刚创建的设备进入设备详情页面，此时页面出现【配置设备】，单击【配置设备】即可生成配置二维码，如下图所示：
![](https://main.qcloudimg.com/raw/1b9799d52f0fd587fff239c14015ffd3.png)
![](https://main.qcloudimg.com/raw/5f7a98a74b75de3cbfce8abca368bcff.png)

>!此二维码涉及商户信息，请注意保密。

### 配置扫码
在首次进入微信云支付智能 POS App 时，单击【扫描配置二维码】，扫描之前生成的配置二维码，即可完成商户配置及设备绑定，如下图所示：
![](https://main.qcloudimg.com/raw/1bc3b47ee9173e501d1809e6f22c1ec8.png)

## 登录
支持微信扫码登录和账户密码登录，店员可使用自身的员工 ID 和密码进行登录，如下图所示：
![](https://main.qcloudimg.com/raw/9182ae4113ac23546c4023eba94e6aa7.png)

## 收银
支持微信支付、支付宝及会员卡等支付方式，收银页面如下图所示：
![](https://main.qcloudimg.com/raw/7f4875d39a36687cd941bd17a4b17a1b.png)

## 交易明细
- 交易明细页面可以查询当前员工在本设备的交易数据，包括支付单和退款单。
- 订单详情里可以对该订单进行退款和打印小票。
- 单击交易明细页面右上角可以进入订单操作页面，在订单操作页面可以输入订单号查询某个订单，或者直接单击【扫码查询】扫码订单条码进行查询。
![](https://main.qcloudimg.com/raw/aacb7d9328086b042e79a3dfc4cd9e92.png)

## 交易汇总
选择功能列表中的【交易汇总】即可使用该功能。在交易汇总中可以查询某个员工在某个时间段的交易汇总数据，如下图所示：
![](https://main.qcloudimg.com/raw/1bf467ca1771630f6e9d02c454e9a4c3.png)

>?
>- 管理员或者店长可以查看所有员工在该台设备上的汇总数据。
>- 店员只能查看自身订单汇总数据。
>- 在交易汇总中，可以通过选择开关某个汇总项的【是否打印】选项，来决定是否打印该汇总项。

## 会员管理
进入【其他】页面，选择功能列表中的【会员管理】即可使用该功能。在会员管理可以查询某个会员的会员卡信息，同时也可以对其进行充值操作，如下图所示：
![](https://main.qcloudimg.com/raw/81b7e0ea6766e54a141ed6ead60c5446.png)
![](https://main.qcloudimg.com/raw/7f36ce6397967aced6557819d2dacba6.png)

## 会员充值
进入【其他】页面，选择功能列表中的【会员充值】即可使用该功能。会员充值可以通过直接扫付款码为会员进行充值。
![](https://main.qcloudimg.com/raw/95c2cbc2441617bd416947f0016d97ea.png)

>?在该功能中，只能给付款人的会员卡充值。

## 交接班
交接班提供交班和交接班记录两个功能。其中，交接班页面店员可以看到从上班开始至当前的交易汇总数据；交班记录页面可查看某时间段内该设备的交班记录。如下图所示：
![](https://main.qcloudimg.com/raw/79ca1f6d8276f6e9c402e28857d8ed9f.png)
![](https://main.qcloudimg.com/raw/1353684449051bea264d176fd97f9c66.png)
在交接班中，可以通过选择开关某个汇总项的【是否打印】选项，来决定是否打印该汇总项。

## 设置
选择功能列表中的【设置】即可使用该功能。其主要功能如下所示：
![](https://main.qcloudimg.com/raw/cc2f993545712ce6d9223a70cf727800.png)

## 解绑设备
解绑设备功能目前仅由商户管理员可见。在【其他】页面中单击【解绑设备】，即可解绑该设备。**解绑设备后，该设备不再能进行交易，请谨慎使用此功能。**
如果再次启用设备，可以继续通过之前的“配置商户及设备”流程，重新绑定设备即可。

## 重置密钥
重置密钥功能目前仅由商户管理员可见。在【其他】页面中的单击【重置密钥】，即可清空原有密钥。
如果再次配置密钥，可以继续通过之前的“配置商户及设备”流程，重新绑定设备即可。
>!重置密钥时，绑定的设备要与原来的设备保持一致，否则无法进行绑定。
