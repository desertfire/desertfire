## Bin Bao · Tech Lead, PyTorch Compiler

I created **AOTInductor**, PyTorch's ahead-of-time compiler for deploying models without Python, and I'm the tech lead behind it. For five years I've worked on the layers that turn PyTorch programs into fast, deployable code. That runs from getting TorchInductor ready for PyTorch 2.0 to bringing these technologies into production at Meta.

**[desertfire.github.io](https://desertfire.github.io)** · [LinkedIn](https://www.linkedin.com/in/bin-bao-9b095812/)

**840+** PRs landed in PyTorch · **1,300+** code reviews · **Creator** of AOTInductor

### Signature work

- **AOTInductor: deploy PyTorch without Python.** Compiles an exported model into a self-contained artifact behind a stable C ABI, servable from C++ and portable across GPU architectures and PyTorch releases. Widely adopted for production deployment, replacing earlier generations of native deployment solutions. [PRs](https://github.com/pytorch/pytorch/pulls?q=is%3Apr+author%3Adesertfire+label%3AMerged+AOTI)
- **TorchInductor: from prototype to PyTorch 2.0.** Worked across the compiler while it was still a prototype, and built the quality bar it shipped against: model-suite CI, accuracy checks, core test suites under Inductor, and the nightly PT2 performance dashboard. [PRs](https://github.com/pytorch/torchdynamo/pulls?q=is%3Apr+author%3Adesertfire)
- **Taking the host out of the hot path.** Inductor's C++ wrapper as a first-class JIT and AOT mode, lazy kernel compilation for faster cold starts, and now CUDA Graphs and regional compilation for large models. [PRs](https://github.com/pytorch/pytorch/pulls?q=is%3Apr+author%3Adesertfire+label%3AMerged+wrapper)

### Leadership

Tech lead for AOTInductor and Inductor's C++ wrapper, leading the PyTorch engineers building them in open source. I now lead a larger team driving production adoption of these technologies at Meta.
