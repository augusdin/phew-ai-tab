# Changelog

中文版本的更新日志.

## [alpha-0.2.1] - 2024.7-15

### Added
- [新增] AI 分组和域名分组支持分组后按 Tabs 数量排序，默认为关闭
- [新增] AI 分组后，对分组内的 Tabs 再按照域名进行排序，默认为开启
- [新增] 关闭持续自动分组的选项，关闭自动分组后，点击分组按钮只进行一次分组，默认开启自动分组
- [新增] 删除分组规则，可用于撤回不满意的 AI 分组结果
- [新增] 增加高级用户计划，支持使用 GPT4o 进行分组
- [新增] AI 分组新增"解释"字段，可在 Option 页面查看 AI 分组的理由，提升分组效果。

### Fixed
- 解决 Tab Item 滑动失焦的问题

### Changed
- [优化] Tab Item 高度,使 Tab 高度更紧凑
- [优化] AI 分组效果，提升分组一致性、稳定性及准确性
- [优化] Space 列表中，当前 Space 排列在列表末尾，以便操作
- [变化] 由于目前体验不够理想，暂时暂停页面预览功能，该功能会在下个月以更佳的使用体验回归

## [alpha-0.2.0] - 2024.5-9

### Added
- 

### Fixed
- [修复] 域名分组的问题
- [修复] AI 分组时开启 Emoji 会导致重复分组的问题

### Changed
- [优化] 通过减少 prompt 字数 (只减少描述内容) 来提升 AI 分组速度


## [alpha-0.1.9] - 2024.5-8

### Added
- [新增] 

### Fixed
- [修复] 在 Space 不可用时生成 Space 名称的 bug
- [修复] 切换 Space 时丢失 Pin 的 Tab 的问题

### Changed
- [变更] 

## [alpha-0.1.8] - 2024.5-8

### Added
- [新增] 将主菜单的解除所有分组移到 AI Grouping 按钮的菜单里
- [新增] Space 自动命名时显示 Loading 状态
- [新增] 自定义模型名称 (限Pro 和 LTD 用户)
- [新增] 打乱当前窗口所有 Tab 的快捷键位

### Fixed
- [修复] 

### Changed
- [变更] 将 Space 对话框移到下边
- [变更] 升级支付系统
- [优化] 优化 Space 列表样式，增加辨识度，并显示创建 Space 日期

## [alpha-0.1.7] - 2024.4-29

### Added
- [新增] 新增导出窗口下的 Tabs 信息为 CVS，支持所有类别窗口,包括当前窗口、挂起的窗口、固定的窗口及历史数据
- [新增] 根据 AI 对 Tab 分析的内容，在全局进行搜索
- [新增] Space 自动命名时增加 emoji 以方便辨别
- [新增] 在侧边栏窗口底部显示窗口所属类别 (需要开启 AI 页面分析)

### Fixed
- [修复] 修复切换到新 Space 的问题
- [修复] 修改挂起的 Window 名称
- [修复] 修改固定的 Window 名称
- [修复] 修复 0.1.2 版本引入的更新分组名称无法更新到分组规则的问题
- [修复] 修复 挂起、固定、历史列表删除后容易遗留空 window 窗口的问题
- [修复] 进一步降低分析页面时请求服务端的接口频次
- [修复] 按域名分组频繁提示 Toast 的问题
- [修复] 兼容 Chrome Tab 加载状态偶尔出问题的 bug
- [修复] 开启域名分组时状态设置错误
- [修复] 本地创建默认 Space 时缺少固定的窗口的 bug

### Changed
- [变更] 将收藏更改名为固定，并完整实现固定、删除、修改名称等编辑功能，且支持加密并同步到服务端
- [变更] 默认不开启AI页面分析与预览
- [优化] 优化窗口工具栏 ICON 显示
- [优化] 界面大改版, 精简界面元素
- [更新] 更新到 OpenAI 最新 gpt-3.5-turbo 模型

## [alpha-0.1.6] - 2024.4-29

### Added
- [新增] 快捷键 Ctrl+Shift+C 键关闭当前标签所在分组的所有标签

### Fixed
- [修复] 请求服务端分析接口过于频繁的问题
- [修复] 切换 Space 时可能存在的问题

### Changed
- [优化] 提升多端自动同步的性能

## [alpha-0.1.5] - 2024.4-28

### Added
- [新增] 快捷键 Command+E 切换"展开所有分组" 与 "收起其他分组"分组状态 (Windows 下为Alt+Shift+E)
- [新增] 快捷键 Command+Shift+U 解除当前所有分组 (Windows 下为Ctrl+Shift+U)
- [新增] 快捷键 Ctrl+Shift+N 创建新的 Space
- [新增] 预留展开所有分组位供自行配置快捷键 (Expand all groups)
- [新增] 预留开始AI分组供自行配置快捷键 (Begin AI Grouping)

### Fixed
- 

### Changed
- [优化] 升级"展开所有分组"按钮为切换分组展开状态，即从"展开所有分组" 与 "收起其他分组"之间切换

## [alpha-0.1.4] - 2024-4-27

### Added
- 

### Fixed
-[修复] 兼容旧版分组规则

### Changed
- 

## [alpha-0.1.3] - 2024-4-27

### Added
- [新增] 分组规则的导出和导入(支持旧版本的导出)

### Fixed
-

### Changed
- 

## [alpha-0.1.2] - 2024-4-27

### Added
- [新增] 一键恢复所有魔术挂起的标签
- [新增] Space 管理
- [新增] AES 256军事级加密本地于远程同步数据，保护Space下所有Tab的数据只能由用户本人才能访问。
- [新增] 多端云同步 (Pro、LTD 用户)
- [新增] LTD用户将 Space 数据私有化部署到 Supabase
- [新增] 全新的 Tab 卡片，支持AI 总结打开的页面 (Pro、LTD用户)
- [新增] AI 分组支持 emoji (Pro、LTD 用户)
- [新增] AI 分组支持自定义分类
- [新增] AI 分组自动翻译为浏览器界面语言
- [新增] 根据 AI 总结内容搜索所有当前Space下的 Tab
- [新增] 新建 Space 自动命名 (Pro、LTD 用户)

### Fixed
-

### Changed
- [优化] 提升分组效果
- [优化] 提升页面预览效果，使用服务端截图，彻底避免本地截图带来的各类问题。 (Pro、LTD用户)
- [优化] AI 分组支持二级域名
- [优化] 减少内存占用，提升侧边栏性能。

## [alpha-0.1.1] - 2024-3-15

### Added
- 

### Fixed
- 

### Changed
- 减少不必要的渲染次数，提升侧边栏性能

## [alpha-0.1.0] - 2024-3-8

### Added
- 

### Fixed
- [修复] 线上紧急 bug

### Changed
- 

## [alpha-0.0.9] - 2024-3-8

### Added
- 

### Fixed
- [修复] google 账户登陆问题

### Changed
- [新增] 用户头像自定义，登陆后可以在个人中心更改自己的头像
- [新增] 删除账户，登陆后可以在个人中心删除自己的账户


## [alpha-0.0.8] - 2024-3-8

### Added
- [新增] 上线用户系统, 登陆即可使用插件，无需再输入序列号和API Key
- [新增] Window 窗口按照数量最多的Tab的域名与Title自动重命名 (本版本暂不支持自定义修改，下个版本恢复)
- [新增] 全新“域名合并”功能，会自动将相同的域名的tab移动到一起，并直观展示所属域名
- [新增] 全新“窗口间域名合并”功能，如果打开的域名已经在其他窗口中存在，则会自动合并到那个窗口中(付费会员功能)

### Fixed
- [修复] 修复 window 面板展开问题
- [修复] 列表卡顿，内存占用大的问题
- [修复] 持续分组 Switch 无法开启或关闭的问题

### Changed
- 全新的魔术挂起tab展示形式，现在魔术挂起的页面展示更为清晰直观。
- 魔术挂起默认开启(付费会员功能)，间隔时间为24小时
- 点击搜索结果后，返回主界面
- 默认收起当前 window 以外的其他 window, 操作一次后会记住展开收起操作
- 暂时默认不开启页面截图预览功能(下一版本将全面修复)

## [alpha-0.0.7] - 2023-1-15

### Added
- 

### Fixed
- [修复] 预览功能失效的问题(安装插件前已打开的页面需要刷新才能出现预览截图)
- [修复] sidepanel tab 卡顿问题 (0.0.6引入问题)
- [修复] 某些情况下自动魔术挂起失效问题
- [修复] sidepanel tab与浏览器tab顺序不一致问题
- [修复] 自动滚动的一些判断问题

### Changed
-

## [alpha-0.0.6] - 2023-1-15

### Added
- [新增] 页面截图预览功能，鼠标移动到侧边栏标签图标会弹出这个标签的页面截图预览(pro版本功能，已知youtube等一些站点截图不正常，后续修复)
- [新增] 魔术挂起功能：将tab或窗口关闭并保存在侧边栏里，点击挂起的标签即可还原到原始位置，至此浏览器标签不在受电脑内存限制，挂起的标签在重新打开浏览器后依然有效，魔术挂起功能替代原先的窗口缓存功能
- [新增] 自动魔术挂起，可设置自动挂起间隔，默认为30分钟(pro版本功能)
- [新增] 魔术挂起白名单，支持通过url、域名和正则表达式指定永远不挂起的页面，也可以在窗口选项中将当前页url添加到白名单中(pro版本功能)
- [新增] 侧边栏自动滚动到当前页面的tab(默认项，可在选项中关闭)
- [新增] 自动收起当前tab所在分组之外的分组(非默认项，需要在选项中开启)
- [新增] Tab 悬停和选择显示地址
- [新增] 分组操作按钮，可以更改分组颜色、解散分组、关闭分组内窗口、移动分组到新窗口以及其他操作
- [新增] 当前窗口外增加最后访问时间显示

### Fixed
- [修复] OpenAI返回格式错误导致分组规则配置面板搜索白屏
- [修复] 分组颜色很容易出现重复的问题

### Changed
- Tab默认不显示url
- 分组前自动排序改为非默认项，需要在选项中开启
- 提升AI分组准确度
- [优化] 提升侧边栏交互逻辑
- [优化] 优化侧边栏显示样式
- [优化] 大幅提升分组速度

## [alpha-0.0.5] - 2023-12-27

### Added
- 新增兼容 Great Suspender 类插件挂起的tab
- 新增窗口下按字母排序
- 新增Command+Shift+P(Windows下为Ctrl+Shift+P) 快捷键唤出和关闭侧面版
- 新增改变面板位置选项
- 新增cohesive分组显示样式，并更换为默认样式，可在选项中切换回旧tag样式(更醒目)
- 新增OpenAI Promxy URL 配置
- 新增AI分组规则可视化编辑器
- 新增标签url显示，并作为默认想，可在选项中设置为不显示

### Fixed
- 修复插件分组功能对pinned标签的影响
- 修复自动分组在某些情况下失效的问题
- 修复拖动时的样式问题
- 修复拖动后变成多选的问题
- 修复挂起、收藏、历史窗口内无法搜索的问题
- 修复搜索框准确性和搜索性能低及其他体验性的问题 (搜索功能现在十分强大, 远超浏览器自带)
- [严重]修复重复分组规则不断累加导致分组规则混乱的问题

### Changed
- 优化tab图标的显示
- 优化点击响应性能
- 大幅提升侧边栏性能
- 开启AI分组默认自动开启自动分组

## [alpha-0.0.4] - 2023-12-25

### Added
-

### Fixed
- 修复tabs大于一定数量(如100)时，导致分组容易超时的问题
- 修复分组大小写不同识别为不同分组问题
- 修复自动分组不生效问题

### Changed
- 优化OpenAI请求算法，减少请求内容，提升分组速度与分组效果
- 重写AI分组规则，按照60个有效tabs进行分批请求
- 内部默认分组规则会显示在设置面板，可自行修改 
- 优化侧边栏右侧分组颜色条，更易于识别


## [alpha-0.0.3] - 2023-12-18

### Added
- 

### Added
- 

### Fixed
- 修复AI分组与Chrome浏览器语言不符问题(使用chrome浏览器的UI默认语言)
- 修复AI分组规则缓存失效导致频繁请求OpenAI的问题
- 修复分组时会错误处理 chrome:// 页面的问题

### Changed
- 增加一些分组类别，以提升AI分组效果
- 改进自动分组模式下的AI持续分组算法
- AI分组前对Tabs进行排序

## [alpha-0.0.2] - 2023-12-17

### Changed
- 

### Added
- 新增按域名排序
- 新增按域名分组
- 新增点击更改窗口名称
- 新增点击更改分组名(自动更改规则)
- 新增窗口和group下的tab数量统计

### Fixed
- 修复破坏某些页面样式及升级弹窗无法弹出问题
- 修复不同步tab顺序变化的问题
- 部分解决开启自动分组后不生效的问题(但目前依然有不同窗口状态相互影响的问题)

### Changed
- 