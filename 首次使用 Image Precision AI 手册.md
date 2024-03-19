# 说明
本文档是 Shopify App LitaCat - Image Precision AI 的首次使用演示文档。


| 说明 | 时间 |
| -- | -- |
| 第一版 | 2024-03-19 |

----------------------------------------------------------------

# 首次使用“图片锐化”
这是一个简单的教程，目标是帮助商家首次使用 Image Precision AI 实现图片优化，整个操作过程大概需要约10分钟。完整操作步骤如下，后面会分别解析每个操作的内容。
![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/1c8c0b7b-d868-441a-9a54-3aba233cfd7b)


# 第一步：进入“Enhance Product Images” 页面
点击 Shopify Apps 菜单，找到 Enhance Product Images 的入口，然后点击它。首次进入列表页会像下面的截图一样，提示没有任务。然后点击右上角的 "New Image Enhancement" 或 “Select Images” 进入新增任务页面。
![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/0c2357fc-157d-4c45-83eb-d9db483ac31f)


# 第二步：进入“New Image Enhancement Task”页面
在这个页面，系统会读取所有套餐的图片。
![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/efca9cd4-acd3-4322-9abd-87df544e95d0)

搜索栏支持简单的搜索，“Product” 输入框必须输入完整的产品名称，不支持模糊搜索。例如，输入“Skirt”，然后点击“Search”，很抱歉，搜索不到任何东西。
![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/228bcec7-cbb5-441b-a7e6-c93833b86ae7)

您必须输入完整的产品名称，如“1# Skirt - Image provided by upstream supplier”才能搜索到。这是由于 Shopify 的产品查询功能的限制，我们正在努力优化，希望以后能支持模糊搜索。
![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/6b8fec05-1e71-4ad9-9ba2-829c93b60b08)

# 第三步：确认图片
![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/c23e0149-d284-4434-9188-b42d7a7a6aa7)


弹框分为左右两部分
### 弹框左边
勾选的图片会再次展示出来，供您查看和确认。每张图片右上角有个“x”，点击它可以取消选择。点击图片可以放大查看。
| 功能 | 说明 |
| -- | -- |
| 取消选择 | ![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/ffbdcf3a-328f-482d-9968-570a0a9d04cf) |
| 放大图片 | ![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/15bb8517-3c48-4657-bbc3-2a95b1654f5b) |



### 弹框右边
会让您修改 Title、Image Enhancement Method、Image Zoom、Replace Image 等内容，下面解析这几个字段的作用

| 功能 | 解析 |
| -- | -- |
| Title | 让商家方便区分多个任务，不同的名称不会对任务产生影响 |
| Image Enhancement Method | 如果您的图片是卡通图片，请选择第二个“Cartoon Images Only”，否则使用默认的“General” |
| Image Zoom | 放大倍数，选项有：Auto、No Zoom。Auto 规则如下：图片的最长边在 10 ~ 500 之间放大4倍，在500 ~ 1000之间放大2倍；在 1000 ~ 4096 保持原大小。No Zoom 是不放大 |
| Replace Image | 是否使用 AI 处理过的新照片替换现有的产品图片，默认勾选。如果勾选，在任务完成后，会自动删除套餐的图片，并使用新照片替换。因此建议您每次新增任务时，都点击下方的“Download Selected Images”下载勾选的照片备份，以便在出现问题时使用这些旧照片还原。如果不勾选，则需要在任务详情页下载 AI 生成的新照片，因为我们最多只保留7天。 |
| Balance | 余额 |
| Image Quantity | 图片数量 |
| Cost | 费用 |
| Submit | 提交任务按钮，确认完成后，请点击此按钮 |
| Download Selected Images | 下载已勾选的图片 |
| Wallet Recharge | 跳转至钱包充值页面 |

### 点击 Submit
当您点击“Submit”按钮提交任务时，如果余额不足，会提示您充值。点击“Recharge”跳转至钱包充值页面。充值完成后，请在浏览器中返回此页面，然后直接点击“Close”、“Submit”，无需刷新页面重新选择图片。
![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/50bb39f3-3778-4556-953f-1931addb7a74)


当然，还可能会遇到其他错误，这些错误将以 Toast 形式展示。如果遇到无法解决的问题，请点击右下角的聊天窗口联系我们。

# 第四步：Image Enhancement Records
至此，任务已成功新增，现在任务正在排队执行。在此页面，您可以查看任务的详细信息、执行日志和图片处理结果等。如果任务正在执行中，页面每10秒将自动获取结果。
任务完成后，点击“New Image”的“Download All”即可下载所有 AI 生成的图片。
如果在新增任务时选择了自动替换产品图片，请立即查看产品页面确认图片是否已清晰化。
![image](https://github.com/huangcong12/image_precision_ai_document/assets/2867782/d4b53041-1839-4c73-8fb6-0fc2739e3d02)



# 完成
恭喜您，您已经学会了如何使用 Image Precision AI 优化图片！现在，您可以继续探索其他功能。



# 下一步
TODO


