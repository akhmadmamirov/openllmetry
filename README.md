<p align="center">
<a href="https://www.traceloop.com/">
<img width="300" src="https://raw.githubusercontent.com/traceloop/openllmetry/main/img/logo.png">
</a>
</p>
<h1 align="center">Open LLMetry</h1>
<p align="center">
  <p align="center">Open-source observability for your LLM application</p>
</p>
<h4 align="center">
    <a href="https://traceloop.com/docs/python-sdk/getting-started"><strong>Get started »</strong></a>
    <br />
    <br />
  <a href="https://join.slack.com/t/traceloopcommunity/shared_invite/zt-1plpfpm6r-zOHKI028VkpcWdobX65C~g">Slack</a> |
  <a href="https://traceloop.com/docs/python-sdk/introduction">Docs</a> |
  <a href="https://www.traceloop.com">Website</a>
</h4>

<h4 align="center">
   <a href="https://github.com/traceloop/openllmetry/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-Apache 2.0-blue.svg" alt="OpenLLMetry is released under the Apache-2.0 License">
  </a>
  <a href="https://www.ycombinator.com/companies/traceloop"><img src="https://img.shields.io/website?color=%23f26522&down_message=Y%20Combinator&label=Backed&logo=ycombinator&style=flat-square&up_message=Y%20Combinator&url=https%3A%2F%2Fwww.ycombinator.com"></a>
  <a href="https://github.com/traceloop/openllmetry/blob/main/CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/PRs-Welcome-brightgreen" alt="PRs welcome!" />
  </a>
  <a href="https://github.com/traceloop/openllmetry/issues">
    <img src="https://img.shields.io/github/commit-activity/m/traceloop/openllmetry" alt="git commit activity" />
  </a>
  <a href="https://join.slack.com/t/traceloopcommunity/shared_invite/zt-1plpfpm6r-zOHKI028VkpcWdobX65C~g">
    <img src="https://img.shields.io/badge/chat-on%20Slack-blueviolet" alt="Slack community channel" />
  </a>
  <a href="https://twitter.com/traceloopdev">
    <img src="https://img.shields.io/badge/follow-%40traceloopdev-1DA1F2?logo=twitter&style=social" alt="Traceloop Twitter" />
  </a>
</h4>

OpenLLMetry is a set of extensions built on top of [OpenTelemetry](https://opentelemetry.io/) that gives you complete observability over your LLM application. Because it uses OpenTelemetry under the hood, it can be connected to your existing observability solutions - Datadog, Honeycomb, and others.

It's built and maintained by Traceloop under the Apache 2.0 license.

## 🚀 Getting Started

```python
pip install traceloop-sdk
```

Then, you can start instrumenting your code:

```python
Tracer.init(app_name="your_app_name")
```

More info can be found in our [docs](https://traceloop.com/docs/python-sdk/getting-started).

## What do we instrument?

OpenLLMetry can instrument everything that [OpenTelemetry already instruments](https://github.com/open-telemetry/opentelemetry-python-contrib/tree/main/instrumentation) - so things like your DB, API calls, and more. On top of that, we built a set of custom extensions that instrument things like your calls to OpenAI or Anthropic, or your Vector DB like Pinecone, Chroma, or Weaviate.

### LLM Providers

- [x] OpenAI / Azure OpenAI
- [ ] Anthropic
- [ ] Cohere
- [ ] Replicate
- [ ] Vertex AI (GCP)
- [ ] Bedrock (AWS)

### Vector DBs

- [ ] Pinecone
- [ ] Chroma
- [ ] Weaviate

## 🌱 Contributing

Whether it's big or small, we love contributions ❤️ Check out our guide to see how to [get started](https://traceloop.com/docs/contributing/overview).

Not sure where to get started? You can:

- [Book a free pairing session with one of our teammates](mailto:nir@traceloop.com?subject=Pairing%20session&body=I'd%20like%20to%20do%20a%20pairing%20session!)!
- Join our <a href="https://join.slack.com/t/traceloopcommunity/shared_invite/zt-1plpfpm6r-zOHKI028VkpcWdobX65C~g">Slack</a>, and ask us any questions there.

## 💚 Community & Support

- [Slack](https://join.slack.com/t/traceloopcommunity/shared_invite/zt-1plpfpm6r-zOHKI028VkpcWdobX65C~g) (For live discussion with the community and the Traceloop team)
- [GitHub Discussions](https://github.com/traceloop/openllmetry/discussions) (For help with building and deeper conversations about features)
- [GitHub Issues](https://github.com/traceloop/openllmetry/issues) (For any bugs and errors you encounter using OpenLLMetry)
- [Twitter](https://twitter.com/traceloopdev) (Get news fast)