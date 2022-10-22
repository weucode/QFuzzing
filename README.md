# QFuzzing

## BugList

| No.  | Compiler |     Version      |                             Link                             | Status                         | Contributor                              | Description   |Category                                   |
| :--: | :------: | :--------------: | :----------------------------------------------------------: | ------------------------------ | ---------------------------------------- | ------------------------------------------------ | -------------------|
|  1   |    Q#    | V0.18.2106148911 | [Bug Report1](https://github.com/microsoft/qsharp-runtime/issues/890) | First Found & Verified         | [Xing Qu](https://github.com/QuXing9)    | 包含Qubit类型的operation在Linux系统下执行超时    |  Performance |
|  2   |    Q#    | V0.21.2111177148 | [Bug Report2](https://github.com/microsoft/QuantumLibraries/issues/498) | First Found & Verified & Fixed | [Xing Qu](https://github.com/QuXing9)    | Binom函数在边界参数处执行结果错误                |  Implementation |
|  3   |    Q#    | V0.21.2111177148 | [Bug Report3](https://github.com/microsoft/QuantumLibraries/issues/500) | First Found & Verified & Fixed | [Xing Qu](https://github.com/QuXing9)    | BitSizeI函数在边界参数处执行结果错误             | Implementation |
|  4   |    Q#    | V0.21.2111177148 | [Bug Report4](https://github.com/microsoft/QuantumLibraries/issues/503) | First Found & Verified & Fixed | [Xing Qu](https://github.com/QuXing9)    | IntAsBoolArray函数在边界参数处执行结果错误       |  Implementation |
|  5   |    Q#    | V0.21.2111177148 | [Bug Report5](https://github.com/microsoft/QuantumLibraries/issues/506) | First Found & Verified & Fixed | [Xing Qu](https://github.com/QuXing9)    | ApproximateFactorial函数在边界参数处执行结果错误 | Implementation |
|  6   |    Q#    | V0.21.2111177148 | [Bug Report6](https://github.com/microsoft/QuantumLibraries/issues/505) | First Found & Verified & Fixed | [Xing Qu](https://github.com/QuXing9)    | PNorm&PNormalized函数的API使用文档描述不清晰     |  Specification |
|  7   |    Q#    | V0.21.2111177148 | [Bug Report7](https://github.com/microsoft/QuantumLibraries/issues/512) | First Found & Verified & Fixed | [Xing Qu](https://github.com/QuXing9)    | ExpModI函数在边界参数处执行结果错误              |  Implementation |
|  8   |    Q#    | V0.21.2111177148 | [Bug Report8](https://github.com/microsoft/qsharp-compiler/issues/1353) | First Found & Verified         | [Xing Qu](https://github.com/QuXing9)    | PermuteQubits函数报错信息行错误                  |  Implementation |
|  9   |    Q#    |   v0.23.195983   | [Bug Report9](https://github.com/microsoft/QuantumLibraries/issues/538) | First Found & Verified & Fixed | [Tianmin Hu](https://github.com/weucode) | Chunks函数在边界参数处执行超时                   |   Implementation |
| 10 | Q# | v0.24.201332 | [Bug-Report10](https://github.com/microsoft/QuantumLibraries/issues/554) | First Found & Verified & Fixed | [Xing Qu](https://github.com/QuXing9) | Padded函数使用文档的example示例描述错误 | Specification |
| 11 | Q# | v0.24.201332 | [Bug-Report11](https://github.com/MicrosoftDocs/quantum-docs/issues/525) | First Found & Verified & Fixed | [Tianmin Hu](https://github.com/weucode) | 介绍Q# immutability的网页上描述有误 | Specification |
| 12 | Q# | v0.24.201332 | [Bug-Report12](https://github.com/microsoft/QuantumLibraries/issues/563) | First Found & Verified & Fixed | [Tianmin Hu](https://github.com/weucode) | 标准文档中包含最新的SDK版本已弃用的API | Specification |
| 13 | Q# | v0.24.201332 | [Bug-Report13](https://github.com/microsoft/qsharp-runtime/issues/993) | First Found & Verified | [Xing Qu](https://github.com/QuXing9) | Parity函数未考虑对负数的处理 | Implementation |
| 14 | Q# | v0.21.2111177148 | [Bug-Report14](/docs/bug/bug-14.png) | Verified & Fixed | [Xing Qu](https://github.com/QuXing9) | HalfIntegerBinom函数的API功能错误 | Implementation |
| 15 | Q# | v0.24.201332 | [Bug-Report15](https://github.com/microsoft/QuantumLibraries/issues/570) | First Found & Verified & Fixed | [Tianmin Hu](https://github.com/weucode) | PurifiedMixedStateRequirements函数的两个参数之一为非正数时产生溢出 | Implementation |
| 16 | Q# | v0.24.201332 | [Bug-Report16](https://github.com/microsoft/QuantumLibraries/issues/571) | First Found & Verified & Fixed | [Tianmin Hu](https://github.com/weucode) | ApproximateFactorial 函数的参数范围与文档描述不符 | Specification |
| 17 | Q# | v0.24.201332 | [Bug-Report17](https://github.com/microsoft/qsharp-runtime/issues/990) | Undetermined | [Xing Qu](https://github.com/QuXing9) | AssertQubitWithinTolerance操作代码实现效率低 | Implementation |
| 18 | Q# | v0.25.228311 | [Bug-Report18](https://github.com/microsoft/QuantumLibraries/issues/624) | First Found & Verified | [Tianmin Hu](https://github.com/weucode) | 在Windows和Linux平台下Sin(PI()/4.0)值的小数最后一位数值不同 | Implementation |
