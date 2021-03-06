# 离线缓存

通过前面章节对 PWA 概念的了解，我们知道，离线缓存是 PWA 应用在体验提升上的一个重要特性，离线缓存特性能够使得 PWA 应用在离线环境下可以正常使用，在弱网环境下能够使站点快速响应。通常 PWA 的离线缓存特性主要是依赖 Web 提供的 Service Worker 机制和 Cache API 来配合实现的，并且可以在 Service Worker 文件中通过开发一系列的策略来管理网络策略。当然，这些工作比较复杂繁琐，尤其是在大型的 Web App 上，也可以借助开源的 Service Worker 工具库 Workbox 来辅助完成这些事情。

在本章将详细的介绍 PWA 离线缓存相关的概念和技术细节，如 Service Worker 缓存管理、缓存相关 API 等，并通过相关技术点的配合来实现离线缓存策略，最终会看到实际 Web App 项目中是如何高效的开发和维护离线缓存功能。

