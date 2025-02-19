## 0.1.29
- 更新 compileSdkVersion 到28

## 0.1.28
-  解决多个地方使用时选择内容为第一次打开的那个内容, 去除缓存

## 0.1.27
- 解决 `getAreaResultByCode` 中. 错误赋值导致的bug. #65

## 0.1.26
- 暴露utils函数接口. 提供 `getAreaResultByCode` 方法
## 0.1.25
- 更新文档, hotTags => hotCities

## 0.1.24
- 解决ios风格的城市选择器, 在自定义顶部按钮状态下的文字溢出问题
- 为字母定位城市选择器, 增加属性 **hotCities (List<HotCity>)**
## 0.1.23
- 解决ios风格模拟器. 在某些主题色下, 无法正常显示数据的问题

## 0.1.22
- 更新最新的城市数据.

## 0.1.21
- 解决字母级城市选择器, 无法自定义城市数据的问题

## 0.1.20
- showCityPicker增加isSort属性. 将省份数据是否排序做配置

## 0.1.19
- 处理代码规范问题
## 0.1.18
- 解决ios风格城市选择器字体无法自定义的问题
- 开放ios风格城市选择器, 头部按钮可能会随主题色显示不出的问题, 支持用户自定义头部按钮

## 0.1.17
- 暴露城市与省份数据到CityPickers上

## 0.1.16
- 增加 **showCitiesSelector** 函数方法, 城市级选择器. 支持右侧拼音首字母定位
## 0.1.15
- 解决使用非标准数据源, 导致的省份数据报错的问题
## 0.1.14
- 解决用户给出的location不正确, 导致的报错
## 0.1.13
- 更新文档
## 0.1.12
- 解决自定义数据源, 报错的问题
- 加入自定义数据源的Example配置
## 0.1.10
- 优化当市级无选项时的显示逻辑
## 0.1.9
- 修复 https://github.com/hanxu317317/city_pickers/issues/5 初始化child为空的Point时，会报错

## 0.1.3
- 更新readme中的效果图
## 0.1.2
- 加入省市县三级全屏效果
- 更新文档介绍
- 完善ios选择器的参数

## 0.0.1

* 加入三级联动
- 支持配置高度
- 支持初始化地理位置
