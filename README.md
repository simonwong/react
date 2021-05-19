# React 源码攻略

## 概念

- Scheduler（调度器）—— 调度任务的优先级，高优任务优先进入Reconciler
- Reconciler（协调器）—— 负责找出变化的组件
- Renderer（渲染器）—— 负责将变化的组件渲染到页面上

## 包分析

### fixtures

React 测试项目

### scripts

工具脚本

### packages

#### 核心公共包

- **react** （react 核心
- **react-reconciler** （react 协调器
- **scheduler** （调度器
- shared （公共的方法、全局常量

#### Renderer 渲染器

- **react-dom** （react 在 web 端的 renderer
- react-art
- react-native-renderer
- react-noop-renderer
- react-test-renderer

#### 辅助包

- react-is （用于测试组件是否是某类型
- react-client （创建自定义的流
- react-fetch （用于数据请求
- react-refresh （热重载的React官方实现

#### 实验性的包

- react-server （创建自定义SSR流
- react-client （创建自定义的流
- react-fetch （用于数据请求
- react-interactions （用于测试交互相关的内部特性，比如React的事件模型
- react-reconciler （Reconciler的实现，你可以用他构建自己的Renderer
