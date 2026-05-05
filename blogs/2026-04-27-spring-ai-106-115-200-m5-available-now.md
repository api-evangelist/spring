---
title: "Spring AI 1.0.6, 1.1.5, 2.0.0-M5 Available Now"
url: "https://spring.io/blog/2026/04/27/spring-ai-1-0-6-1-1-5-2-0-0-M5-available-now"
date: "Mon, 27 Apr 2026 00:00:00 GMT"
author: "ilayaperumalg"
feed_url: "https://spring.io/blog.atom"
---
<p>On behalf of the Spring AI engineering team and everyone who has contributed, I'm happy to announce that Spring AI <code>1.0.6</code>, <code>1.1.5</code>, <code>2.0.0-M5</code> have been released and are now available from Maven Central.</p>
<p>These releases deliver important improvements, stability enhancements, bug fixes, documentation updates, and security fixes for <a href="https://spring.io/security/cve-2026-40966">CVE-2026-40966</a>, <a href="https://spring.io/security/cve-2026-40967">CVE-2026-40967</a>, <a href="https://spring.io/security/cve-2026-40978">CVE-2026-40978</a>, <a href="https://spring.io/security/cve-2026-40979">CVE-2026-40979</a> and <a href="https://spring.io/security/cve-2026-40980">CVE-2026-40980</a></p>
<h2 id="release-summary"><a class="anchor before" href="#release-summary"><svg height="16" version="1.1" viewBox="0 0 16 16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z" fill-rule="evenodd"></path></svg></a>Release Summary</h2>
<p>See individual release notes: <a href="https://github.com/spring-projects/spring-ai/releases/tag/v1.0.6">1.0.6</a> | <a href="https://github.com/spring-projects/spring-ai/releases/tag/v1.1.5">1.1.5</a> | <a href="https://github.com/spring-projects/spring-ai/releases/tag/v2.0.0-M5">2.0.0-M5</a></p>
<p>Thanks to all those who have contributed with issue reports and pull requests.</p>
<h2 id="version-specific-highlights"><a class="anchor before" href="#version-specific-highlights"><svg height="16" version="1.1" viewBox="0 0 16 16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z" fill-rule="evenodd"></path></svg></a>Version-Specific Highlights</h2>
<h3 id="spring-ai-106"><a class="anchor before" href="#spring-ai-106"><svg height="16" version="1.1" viewBox="0 0 16 16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z" fill-rule="evenodd"></path></svg></a>Spring AI 1.0.6</h3>
<p><strong>Overview:</strong> Maintenance release with 1 dependency upgrade and 1 build fix.</p>
<ul>
<li>Upgraded Spring Boot to 3.5.14</li>
<li>Renamed <code>JdbcChatMemoryRepositorySchemaInitializerPostgresqlTests</code> to follow the integration test naming convention</li>
</ul>
<p><a href="https://github.com/spring-projects/spring-ai/releases/tag/v1.0.6">View complete release notes →</a></p>
<h3 id="spring-ai-115"><a class="anchor before" href="#spring-ai-115"><svg height="16" version="1.1" viewBox="0 0 16 16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z" fill-rule="evenodd"></path></svg></a>Spring AI 1.1.5</h3>
<p><strong>Overview:</strong> 5 bug fixes, 4 documentation updates, 2 dependency upgrades, and 3 build updates.</p>
<p><strong>📢 Noteworthy:</strong></p>
<ul>
<li>The Pixtral 12B model has been removed and the Pixtral Large model is now deprecated. Users are encouraged to migrate to the currently recommended Mistral AI vision models. Integration tests have been updated to reflect the recommended models.</li>
</ul>
<p><strong>Bug Fixes:</strong></p>
<ul>
<li>Fixed string-based tool choice parsing in OpenAI SDK chat model</li>
<li>Fixed non-deterministic streaming token usage in BedrockConverse integration tests</li>
<li>Fixed incorrect <code>extra_body</code> parameter being included in OpenAI API requests</li>
<li>Fixed test skip condition when API keys are not configured</li>
<li>Fixed integration test naming convention (IT suffix)</li>
</ul>
<p><strong>Dependency Upgrades:</strong></p>
<ul>
<li>Upgraded Spring Boot to 3.5.14</li>
<li>Upgraded Apache Tika to 3.3.0, jsoup to 1.22.1, and Apache PDFBox to 3.0.7</li>
</ul>
<p><a href="https://github.com/spring-projects/spring-ai/releases/tag/v1.1.5">View complete release notes →</a></p>
<h3 id="spring-ai-200-m5"><a class="anchor before" href="#spring-ai-200-m5"><svg height="16" version="1.1" viewBox="0 0 16 16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z" fill-rule="evenodd"></path></svg></a>Spring AI 2.0.0-M5</h3>
<p><strong>Overview:</strong> 13 new features, 34 bug fixes, 12 documentation updates, 7 dependency upgrades, and 10 build updates.</p>
<p><strong>⚠️ Breaking Changes:</strong></p>
<ul>
<li>The Azure OpenAI modules have been removed from Spring AI. Users relying on Azure OpenAI integrations must migrate to the standard spring-ai-openai module, which now includes Azure OpenAI support via deployment handling.</li>
<li>Options merging behavior has been moved from the model level to the ChatClient level using a new builder <code>combineWith()</code> method. Existing code that relied on <code>ModelOptionUtils.merge()</code> calls may need to be updated. <a href="https://github.com/spring-projects/spring-ai/pull/5725">#5725</a></li>
<li>The Vertex AI model and autoconfiguration modules have been removed. Only the <code>spring-ai-vertex-ai-embedding</code> module is retained. <a href="https://github.com/spring-projects/spring-ai/pull/5714">#5714</a></li>
<li>The ZhipuAI model integration has been removed from the main repository. Users must migrate to the separate ZhipuAI integration repository. <a href="https://github.com/spring-projects/spring-ai/pull/5700">#5700</a></li>
<li>Oracle Cloud Infrastructure (OCI) GenAI support has been removed from the main repository. Users must migrate to the separate OCI GenAI integration repository. <a href="https://github.com/spring-projects/spring-ai/pull/5695">#5695</a></li>
<li>The <code>SpringAiTestAutoConfigurations</code> class has been removed. <a href="https://github.com/spring-projects/spring-ai/pull/5684">#5684</a></li>
</ul>
<p><strong>📢 Noteworthy:</strong></p>
<ul>
<li>The <code>spring-ai-openai</code> module now uses the official openai-java SDK across all OpenAI models (Chat, Embedding, Image, Audio, Moderation). The <code>spring-ai-openai-sdk</code> module has been removed and merged in. Existing <code>spring.ai.openai</code> properties, builders, and chat options remain fully compatible with no breaking changes. <a href="https://github.com/spring-projects/spring-ai/pull/5779">#5779</a></li>
<li>The Pixtral 12B model has been removed and the Pixtral Large model has been deprecated. Users should migrate to the recommended Mistral AI models.</li>
</ul>
<p><strong>New Features:</strong></p>
<ul>
<li>Custom <code>StructuredOutputConverter</code> implementations can now participate in the Native Structured Output pipeline <a href="https://github.com/spring-projects/spring-ai/pull/5659">#5659</a></li>
<li>MCP Server supports filtering which tools are exposed via <code>spring.ai.mcp.server.expose-mcp-client-tools</code> <a href="https://github.com/spring-projects/spring-ai/pull/5755">#5755</a></li>
<li>New unified cache usage metrics added to the <code>Usage</code> interface</li>
<li>New OpenAI SDK-based Audio Transcription and Moderation Model support <a href="https://github.com/spring-projects/spring-ai/pull/5730">#5730</a></li>
<li>OpenAI SDK models now support <code>extraBody</code> configuration <a href="https://github.com/spring-projects/spring-ai/pull/5734">#5734</a></li>
<li>Anthropic native web search tool integrated <a href="https://github.com/spring-projects/spring-ai/pull/5689">#5689</a></li>
<li>Anthropic thinking display setting, service tier, and geographic data residency support added <a href="https://github.com/spring-projects/spring-ai/pull/5666">#5666</a></li>
<li><code>ToolCallAdvisor.Builder</code> now exposes a getter for <code>conversationHistoryEnabled</code> <a href="https://github.com/spring-projects/spring-ai/pull/5869">#5869</a></li>
</ul>
<p><a href="https://github.com/spring-projects/spring-ai/releases/tag/v2.0.0-M5">View complete release notes →</a></p>
<h2 id="whats-next"><a class="anchor before" href="#whats-next"><svg height="16" version="1.1" viewBox="0 0 16 16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z" fill-rule="evenodd"></path></svg></a>What's Next</h2>
<p>The Spring AI team continues to focus on improving AI application development with Spring Boot. Based on the momentum from these releases, upcoming versions will build on these foundations with enhanced capabilities and developer experience improvements.</p>
<p>For the latest updates and to contribute to the project, visit our <a href="https://github.com/spring-projects/spring-ai">GitHub repository</a> or join the discussion in our community channels.</p>
<h2 id="resources"><a class="anchor before" href="#resources"><svg height="16" version="1.1" viewBox="0 0 16 16" width="16" xmlns="http://www.w3.org/2000/svg"><path d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z" fill-rule="evenodd"></path></svg></a>Resources</h2>
<p><a href="https://spring.io/projects/spring-ai/">Project Page</a> | <a href="https://github.com/spring-projects/spring-ai">GitHub</a> | <a href="https://github.com/spring-projects/spring-ai/issues">Issues</a> | <a href="https://stackoverflow.com/questions/tagged/spring-ai">Stack Overflow</a></p>
<p><strong>Documentation:</strong> <a href="https://docs.spring.io/spring-ai/reference/1.0/index.html">1.0.6 Docs</a> | <a href="https://docs.spring.io/spring-ai/reference/index.html">1.1.5 Docs</a> | <a href="https://docs.spring.io/spring-ai/reference/2.0/index.html">2.0.0-M5 Docs</a></p>
