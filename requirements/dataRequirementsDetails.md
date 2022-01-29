## 访问
### 流量指标
说明: 
1. PV > UV > IP
2. 重复访问者数量 < UV 
3. 频次（人均） = PV / UV
数据字段：
- PV
- UV 
- IP 
- 重复访问者数量 
- 每个访问者的页面浏览数 频次（人均）

### 用户行为指标
- 跳出率 10% ~ 90%
- 平均访问时长 100 ~ 1000s
- 平均访问页数 1 ~ 10
### 用户浏览方式指标
- 用户上网设备类型。
  1. PC 
  2. Mobile
  3. other 
- 用户所使用浏览器
  1. chrome 
  2. safari 
  3. firefox
  4. other
- 用户所使用计算机的分辨率显示模式。
 1. 1920x1080 
 2. 1440x900 
 3. 2560x1440
 4. 1536x864 
 5. 1366x768
 6. 2560x1080
 7. other
- 用户所使用的操作系统名称和版本。 
1. iOS
2. Android
3. MacOS
4. Windows
5. other
- 用户所在地理区域分布状况等。(单独拉出来)

## 性能
说明： 性能指标 1-3 代表三个等级，可以根据这个范围去生成数据，分数对应着去随机生成就行了，不是重点
1. First Contentful Paint (FCP) 
   1. 0-1.8s 100～70
   2. 1.8-3 70～40
   3. 3+ 40～1
2. Speed Index(SI)
   1. 0-0.34s 100～70
   2. 3.4-5.8 70～40
   3. 5.8+ 40～1
3. Largest Contentful Paint (LCP).
   1. 0-2.5s 100～70
   2. 2.5-4s 70～40
   3. 4+s 40～1
4. Time to Interactive (TTI).
   4. 0-3.8s 100～70
   5. 3.9-7.3 70～40
   6. 7.3+ 40～1
5. Total Blocking Time (TBT)
   1. 0-200ms 100～70
   2. 200-600ms 70～40
   3. 600+ 40～1
6. Cumulative Layout Shift(CLS).
   1. 0-0.1 100～80
   2. 0.1-0.25
   3. 0.25+
### 性能得分计算方式
总得分 = FCP * 0.1 + SI * 0.1 +  LCP * 0.25 + TTI * 0.1 + TBT * 0.3 + CLS + 0.15

## 错误
### 错误数据类型
- SyntaxError:语法错误。 
- TypeError:类型错误。 
- RangeError:范围错误。 
- ReferenceError:引用错误。 
- EvalError: eval 错误。 
- URIError: URL 错误。 
- Failed to load resource:资源加载错误。
