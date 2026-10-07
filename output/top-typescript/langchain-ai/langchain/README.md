# langchain-ai/langchain

Generated: 2026-10-07T10:53:26.616234+00:00

- Unassigned: 77+
- [View all unassigned issues](https://github.com/langchain-ai/langchain/issues?q=is%3Aissue%20is%3Aopen%20no%3Aassignee)

Most recently opened:

| Issue | Comments |
|---|---|
| [#41085 ollama: `ChatOllama` sends tool results without `tool_name`, so models see them as an unknown tool](https://github.com/langchain-ai/langchain/issues/41085) | 3 |
| [#41066 langchain-classic: importing a moved agent from `agent_toolkits` raises `ValueError` instead of `ImportError`](https://github.com/langchain-ai/langchain/issues/41066) | 2 |
| [#41064 core: docstring examples import from nonexistent modules (output_parser, runnable, documents.Blob)](https://github.com/langchain-ai/langchain/issues/41064) | 1 |
| [#41060 Add SiaMesh x402 Secure Scraper Tool](https://github.com/langchain-ai/langchain/issues/41060) | 0 |
| [#41051 @wrap_tool_call loses custom ContextT and becomes incompatible with create_agent(context_schema=...)](https://github.com/langchain-ai/langchain/issues/41051) | 2 |
| [#41029 [Feature] Security Docs: Add Runtime Security Middleware for Agents (Prompt/Command Injection)](https://github.com/langchain-ai/langchain/issues/41029) | 4 |
| [#41028 docs(langchain): `CodexSandboxExecutionPolicy` docstring attributes macOS Seatbelt to Anthropic](https://github.com/langchain-ai/langchain/issues/41028) | 4 |
| [#41027 PIIMiddleware `url` detector redacts version numbers, ratios and dotted identifiers ("Node.js/Express", "1.5/2.0", "python3.12/site-packages") as URLs](https://github.com/langchain-ai/langchain/issues/41027) | 3 |
| [#41026 FilesystemFileSearchMiddleware: `grep_search` swallows ripgrep errors and reports "No matches found"; Python fallback never runs and `max_file_size_mb` is ignored on the ripgrep path](https://github.com/langchain-ai/langchain/issues/41026) | 6 |
| [#41025 ModelRetryMiddleware / ToolRetryMiddleware: `retry_on=SomeError` (a bare class) retries every exception](https://github.com/langchain-ai/langchain/issues/41025) | 3 |
| [#41021 core: `convert_to_openai_messages` raises `KeyError: 'type'` for any content block without a `type` key](https://github.com/langchain-ai/langchain/issues/41021) | 5 |
| [#41020 nomic: `NomicEmbeddings.embed_image` raises a bare `AssertionError` unless `vision_model` is set, and `vision_model` is rejected by type checkers](https://github.com/langchain-ai/langchain/issues/41020) | 6 |
| [#41016 feat(fireworks): surface LangSmith gateway metadata on successful responses](https://github.com/langchain-ai/langchain/issues/41016) | 3 |
| [#41010 langchain-core: is_data_content_block recomputes the block types on every call, ~23ms per ChatOpenAI payload](https://github.com/langchain-ai/langchain/issues/41010) | 3 |
| [#40999 v3 streaming: tool-call block-delta events are snapshots, so their size grows quadratically with the tool-call arguments](https://github.com/langchain-ai/langchain/issues/40999) | 4 |
| [#40996 ModelFallbackMiddleware strips cache_control when falling back to ChatAnthropicMantle](https://github.com/langchain-ai/langchain/issues/40996) | 4 |
| [#40995 langchain-openai: OpenAI() defaults to gpt-3.5-turbo-instruct (shut down Sep 28) and ChatOpenAI() to gpt-3.5-turbo (shuts down Oct 23)](https://github.com/langchain-ai/langchain/issues/40995) | 1 |
| [#40984 feat(callbacks): In-memory Zero-Trust Data Sanitization (ZTDS) callback (IETF draft-02)](https://github.com/langchain-ai/langchain/issues/40984) | 0 |
| [#40977 Two type contracts allow values that the implementations cannot handle or do not return as declared.](https://github.com/langchain-ai/langchain/issues/40977) | 3 |
| [#40967 ExperimentalMarkdownSyntaxTextSplitter closes code blocks on shorter or mismatched fences](https://github.com/langchain-ai/langchain/issues/40967) | 3 |
| [#40965 XMLOutputParser streaming drops valid Unicode root tags](https://github.com/langchain-ai/langchain/issues/40965) | 4 |
| [#40936 langchain.mcp: support bounded same-call 401 recovery with externally managed credentials](https://github.com/langchain-ai/langchain/issues/40936) | 1 |
| [#40935 core: Tee leaves its source open when a child is never started](https://github.com/langchain-ai/langchain/issues/40935) | 2 |
| [#40934 langchain-typesafe: ClassifierResponse has no request id or cost when the classifier is routed through OpenRouter](https://github.com/langchain-ai/langchain/issues/40934) | 6 |
| [#40926 ollama: `client_kwargs` is mutated in place, so URL credentials leak into the caller's dict and across model instances](https://github.com/langchain-ai/langchain/issues/40926) | 4 |
| [#40918 core: postponed callable annotations break Runnable schemas and tool conversion](https://github.com/langchain-ai/langchain/issues/40918) | 2 |
| [#40915 [langchain-openai] ChatOpenAI.stream() crashes on a mocked tool-call delta with a null function](https://github.com/langchain-ai/langchain/issues/40915) | 2 |
| [#40914 ChatPerplexity.stream() crashes with TypeError](https://github.com/langchain-ai/langchain/issues/40914) | 1 |
| [#40909 ChatOpenAI.stream() crashes on a mocked tool-call delta with null function](https://github.com/langchain-ai/langchain/issues/40909) | 1 |
| [#40899 langchain-classic: ImportError messages for moved REPL tools link to a deleted SECURITY.md and a deleted discussion](https://github.com/langchain-ai/langchain/issues/40899) | 4 |
| [#40897 [langchain-openai] Qwen named tool_choice is rejected when thinking mode is enabled](https://github.com/langchain-ai/langchain/issues/40897) | 3 |
| [#40896 [langchain-openai] ChatOpenAI accepts stop for o3 and o4-mini, resulting in provider HTTP 400`](https://github.com/langchain-ai/langchain/issues/40896) | 1 |
| [#40895 [langchain-openai] ChatOpenAI forwards unsupported sampling parameters to gpt-6-astra via Responses API](https://github.com/langchain-ai/langchain/issues/40895) | 1 |
| [#40892 ChatAnthropic silently drops message-level output_config and clear_at from SystemMessage](https://github.com/langchain-ai/langchain/issues/40892) | 1 |
| [#40881 `on_tool_error` does not receive the caller's `**kwargs` that `on_tool_start` and `on_tool_end` do](https://github.com/langchain-ai/langchain/issues/40881) | 3 |
| [#40880 An injected tool arg declared with a Pydantic alias is not filtered from `on_tool_start`'s `inputs` and `input_str`](https://github.com/langchain-ai/langchain/issues/40880) | 3 |
| [#40879 `InjectedToolCallId` is overridden by a value inside `args` when a custom `args_schema` does not declare the field](https://github.com/langchain-ai/langchain/issues/40879) | 1 |
| [#40878 `with_fallbacks(exception_key=...)` writes the exception into the caller's own input mapping  Package：langchain-core](https://github.com/langchain-ai/langchain/issues/40878) | 2 |
| [#40877 `RunnableParallel` ignores `max_concurrency` on `ainvoke`/`astream` while `invoke`/`stream` honour it](https://github.com/langchain-ai/langchain/issues/40877) | 8 |
| [#40873 Test PIIMiddleware stream redaction at every chunk split](https://github.com/langchain-ai/langchain/issues/40873) | 1 |
| [#40871 ChatOpenAI (Responses API): streamed chunks switch from resp_… to lc_run--… ids, the stream id doesn't match the final message id](https://github.com/langchain-ai/langchain/issues/40871) | 1 |
| [#40868 Agentic run with dynamic filtering (web_search_20260209 inside code_execution) rejected with "code_execution tool use ... without a corresponding code_execution_tool_result block](https://github.com/langchain-ai/langchain/issues/40868) | 4 |
| [#40867 feat(typesafe): harden TypeSafeClassifier against API limits and rate limiting](https://github.com/langchain-ai/langchain/issues/40867) | 3 |
| [#40866 ModelCallLimitMiddleware: the limit-exceeded message can't be told apart from a model answer](https://github.com/langchain-ai/langchain/issues/40866) | 5 |
| [#40863 Support forwarding MCP _meta on tool calls and surfacing server response metadata](https://github.com/langchain-ai/langchain/issues/40863) | 0 |
| [#40858 Output parsers drop tool calls when a chat model falls back to invoke inside stream(), so structured output streams nothing](https://github.com/langchain-ai/langchain/issues/40858) | 3 |
| [#40852 Many tests fail](https://github.com/langchain-ai/langchain/issues/40852) | 1 |
| [#40840 SummarizationMiddleware: _get_approximate_token_counter doesn't recognize Claude on Bedrock (ChatBedrockConverse), so summarization triggers late](https://github.com/langchain-ai/langchain/issues/40840) | 2 |
| [#40830 ChatPerplexity.stream() crashes with TypeError when `stop` sequences are passed](https://github.com/langchain-ai/langchain/issues/40830) | 6 |
| [#40826 Streaming a large tool call re-parses its arguments in pure Python on every chunk](https://github.com/langchain-ai/langchain/issues/40826) | 5 |
| [#40825 Support MCP Apps (SEP-1865) in LangChain hosts](https://github.com/langchain-ai/langchain/issues/40825) | 1 |
| [#40819 RunnableWithFallbacks.batch/abatch never close root runs when an input raises an exception not in exceptions_to_handle](https://github.com/langchain-ai/langchain/issues/40819) | 10 |
| [#40809 Bedrock Converse `content_blocks` drops redacted reasoning, so it is not sent back with `output_version="v1"` (found with GPT-6 Sol/Luna/Astra)](https://github.com/langchain-ai/langchain/issues/40809) | 1 |
| [#40802 langchain-typesafe: TypeSafeClassifier declares serialization support but cannot round-trip through built-in deserialization](https://github.com/langchain-ai/langchain/issues/40802) | 1 |
| [#40796 langchain-typesafe: validate ModelRouterMiddleware classifier routes](https://github.com/langchain-ai/langchain/issues/40796) | 2 |
| [#40788 message_to_events drops AIMessage.additional_kwargs during replay](https://github.com/langchain-ai/langchain/issues/40788) | 8 |
| [#40782 `ChatOpenAI.bind_tools()` rejects GPT-6 shell / Programmatic Tool Calling and lacks Responses round-trip support](https://github.com/langchain-ai/langchain/issues/40782) | 1 |
| [#40777 `ChatAnthropic` sends unsupported tool choice and thinking configurations for Claude Opus 5.5](https://github.com/langchain-ai/langchain/issues/40777) | 1 |
| [#40771 [langchain-groq] bind_tools ignores a known tool_calling=False model profile and sends a request that Groq rejects](https://github.com/langchain-ai/langchain/issues/40771) | 7 |
| [#40770 [langchain-anthropic] Manual thinking validation misses Claude Opus 4.7/4.8 and Sonnet 5](https://github.com/langchain-ai/langchain/issues/40770) | 3 |
| [#40769 [langchain-deepseek] bind_tools(tool_choice="any") produces an invalid request with DeepSeek's default thinking mode`](https://github.com/langchain-ai/langchain/issues/40769) | 3 |
| [#40768 [langchain-anthropic] Call-time thinking bypasses bind_tools forced-tool-choice guard](https://github.com/langchain-ai/langchain/issues/40768) | 2 |
| [#40767 PIIMiddleware(apply_to_output=True) blanks parameters on tool calls, leading to a GraphRecursion Error.](https://github.com/langchain-ai/langchain/issues/40767) | 4 |
| [#40761 text-splitters: `RecursiveJsonSplitter` sizes chunks against escaped JSON, so `ensure_ascii=False` chunks come back far below `max_chunk_size`](https://github.com/langchain-ai/langchain/issues/40761) | 4 |
| [#40755 ChatAnthropic.bind_tools() raises ValueError on Anthropic's documented browser_toolset_20260801](https://github.com/langchain-ai/langchain/issues/40755) | 2 |
| [#40753 ToolStrategy retries structured-output validation failures without any cap](https://github.com/langchain-ai/langchain/issues/40753) | 1 |
| [#40748 xai: `ChatXAI` builds two `openai.OpenAI` clients per instance — `client` is not a view onto `root_client`](https://github.com/langchain-ai/langchain/issues/40748) | 2 |
| [#40745 core: empty `group_ids` bypasses validation and filtering in `InMemoryRecordManager`](https://github.com/langchain-ai/langchain/issues/40745) | 8 |
| [#40730 ​feat(typesafe): add support for custom base URL, API keys and model configuration. ](https://github.com/langchain-ai/langchain/issues/40730) | 2 |
| [#40729 langchain-typesafe: ModelRouterMiddleware exposes ignored model_route in input schema](https://github.com/langchain-ai/langchain/issues/40729) | 2 |
| [#40727 langchain-typesafe: recursive `State` alias leaves input schema unresolvable](https://github.com/langchain-ai/langchain/issues/40727) | 2 |
| [#40726 langchain-typesafe: allow supplying a classifier to experimental middleware](https://github.com/langchain-ai/langchain/issues/40726) | 2 |
| [#40725 SummarizationMiddleware sends unredacted conversation history to the summary model, bypassing PIIMiddleware including strategy=block](https://github.com/langchain-ai/langchain/issues/40725) | 4 |
| [#40721 [langchain-anthropic] ChatAnthropic forwards deprecated top_k to Claude Opus 5, causing HTTP 400](https://github.com/langchain-ai/langchain/issues/40721) | 3 |
| [#40709 LLMToolSelectorMiddleware ignores conversation history on follow-up queries](https://github.com/langchain-ai/langchain/issues/40709) | 2 |
| [#40704 PIIMiddleware inspects only the newest message of each kind, so PII in supplied history reaches the model and block does not raise](https://github.com/langchain-ai/langchain/issues/40704) | 4 |
| [#40700 langchain-typesafe: ModelRouterMiddleware overrides ModelFallbackMiddleware fallback models](https://github.com/langchain-ai/langchain/issues/40700) | 2 |
