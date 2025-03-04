# Summary

- [关于 pracitce.rs](why-exercise.md)
- [值得学习的小型项目](elegant-code-base.md)
- [变量绑定与解构](variables.md)
- [基本类型](basic-types/intro.md)
  - [数值类型](basic-types/numbers.md)
  - [字符、布尔、单元类型](basic-types/char-bool-unit.md)
  - [语句与表达式](basic-types/statements-expressions.md)
  - [函数](basic-types/functions.md)
- [所有权和借用](ownership/intro.md)
  - [所有权](ownership/ownership.md)
  - [引用和借用](ownership/borrowing.md)
- [复合类型](compound-types/intro.md)
  - [字符串](compound-types/string.md)
  - [数组](compound-types/array.md)
  - [切片](compound-types/slice.md)
  - [元组](compound-types/tuple.md)
  - [结构体](compound-types/struct.md)
  - [枚举](compound-types/enum.md)
- [流程控制](flow-control.md)
- [模式匹配](pattern-match/intro.md)
  - [match, matches! 和 if let](pattern-match/match-iflet.md)
  - [模式](pattern-match/patterns.md)
- [方法和关联函数](method.md)
- [泛型和特征](generics-traits/intro.md)
  - [泛型](generics-traits/generics.md)
  - [Const 泛型](generics-traits/const-generics.md)
  - [特征 Traits](generics-traits/traits.md)
  - [特征对象](generics-traits/trait-object.md)
  - [进一步深入特征](generics-traits/advanced-traits.md)
- [集合类型](collections/intro.md)
  - [动态字符串 String](collections/String.md)
  - [动态数组 Vector](collections/vector.md)
  - [KV 存储 HashMap](collections/hashmap.md)
- [类型转换](type-conversions/intro.md)
  - [as](type-conversions/as.md)
  - [From/Into](type-conversions/from-into.md)
  - [其它转换](type-conversions/others.md)
- [返回值和 panic!](result-panic/intro.md)
  - [panic! 深入剖析](result-panic/panic.md)
  - [返回值result 和 ?](result-panic/result.md)
- [包和模块](crate-module/intro.md)
  - [包 Crate](crate-module/crate.md)
  - [模块 Module](crate-module/module.md)
  - [使用use引入模块及受限可见性](crate-module/use-pub.md)
- [注释和文档 todo](comments-docs.md)
- [格式化输出 todo](formatted-output.md)
- [生命周期 todo](lifetime/intro.md)
  - [生命周期基础](lifetime/basic.md)
  - [&'static 和 T: 'static](lifetime/static.md)
  - [深入生命周期](lifetime/advance.md)
- [函数式编程: 闭包、迭代器 todo](functional-programing/intro.md)
  - [闭包 Closure](functional-programing/cloure.md)
  - [迭代器 Iterator](functional-programing/iterator.md)
- [newtype 和 Sized todo](newtype-sized.md)
- [智能指针 todo](smart-pointers/intro.md)
  - [Box](smart-pointers/box.md)
  - [Deref](smart-pointers/deref.md)
  - [Drop](smart-pointers/drop.md)
  - [Rc and Arc](smart-pointers/rc-arc.md)
  - [Cell and RefCell](smart-pointers/cell-refcell.md)
- [Weak 和循环引用todo](weak.md)
- [自引用 todo](self-referential.md)
- [多线程 todo](threads/intro.md)
  - [多线程基础](threads/basic-using.md)
  - [消息传递](threads/message-passing.md)
  - [线程同步：锁、Condvar和信号量](threads/sync.md)
  - [线程同步：Atomic](threads/atomic.md)
  - [Send 和 Sync](threads/send-sync.md)
- [全局变量 todo](global-variables.md)
- [错误处理 todo](errors.md)
- [Unsafe doing](unsafe/intro.md)
  - [内联汇编](unsafe/inline-asm.md)
- [macro 宏 todo](macro.md)
- [测试 todo](tests/intro.md)
  - [编写测试及控制执行](tests/write-tests.md)
  - [基准性能测试 Benchmark](tests/benchmark.md)
  - [单元测试及集成测试](tests/unit-integration.md)
  - [断言 Assertions](tests/assertions.md)
- [Async/Await 异步编程 todo](async/intro.md)
  - [async 和 await!](async/async-await.md)
  - [Future](async/future.md)
  - [Pin 和 Unpin](async/pin-unpin.md)
  - [Stream 流处理](async/stream.md)
