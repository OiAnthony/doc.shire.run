# Lifecycle

Shire 的生命周期是围绕 IDE 与 LLM 生成过程所设计的。Shire 的生命周期包括：

- beforeStreaming: 在 Streaming 开始前对生成的内容进行处理。
- onStreaming：在 Streaming 过程中对生成的内容进行处理。（TBD）
- onStreamingDone：在 Streaming 完成后通过一系列的后处理器对生成的内容进行处理。
- afterStreaming：在 Streaming 完成后，根据条件执行后续操作，诸如执行新的 Shire 指令、调用其它工具等等。
