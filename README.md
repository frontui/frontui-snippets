# FrontUI Snippets
---

FrontUI 代码片段。

## 下载代码片段

- [JetBrains 系列编辑器（WebStorm、IntelliJ IDEA 等） 配置文件 `jar`](http://amazeui.org/download?ver=jetbrainsjar)
- [JetBrains 系列编辑器（WebStorm、IntelliJ IDEA 等） XML 文件](http://amazeui.org/download?ver=jetbrains)
- [Sublime Text](http://amazeui.org/download?ver=sublime)

## 安装

- 现目前还没有添加到官方插件中使用如下：

- **Sublime Text 2/3**：打开 `Preferences > Browse Packages`，在 `Browse Packages` 下创建 `frontui` 目录，把从上面下载的 Sublime 代码片段解压得到的文件复制创建好的 `frontui` 目录下。

- **JetBrains 系列编辑器（WebStorm 等）**：
  - **方式一**：下载 `jar` 文件（上面第一个链接），点击编辑器菜单 `File` -> `Import Settings...`，选择刚才下载的 `jar`，点击 `OK`，编辑器会提示重启，重启以后导入完成。
  - **方式二**：把下载解压得到的 frontui.xml 拷贝到 IDE 配置文件 `templates` 目录下（**如果 `templates` 文件夹不存在，则需要手动创建**），重启编辑器：
    - Windows: `%USERPROFILE%/\.<产品名称><版本号>\config\templates`，例如 WebStorm 9 的模板配置目录为 `%USERPROFILE%/.WebStorm9/config/templates`
    - Linux: `~\.<产品名称><版本号>\config\templates`
    - OS X: `~/Library/Preferences/<产品名称><版本号>/templates`，例如 WebStorm 10 的模板配置目录为 `~/Library/Preferences/WebStorm10/templates`； PHPStorm 9 的路径为 `~/Library/Preferences/WebIde90/templates`

  - **方式三**：打开 `Preferences > Live Templates` 增加 frontui 代码片段，把下载解压得到的 `frontui.xml` 拷贝到 `Live Templates` 你自定义的代码片段下；

## CSS 代码片段目录

### bower

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead><th>组件</th><th>代码片段</th></thead>
  <tbody>
    <tr><td>bower 链接 (both CSS & JS)</td><td>fu-bower</td></tr>
    <tr><td>bower 链接 (CSS only)</td><td>fu-bower:css</td></tr>
    <tr><td>bower 链接 (JS only)</td><td>fu-bower:js</td></tr>
  </tbody>
</table>

### HTML

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead><th>组件</th><th>代码片段</th></thead>
  <tbody>
    <tr><td>HTML5 布局模板</td><td>fu-html</td></tr>
  </tbody>
</table>


### Form 表单

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基础表单</td>
    <td>fu-form</td>
    </tr>
    <tr>
    <td>灰色背景</td>
    <td>fu-form:gray</td>
    </tr>
  </tbody>
</table>

### Table 表格

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基础表格</td>
    <td>fu-table</td>
    </tr>
    <tr>
    <td>反色表格</td>
    <td>fu-table:inverse</td>
    </tr>
  </tbody>
</table>

### Breadcrumb 面包屑导航

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基础面包屑</td>
    <td>fu-breadcrumb</td>
    </tr>
  </tbody>
</table>

### Nav 导航

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-nav</td>
    </tr>
  </tbody>
</table>

### Pagination 分页

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-pagination</td>
    </tr>
    <tr>
    <td>居中对齐</td>
    <td>fu-pagination:center</td>
    </tr>
    <tr>
    <td>右对齐</td>
    <td>fu-pagination:right</td>
    </tr>
    <tr>
    <td>左对齐</td>
    <td>fu-pagination:left</td>
    </tr>
  </tbody>
</table>

### amount 可提金额

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-amount</td>
    </tr>
  </tbody>
</table>

### bankList 个人银行列表

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-bankList</td>
    </tr>
  </tbody>
</table>

### ebanks 支付银行列表

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-ebanks</td>
    </tr>
  </tbody>
</table>

### chart 图表

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-chart</td>
    </tr>
    <tr>
    <td>带title图表</td>
    <td>fu-chart:title</td>
    </tr>
  </tbody>
</table>

### datacount 统计数据

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-datacount</td>
    </tr>
  </tbody>
</table>

### filter 过滤器

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-filter</td>
    </tr>
  </tbody>
</table>

### formtable 表单内表格

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-formtable</td>
    </tr>
  </tbody>
</table>

### input 输入框

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-input</td>
    </tr>
    <tr>
    <td>带弹框icon</td>
    <td>fu-input:modal</td>
    </tr>
    <tr>
    <td>带日期icon</td>
    <td>fu-input:date</td>
    </tr>
    <tr>
    <td>带验证按钮</td>
    <td>fu-input:verify</td>
    </tr>
    <tr>
    <td>带可提取按钮</td>
    <td>fu-input:draw</td>
    </tr>
    <tr>
    <td>小按钮</td>
    <td>fu-input:smallsize</td>
    </tr>
    <tr>
    <td>激活的输入框</td>
    <td>fu-input:active</td>
    </tr>
  </tbody>
</table>

### select 下拉框

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-select</td>
    </tr>
    <tr>
    <td>可输入</td>
    <td>fu-select:input</td>
    </tr>
  </tbody>
</table>

### notice 提示框

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-notice</td>
    </tr>
    <tr>
    <td>成功样式</td>
    <td>fu-notice:success</td>
    </tr>
    <tr>
    <td>信息样式</td>
    <td>fu-notice:info</td>
    </tr>
    <tr>
    <td>错误样式</td>
    <td>fu-notice:error</td>
    </tr>
    <td>等待样式</td>
    <td>fu-notice:waiting</td>
    </tr>
    <tr>
    <td>弹层成功样式</td>
    <td>fu-notice:modal-success</td>
    </tr>
    <tr>
    <td>弹层信息样式</td>
    <td>fu-notice:modal-info</td>
    </tr>
    <tr>
    <td>弹层错误样式</td>
    <td>fu-notice:modal-error</td>
    </tr>
    <td>弹层等待样式</td>
    <td>fu-notice:modal-waiting</td>
    </tr>
  </tbody>
</table>

### pawset 密码设置表格

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-pwdset</td>
    </tr>
  </tbody>
</table>

### step 步骤

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-step</td>
    </tr>
    <tr>
    <td>第一步</td>
    <td>fu-step:pass1</td>
    </tr>
    <tr>
    <td>第二步</td>
    <td>fu-step:pass2</td>
    </tr>
    <tr>
    <td>第三步</td>
    <td>fu-step:pass3</td>
    </tr>
  </tbody>
</table>

## JS 代码片段目录

### Alert 警告框

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-alert</td>
    </tr>
    <tr>
    <td>颜色: success</td>
    <td>fu-alert:success</td>
    </tr>
    <tr>
    <td>颜色: warning</td>
    <td>fu-alert:warning</td>
    </tr>
    <tr>
    <td>颜色: danger</td>
    <td>fu-alert:danger</td>
    </tr>
  </tbody>
</table>

### Modal 模态窗口

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-modal</td>
    </tr>
  </tbody>
</table>


### Tabs 选项卡

<table class="am-table am-table-bordered am-table-striped am-table-hover">
  <thead>
    <tr>
    <th>组件</th>
    <th>代码片段</th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>基本样式</td>
    <td>fu-tab</td>
    </tr>
    <tr>
    <td>带搜索框</td>
    <td>fu-tab:search</td>
    </tr>
    <tr>
    <td>第二种</td>
    <td>fu-tab:type2</td>
    </tr>
  </tbody>
</table>
