# E_Controller 模块文档

`E_Controller` 模块用于管理 Actor 的动画状态，包含状态切换、获取当前状态等功能。
## 运行环境
 客户端 服务端

### `E_Controller:new(Actor)`
- **参数**: 
  - `Actor`: 需要控制的对象
- **返回值**: 一个新的 `E_Controller` 对象

### `E_Controller:ChangeState(NewState, layer, total, offset)`
- **参数**:
  - `NewState`: 新的动画状态
  - `layer` (可选): 动画层，默认 0
  - `total` (可选): 动画过渡时间，默认 0.2
  - `offset` (可选): 动画偏移，默认 0
- **返回值**: 无

### `E_Controller:GetState()`
- **参数**: 无
- **返回值**: 当前动画状态 (`self.State`)

### `E_Controller:GetStuck()`
- **参数**: 无
- **返回值**: 是否卡住 (`self.Stuck`)

### `E_Controller:SetStuck(value)`
- **参数**:
  - `value`: 布尔值，表示是否卡住
- **返回值**: 无

