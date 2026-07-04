### Hi, I'm Pablo

I'm a CS student at the University of Florida and I work in applied AI.
Right now I'm doing an AI engineering internship at Handtevy, building
document intelligence pipelines for emergency medicine software used by
200,000+ clinicians nationwide, and contributing to open source projects
like docling, vLLM, SGLang, and the MCP SDKs.

I'm also a classical pianist. I run Accordo, a booking and payments
marketplace for musicians, and I'm building
[Gradus ad Parnassum](https://github.com/pablopupo/gradus-ad-parnassum),
which reads sheet music and answers a musician's questions about it.

### Open source

Merged:

- [docling #3702](https://github.com/docling-project/docling/pull/3702) - optional-dependency imports that broke the core converter in slim installs
- [docling #3721](https://github.com/docling-project/docling/pull/3721) - code language detection for parsed code blocks

In review:

- [vllm #47439](https://github.com/vllm-project/vllm/pull/47439) - response_format was silently suppressing tool calls when tool_choice is auto
- [sglang #29952](https://github.com/sgl-project/sglang/pull/29952) - msgpack round-trip for customized_info, removing the pickle wrap
- [typescript-sdk #2418](https://github.com/modelcontextprotocol/typescript-sdk/pull/2418) - double onerror on transport close, ported to v2
- [docling #3722](https://github.com/docling-project/docling/pull/3722) - new Box Notes backend, with [docling-core #668](https://github.com/docling-project/docling-core/pull/668) and [docling-mcp #104](https://github.com/docling-project/docling-mcp/pull/104) alongside

### Projects

- [kit-ai](https://github.com/pablopupo/kit-ai) - offline-first emergency first-aid PWA I built with my hackathon team. Llama 3.2 runs on-device through WebLLM and WebGPU. My pieces were the IndexedDB retrieval layer, the online/offline TTS fallback, and a fine-tuned Llama 3 medical model that I'm now working to ship in the app.
- Accordo - live marketplace for musicians: booking, contracts, payments.

