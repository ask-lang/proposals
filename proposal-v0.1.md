# Ask-lite v0.1 Proposal

Ask! is a framework to write wasm smart contracts, written by assemblyscript, like ink!, maintained by patract.

But as far as I know patract doesn't maintain it anymore, so I contacted a former patract member who is also one of the core developers of Ask! to continue maintaining a redesigned version, called Ask-lite, which you can think of as a successor to Ask!.

## Design

## Development plan

- ask-lite v0.1 (10 weeks)

- ask-lite v0.2 (TBD)

## Development timeline (10 weeks，21 Mar ~ 27 May)

- Week 1~2 (3 developers)

  1. 追踪最新的pallet-contracts和ink!代码，引入host functions

  2. 重新设计与实现基本的合约语法，改进 ask 架构，使用一次编译的方式而不是多次编译

- Week 3~4 (3 developers)

  1. 引入更通用的编码框架[serde-as](https://github.com/yjhmelody/serde-as)和基于 serde-as 的SCALE编码库，适配到合约框架中

  2. 设计好类似于 ink! 的各个组件的接口(interfaces)

- Week 5~6 (3 developers)

  1. 参考 ink! 的存储抽象，定义类似的 PackedLayout/SpreadLayout 接口。

  2. 把编码逻辑结合到新的装饰器语法中

  3. 为编译阶段增加类型分析阶段， 这用于 metadata.json(兼容ink! metadata) 的生成逻辑。

- Week 7~8 (3 developers)

  1. 设计与实现 Event 语法，并兼容ink!
  2. 为密码学原语提供合适的抽象
  3. 为 env function 提供更良好的抽象

- Week 9~10 (3 developers)

  1. 实现一些常用的存储数据结构，比如Array/Mapping， 这类似于 ink! 。
  2. 提供一些合约示例和文档, 例如 flipper/ERC20。

## Cost

## Verification
