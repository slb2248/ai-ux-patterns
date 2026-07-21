# Awesome AI UX Patterns

183 patterns for chat, agents, trust, commerce, and the rest of AI product UI.

I keep the interactive versions on [AI UX Playground](https://aiuxplayground.com/patterns). This repo is the open catalog - names, notes, and links - so you can browse or search without hunting through screenshots on Twitter.

[![Patterns](https://img.shields.io/badge/patterns-183-0A66C2)](https://aiuxplayground.com/patterns)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

<p align="center">
  <img src="assets/hero.jpg" alt="Screenshots of AI product UI patterns" width="100%" />
</p>

## What’s in here

Each pattern page has a short write-up. The better ones also cover when *not* to use it, common mistakes, and how real products do it. Where I have a demo, there’s a link.

Not every entry is equally deep yet. Start with the featured list if you just want a feel for the catalog.

**Tip:** use find-in-page on this README - the full index is below.

## Featured

- **[Tool Switching in Composer](https://aiuxplayground.com/pattern/tool-switching)** - pick web search, image gen, etc. from the composer · [Details](patterns/input/tool-switching.md)
- **[Human in the loop](https://aiuxplayground.com/pattern/human-in-the-loop)** - AI proposes; a person has to approve before it acts · [Details](patterns/collab/human-in-the-loop.md)
- **[Citations](https://aiuxplayground.com/pattern/citations)** - show where a claim came from · [Details](patterns/trust/citations.md)
- **[Chat Artifacts](https://aiuxplayground.com/pattern/chat-artifact)** - docs/code open beside the chat, not buried in it · [Details](patterns/chatbot/chat-artifact.md)
- **[Memory Management](https://aiuxplayground.com/pattern/memory-manage)** - let people see and edit what the model remembers · [Details](patterns/agents/memory-manage.md)
- **[Instant Buy](https://aiuxplayground.com/pattern/instant-buy)** - checkout without leaving the AI surface · [Details](patterns/commerce/instant-buy.md)
- **[Generative UI](https://aiuxplayground.com/pattern/gen-ui)** - answers that render real UI, not just markdown · [Details](patterns/output/gen-ui.md)
- **[Thread Branching](https://aiuxplayground.com/pattern/thread-branch)** - edit an earlier message and fork the thread · [Details](patterns/chatbot/thread-branch.md)

## Categories

- [Chatbot](#chatbot) (12)
- [Inputs](#inputs) (22)
- [Outputs](#outputs) (17)
- [Agents](#agents) (30)
- [Trust](#trust) (26)
- [Collab](#collab) (5)
- [Design Tools](#design-tools) (13)
- [Audio](#audio) (11)
- [Commerce](#commerce) (16)
- [Onboarding](#onboarding) (9)
- [Navigation](#navigation) (10)
- [Performance](#performance) (12)

## All patterns

### Chatbot

[Try on the site](https://aiuxplayground.com/patterns/chatbot) · [Folder](patterns/chatbot/)

- [Chat Artifacts](patterns/chatbot/chat-artifact.md) - Open generated docs and code in a side panel · [demo](https://aiuxplayground.com/pattern/chat-artifact)
- [Conversation History Search](patterns/chatbot/conversation-search.md) - Search through past conversations · [demo](https://aiuxplayground.com/pattern/conversation-search)
- [Conversation Tags & Labels](patterns/chatbot/conversation-tags.md) - Organize conversations with tags · [demo](https://aiuxplayground.com/pattern/conversation-tags)
- [Conversation Templates](patterns/chatbot/conversation-templates.md) - Save and reuse conversation starters · [demo](https://aiuxplayground.com/pattern/conversation-templates)
- [Export Conversation](patterns/chatbot/export-conversation.md) - Export chats as PDF/Markdown/JSON · [demo](https://aiuxplayground.com/pattern/export-conversation)
- [Interrupt and Resume](patterns/chatbot/interrupt-and-resume.md) - Stop mid-response and continue with context · [demo](https://aiuxplayground.com/pattern/interrupt-and-resume)
- [Memory Scope Toggle](patterns/chatbot/memory-scope-toggle.md) - Set memory persistence per message · [demo](https://aiuxplayground.com/pattern/memory-scope-toggle)
- [Message Pinning](patterns/chatbot/message-pinning.md) - Pin important messages · [demo](https://aiuxplayground.com/pattern/message-pinning)
- [Regeneration Carousel](patterns/chatbot/regen-carousel.md) - Swipe bot responses · [demo](https://aiuxplayground.com/pattern/regen-carousel)
- [Repair Contract](patterns/chatbot/repair-contract.md) - Retry with explicit delta and constraints · [demo](https://aiuxplayground.com/pattern/repair-contract)
- [Response Refinement](patterns/chatbot/response-refinement.md) - Modify AI responses with contextual actions · [demo](https://aiuxplayground.com/pattern/response-refinement)
- [Thread Branching](patterns/chatbot/thread-branch.md) - Edit and fork chats · [demo](https://aiuxplayground.com/pattern/thread-branch)

### Inputs

[Try on the site](https://aiuxplayground.com/patterns/input) · [Folder](patterns/input/)

- [AI Context Menu](patterns/input/context-menu.md) - Actions on select · [demo](https://aiuxplayground.com/pattern/context-menu)
- [Batch Input Processing](patterns/input/batch-input-processing.md) - Process multiple inputs at once · [demo](https://aiuxplayground.com/pattern/batch-input-processing)
- [Command Bar](patterns/input/command-bar.md) - Jump to AI actions with a command palette · [demo](https://aiuxplayground.com/pattern/command-bar)
- [Context Chip Management](patterns/input/context-chip-management.md) - Adding context sources via menu with removable chips · [demo](https://aiuxplayground.com/pattern/context-chip-management)
- [Context Mentions](patterns/input/mention.md) - Reference files via @ · [demo](https://aiuxplayground.com/pattern/mention)
- [Dynamic Follow-ups](patterns/input/follow-up.md) - Suggested questions · [demo](https://aiuxplayground.com/pattern/follow-up)
- [File Upload with AI Preview](patterns/input/file-upload-preview.md) - Upload files with AI-generated previews · [demo](https://aiuxplayground.com/pattern/file-upload-preview)
- [Follow-up Chips](patterns/input/follow-up-chips.md) - Suggested next turns · [demo](https://aiuxplayground.com/pattern/follow-up-chips)
- [Gesture Input](patterns/input/gesture-input.md) - Draw or gesture to trigger AI actions · [demo](https://aiuxplayground.com/pattern/gesture-input)
- [Input Mode Toggle](patterns/input/input-mode-toggle.md) - Switch between text, voice, and dictation modes · [demo](https://aiuxplayground.com/pattern/input-mode-toggle)
- [Magic Edit](patterns/input/magic-edit.md) - Transform selection · [demo](https://aiuxplayground.com/pattern/magic-edit)
- [Multimodal Input](patterns/input/multimodal.md) - Combine images, files, and text in one turn · [demo](https://aiuxplayground.com/pattern/multimodal)
- [Persona Selector](patterns/input/persona-selector.md) - Change AI role · [demo](https://aiuxplayground.com/pattern/persona-selector)
- [Predictive Type](patterns/input/predictive-type.md) - Ghost text · [demo](https://aiuxplayground.com/pattern/predictive-type)
- [Prompt Starters](patterns/input/empty-state.md) - Example prompts on an empty chat screen · [demo](https://aiuxplayground.com/pattern/empty-state)
- [Prompt Templates](patterns/input/templates.md) - Starter prompts · [demo](https://aiuxplayground.com/pattern/templates)
- [Slash Commands](patterns/input/slash-command.md) - Quick actions via / · [demo](https://aiuxplayground.com/pattern/slash-command)
- [Smart Autocomplete](patterns/input/smart-autocomplete.md) - Context-aware autocomplete beyond text · [demo](https://aiuxplayground.com/pattern/smart-autocomplete)
- [Tone Sliders](patterns/input/tone-slider.md) - Adjust style · [demo](https://aiuxplayground.com/pattern/tone-slider)
- [Tool Switching in Composer](patterns/input/tool-switching.md) - Switch between AI capabilities within composer · [demo](https://aiuxplayground.com/pattern/tool-switching)
- [Voice Input](patterns/input/voice-input.md) - Speech-to-text with visual feedback · [demo](https://aiuxplayground.com/pattern/voice-input)
- [Voice-to-Action](patterns/input/voice-to-action.md) - Voice commands that trigger specific actions · [demo](https://aiuxplayground.com/pattern/voice-to-action)

### Outputs

[Try on the site](https://aiuxplayground.com/patterns/output) · [Folder](patterns/output/)

- [Auto Tagging](patterns/output/auto-tag.md) - AI metadata · [demo](https://aiuxplayground.com/pattern/auto-tag)
- [Conversation Summary](patterns/output/conversation-summary.md) - Auto-summarize long chats · [demo](https://aiuxplayground.com/pattern/conversation-summary)
- [Feedback](patterns/output/feedback-loops.md) - Collect thumbs and comments to improve answers · [demo](https://aiuxplayground.com/pattern/feedback-loops)
- [Generative Charts](patterns/output/gen-chart.md) - Text to viz · [demo](https://aiuxplayground.com/pattern/gen-chart)
- [Generative UI](patterns/output/gen-ui.md) - Render interactive UI components in the answer · [demo](https://aiuxplayground.com/pattern/gen-ui)
- [Instant Translation](patterns/output/lang-toggle.md) - Swap language · [demo](https://aiuxplayground.com/pattern/lang-toggle)
- [Message Reactions](patterns/output/message-reactions.md) - Quick emoji reactions · [demo](https://aiuxplayground.com/pattern/message-reactions)
- [Output Analytics](patterns/output/output-analytics.md) - Track which outputs users prefer/use most · [demo](https://aiuxplayground.com/pattern/output-analytics)
- [Output Comparison View](patterns/output/output-comparison-view.md) - Side-by-side comparison of multiple outputs · [demo](https://aiuxplayground.com/pattern/output-comparison-view)
- [Output Format Selection](patterns/output/output-format-selection.md) - Choose output format (JSON, CSV, Markdown) · [demo](https://aiuxplayground.com/pattern/output-format-selection)
- [Output History](patterns/output/output-history.md) - Browse and restore previous outputs · [demo](https://aiuxplayground.com/pattern/output-history)
- [Output Sharing](patterns/output/output-sharing.md) - Share outputs with permissions/links · [demo](https://aiuxplayground.com/pattern/output-sharing)
- [Progressive Disclosure](patterns/output/progressive-disclosure.md) - Gradually reveal complex information · [demo](https://aiuxplayground.com/pattern/progressive-disclosure)
- [Scroll to Bottom](patterns/output/scroll-bottom.md) - New message alert · [demo](https://aiuxplayground.com/pattern/scroll-bottom)
- [Skeleton Screens](patterns/output/skeleton-loader.md) - Show content shape while loading · [demo](https://aiuxplayground.com/pattern/skeleton-loader)
- [Smart Code Blocks](patterns/output/smart-code.md) - Interactive snippets · [demo](https://aiuxplayground.com/pattern/smart-code)
- [Streaming](patterns/output/streaming.md) - Show replies token-by-token as they generate · [demo](https://aiuxplayground.com/pattern/streaming)

### Agents

[Try on the site](https://aiuxplayground.com/patterns/agents) · [Folder](patterns/agents/)

- [Agent Marketplace](patterns/agents/agent-marketplace.md) - Browse and install pre-built agents · [demo](https://aiuxplayground.com/pattern/agent-marketplace)
- [Agent Orchestration](patterns/agents/agent-orchestration.md) - Visual flow for multiple agents · [demo](https://aiuxplayground.com/pattern/agent-orchestration)
- [Agent Performance Metrics](patterns/agents/agent-performance-metrics.md) - Dashboard showing agent success rates · [demo](https://aiuxplayground.com/pattern/agent-performance-metrics)
- [Agent Versioning](patterns/agents/agent-versioning.md) - A/B test different agent configurations · [demo](https://aiuxplayground.com/pattern/agent-versioning)
- [Ambient Presence Displays](patterns/agents/ambient-presence-displays.md) - Low-attention signals for agent state · [demo](https://aiuxplayground.com/pattern/ambient-presence-displays)
- [Approval Workflows](patterns/agents/approval-workflows.md) - Human approval gates · [demo](https://aiuxplayground.com/pattern/approval-workflows)
- [Autonomous Mode Display](patterns/agents/autonomous-mode-display.md) - Persistent signal when agent runs unattended · [demo](https://aiuxplayground.com/pattern/autonomous-mode-display)
- [Autonomy Budgets](patterns/agents/autonomy-budgets.md) - Time- or action-bounded unattended runs · [demo](https://aiuxplayground.com/pattern/autonomy-budgets)
- [Blast Radius Visualization](patterns/agents/blast-radius-visualization.md) - Preview scope before agent executes · [demo](https://aiuxplayground.com/pattern/blast-radius-visualization)
- [Checkpoints and Restore](patterns/agents/checkpoints-and-restore.md) - Named snapshots with one-click restore · [demo](https://aiuxplayground.com/pattern/checkpoints-and-restore)
- [Conditional Logic & Branching](patterns/agents/conditional-logic.md) - Branch workflows by conditions · [demo](https://aiuxplayground.com/pattern/conditional-logic)
- [Context Portability](patterns/agents/context-portability.md) - Legible payloads across app boundaries · [demo](https://aiuxplayground.com/pattern/context-portability)
- [Error Recovery Strategies](patterns/agents/error-recovery-strategies.md) - Configurable retry/fallback patterns · [demo](https://aiuxplayground.com/pattern/error-recovery-strategies)
- [Escalation Thresholds](patterns/agents/escalation-thresholds.md) - Auto-demote autonomy when risk crosses a line · [demo](https://aiuxplayground.com/pattern/escalation-thresholds)
- [Human Handoff](patterns/agents/human-handoff.md) - Escalating to humans · [demo](https://aiuxplayground.com/pattern/human-handoff)
- [Memory Management](patterns/agents/memory-manage.md) - Viewing what AI remembers · [demo](https://aiuxplayground.com/pattern/memory-manage)
- [Multi-step Forms with AI](patterns/agents/multi-step-forms.md) - Adaptive progressive forms · [demo](https://aiuxplayground.com/pattern/multi-step-forms)
- [Per-Action Autonomy](patterns/agents/per-action-autonomy.md) - Autonomy scoped per capability, not per app · [demo](https://aiuxplayground.com/pattern/per-action-autonomy)
- [Plan & Execute](patterns/agents/plan-execute.md) - Breaking goals into steps · [demo](https://aiuxplayground.com/pattern/plan-execute)
- [Pre-Task Cost Estimate](patterns/agents/pre-task-cost-estimate.md) - Forecast tokens, dollars, and time before run · [demo](https://aiuxplayground.com/pattern/pre-task-cost-estimate)
- [Prompt Chaining](patterns/agents/chain.md) - Multi-step logic · [demo](https://aiuxplayground.com/pattern/chain)
- [Reversibility Marking](patterns/agents/reversibility-marking.md) - Label actions by how easily undone · [demo](https://aiuxplayground.com/pattern/reversibility-marking)
- [Sandbox Preview](patterns/agents/sandbox-preview.md) - Dry-run plan with explicit side effects before execute · [demo](https://aiuxplayground.com/pattern/sandbox-preview)
- [Scheduled Tasks & Recurring Actions](patterns/agents/scheduled-tasks.md) - Time-based automation triggers · [demo](https://aiuxplayground.com/pattern/scheduled-tasks)
- [Self-Correction](patterns/agents/correction.md) - Agents fixing errors · [demo](https://aiuxplayground.com/pattern/correction)
- [Suggest / Confirm / Execute](patterns/agents/suggest-confirm-execute.md) - Three autonomy modes for AI agents · [demo](https://aiuxplayground.com/pattern/suggest-confirm-execute)
- [Task Queue](patterns/agents/task-queue.md) - Visual queue of agent tasks · [demo](https://aiuxplayground.com/pattern/task-queue)
- [Time-Delayed Execution](patterns/agents/time-delayed-execution.md) - Cancelable countdown before high-impact actions · [demo](https://aiuxplayground.com/pattern/time-delayed-execution)
- [Tool Use](patterns/agents/tool-use.md) - Visualizing AI using external tools · [demo](https://aiuxplayground.com/pattern/tool-use)
- [Workflow Builder](patterns/agents/workflow-builder.md) - Visual drag-and-drop workflows · [demo](https://aiuxplayground.com/pattern/workflow-builder)

### Trust

[Try on the site](https://aiuxplayground.com/patterns/trust) · [Folder](patterns/trust/)

- [Agent Identity](patterns/trust/agent-identity.md) - Stable name, version, and capabilities per agent · [demo](https://aiuxplayground.com/pattern/agent-identity)
- [Audit Trail](patterns/trust/audit-trail.md) - Complete log of AI decisions and data usage · [demo](https://aiuxplayground.com/pattern/audit-trail)
- [Authentication Chains](patterns/trust/authentication-chains.md) - Legible identity trails across agent actions · [demo](https://aiuxplayground.com/pattern/authentication-chains)
- [Bias Detection](patterns/trust/bias-detection.md) - Flag potentially biased outputs · [demo](https://aiuxplayground.com/pattern/bias-detection)
- [Chain of Thought](patterns/trust/cot.md) - Reveal step-by-step reasoning behind an answer · [demo](https://aiuxplayground.com/pattern/cot)
- [Citation Tooltips](patterns/trust/citation-hover.md) - Hover for source · [demo](https://aiuxplayground.com/pattern/citation-hover)
- [Citations](patterns/trust/citations.md) - Attach verifiable sources to generated claims · [demo](https://aiuxplayground.com/pattern/citations)
- [Confidence Indicators](patterns/trust/confidence-indicators.md) - Visual confidence levels for outputs · [demo](https://aiuxplayground.com/pattern/confidence-indicators)
- [Confidence Score](patterns/trust/confidence-score.md) - Show how sure the model is about a claim · [demo](https://aiuxplayground.com/pattern/confidence-score)
- [Data Ownership & Control](patterns/trust/data-ownership.md) - User control over AI data usage · [demo](https://aiuxplayground.com/pattern/data-ownership)
- [Duration-Bound Consent](patterns/trust/duration-bound-consent.md) - Permissions that expire by default · [demo](https://aiuxplayground.com/pattern/duration-bound-consent)
- [Fact-Checking Indicators](patterns/trust/fact-checking-indicators.md) - Real-time fact-checking status · [demo](https://aiuxplayground.com/pattern/fact-checking-indicators)
- [Failure Disclosure](patterns/trust/failure-disclosure.md) - Honest signaling of AI limitations · [demo](https://aiuxplayground.com/pattern/failure-disclosure)
- [Granular Consent](patterns/trust/granular-consent.md) - Per-capability toggles, not bundled grants · [demo](https://aiuxplayground.com/pattern/granular-consent)
- [Knowledge Graph](patterns/trust/knowledge-graph.md) - Visualizing RAG · [demo](https://aiuxplayground.com/pattern/knowledge-graph)
- [Permission Drift Indicator](patterns/trust/permission-drift-indicator.md) - Surface accumulated agent permissions · [demo](https://aiuxplayground.com/pattern/permission-drift-indicator)
- [Privacy Filters](patterns/trust/privacy-blur.md) - Masking PII · [demo](https://aiuxplayground.com/pattern/privacy-blur)
- [Progress Steps](patterns/trust/status-steps.md) - Collapsible thinking and tool traces · [demo](https://aiuxplayground.com/pattern/status-steps)
- [Responsibility Attribution](patterns/trust/responsibility-attribution.md) - Trace which agent or human caused each action · [demo](https://aiuxplayground.com/pattern/responsibility-attribution)
- [Retrieval Context Preview](patterns/trust/retrieval-context-preview.md) - Preview retrieved context before acting on the answer · [demo](https://aiuxplayground.com/pattern/retrieval-context-preview)
- [Revocation Affordances](patterns/trust/revocation-affordances.md) - One-click revoke beside the grant · [demo](https://aiuxplayground.com/pattern/revocation-affordances)
- [Scope Disclosure](patterns/trust/scope-disclosure.md) - Plain-language agent permissions · [demo](https://aiuxplayground.com/pattern/scope-disclosure)
- [Source Browser](patterns/trust/source-browser.md) - Inspect source documents beside the answer · [demo](https://aiuxplayground.com/pattern/source-browser)
- [Source Quality Scores](patterns/trust/source-quality-scores.md) - Rate source reliability · [demo](https://aiuxplayground.com/pattern/source-quality-scores)
- [Transparency Report](patterns/trust/transparency-report.md) - Periodic reports on AI behavior/accuracy · [demo](https://aiuxplayground.com/pattern/transparency-report)
- [Verification Next Steps](patterns/trust/verification-next-steps.md) - Concrete actions to validate uncertain output · [demo](https://aiuxplayground.com/pattern/verification-next-steps)

### Collab

[Try on the site](https://aiuxplayground.com/patterns/collab) · [Folder](patterns/collab/)

- [Human in the loop](patterns/collab/human-in-the-loop.md) - Require human approval before AI acts · [demo](https://aiuxplayground.com/pattern/human-in-the-loop)
- [Inline Comment Thread](patterns/collab/inline-comment-thread.md) - Discuss selections · [demo](https://aiuxplayground.com/pattern/inline-comment-thread)
- [Live Presence](patterns/collab/live-presence.md) - Who is here now · [demo](https://aiuxplayground.com/pattern/live-presence)
- [Shared Session Link](patterns/collab/shared-session-link.md) - Shareable AI context · [demo](https://aiuxplayground.com/pattern/shared-session-link)
- [Smart Diff](patterns/collab/smart-diff.md) - Highlight and review what the model changed · [demo](https://aiuxplayground.com/pattern/smart-diff)

### Design Tools

[Try on the site](https://aiuxplayground.com/patterns/design) · [Folder](patterns/design/)

- [Background Removal](patterns/design/background-removal.md) - Automatic background removal/transparency · [demo](https://aiuxplayground.com/pattern/background-removal)
- [Color Palette Generator](patterns/design/color-palette-gen.md) - Generate color schemes from images/text · [demo](https://aiuxplayground.com/pattern/color-palette-gen)
- [Component Variants](patterns/design/component-variants.md) - Generate multiple UI variations · [demo](https://aiuxplayground.com/pattern/component-variants)
- [Image Upscaling](patterns/design/image-upscaling.md) - AI-powered resolution enhancement · [demo](https://aiuxplayground.com/pattern/image-upscaling)
- [In-painting](patterns/design/inpainting.md) - Modify specific areas · [demo](https://aiuxplayground.com/pattern/inpainting)
- [Infinite Canvas](patterns/design/infinite-canvas.md) - Spatial AI organization · [demo](https://aiuxplayground.com/pattern/infinite-canvas)
- [Object Removal](patterns/design/object-removal.md) - Remove unwanted objects from images · [demo](https://aiuxplayground.com/pattern/object-removal)
- [Prompt to UI](patterns/design/prompt-ui.md) - Generate editable UI from a text prompt · [demo](https://aiuxplayground.com/pattern/prompt-ui)
- [Style Interpolation](patterns/design/style-interpolation.md) - Blend between multiple styles · [demo](https://aiuxplayground.com/pattern/style-interpolation)
- [Style Transfer](patterns/design/style-transfer.md) - Applying visual styles · [demo](https://aiuxplayground.com/pattern/style-transfer)
- [Text-to-Image with Advanced Controls](patterns/design/text-to-image-controls.md) - Advanced generation controls · [demo](https://aiuxplayground.com/pattern/text-to-image-controls)
- [Theme Generation](patterns/design/theme-gen.md) - Color system creation · [demo](https://aiuxplayground.com/pattern/theme-gen)
- [Variation Picker](patterns/design/variation-grid.md) - Pick among side-by-side generated options · [demo](https://aiuxplayground.com/pattern/variation-grid)

### Audio

[Try on the site](https://aiuxplayground.com/patterns/audio) · [Folder](patterns/audio/)

- [Activation Boundaries](patterns/audio/activation-boundaries.md) - Explicit starts and stops for always-on agents · [demo](https://aiuxplayground.com/pattern/activation-boundaries)
- [Audio Enhancement](patterns/audio/audio-enhancement.md) - Noise reduction, clarity improvement · [demo](https://aiuxplayground.com/pattern/audio-enhancement)
- [Audio Summarization](patterns/audio/audio-summarization.md) - Summarize long audio recordings · [demo](https://aiuxplayground.com/pattern/audio-summarization)
- [Interruptibility](patterns/audio/interruptibility.md) - Single gesture to pause or cancel · [demo](https://aiuxplayground.com/pattern/interruptibility)
- [Live Transcript](patterns/audio/live-transcript.md) - Real-time text from audio · [demo](https://aiuxplayground.com/pattern/live-transcript)
- [Multi-User Awareness](patterns/audio/multi-user-awareness.md) - Identify speaker and scope to their permissions · [demo](https://aiuxplayground.com/pattern/multi-user-awareness)
- [Real-time Translation](patterns/audio/real-time-translation.md) - Live translation during voice conversations · [demo](https://aiuxplayground.com/pattern/real-time-translation)
- [Voice Cloning](patterns/audio/voice-cloning.md) - Clone and use custom voices · [demo](https://aiuxplayground.com/pattern/voice-cloning)
- [Voice Commands](patterns/audio/voice-commands.md) - Trigger actions via voice commands · [demo](https://aiuxplayground.com/pattern/voice-commands)
- [Voice Confirmation](patterns/audio/voice-confirmation.md) - Spoken approval for high-stakes voice actions · [demo](https://aiuxplayground.com/pattern/voice-confirmation)
- [Voice Visualizer](patterns/audio/voice-visualizer.md) - Feedback for voice mode · [demo](https://aiuxplayground.com/pattern/voice-visualizer)

### Commerce

[Try on the site](https://aiuxplayground.com/patterns/commerce) · [Folder](patterns/commerce/)

- [AI-Powered Customer Support](patterns/commerce/ai-customer-support.md) - Proactive support suggestions · [demo](https://aiuxplayground.com/pattern/ai-customer-support)
- [Dynamic Pricing](patterns/commerce/dynamic-pricing.md) - AI-powered real-time price optimization · [demo](https://aiuxplayground.com/pattern/dynamic-pricing)
- [Fraud Alert](patterns/commerce/fraud-detection.md) - Verify suspicious acts · [demo](https://aiuxplayground.com/pattern/fraud-detection)
- [Instant Buy](patterns/commerce/instant-buy.md) - One-click purchase from AI · [demo](https://aiuxplayground.com/pattern/instant-buy)
- [Inventory Prediction](patterns/commerce/inventory-prediction.md) - Predict stock needs based on trends · [demo](https://aiuxplayground.com/pattern/inventory-prediction)
- [Natural Language Filter](patterns/commerce/nl-filter.md) - Turn natural language into editable filters · [demo](https://aiuxplayground.com/pattern/nl-filter)
- [Personalized Checkout](patterns/commerce/personalized-checkout.md) - Custom checkout flow per user · [demo](https://aiuxplayground.com/pattern/personalized-checkout)
- [Price Drop Alerts](patterns/commerce/price-drop-alerts.md) - Notify users of price changes · [demo](https://aiuxplayground.com/pattern/price-drop-alerts)
- [Return Prediction](patterns/commerce/return-prediction.md) - Predict likelihood of returns · [demo](https://aiuxplayground.com/pattern/return-prediction)
- [Review Summary](patterns/commerce/review-summary.md) - Summarizing feedback · [demo](https://aiuxplayground.com/pattern/review-summary)
- [Semantic Search](patterns/commerce/semantic-search.md) - Retrieve items by meaning, not keywords · [demo](https://aiuxplayground.com/pattern/semantic-search)
- [Smart Bundles](patterns/commerce/smart-bundles.md) - Contextual upsell · [demo](https://aiuxplayground.com/pattern/smart-bundles)
- [Smart Comparison](patterns/commerce/comparison.md) - Build dynamic product or option comparison tables · [demo](https://aiuxplayground.com/pattern/comparison)
- [Smart Form Fill](patterns/commerce/smart-fill.md) - Unstructured to structured · [demo](https://aiuxplayground.com/pattern/smart-fill)
- [Smart Recommendations](patterns/commerce/smart-recommendations.md) - Context-aware product suggestions · [demo](https://aiuxplayground.com/pattern/smart-recommendations)
- [Visual Search](patterns/commerce/visual-search.md) - Find products or images from an uploaded photo · [demo](https://aiuxplayground.com/pattern/visual-search)

### Onboarding

[Try on the site](https://aiuxplayground.com/patterns/onboarding) · [Folder](patterns/onboarding/)

- [AI Personality Customization](patterns/onboarding/ai-personality-customization.md) - Customize AI assistant personality · [demo](https://aiuxplayground.com/pattern/ai-personality-customization)
- [AI Tips & Tricks](patterns/onboarding/ai-tips-tricks.md) - Contextual AI guidance · [demo](https://aiuxplayground.com/pattern/ai-tips-tricks)
- [Example Prompts Library](patterns/onboarding/example-prompts-library.md) - Curated prompt examples · [demo](https://aiuxplayground.com/pattern/example-prompts-library)
- [First Success Flow](patterns/onboarding/first-success-flow.md) - Guaranteed first successful AI interaction · [demo](https://aiuxplayground.com/pattern/first-success-flow)
- [Interactive Tutorials](patterns/onboarding/interactive-tutorials.md) - Step-by-step AI guides · [demo](https://aiuxplayground.com/pattern/interactive-tutorials)
- [Learning Path Recommendations](patterns/onboarding/learning-path-recommendations.md) - Personalized learning paths · [demo](https://aiuxplayground.com/pattern/learning-path-recommendations)
- [Onboarding Progress Tracking](patterns/onboarding/onboarding-progress-tracking.md) - Visual progress through onboarding · [demo](https://aiuxplayground.com/pattern/onboarding-progress-tracking)
- [Progressive Feature Unlock](patterns/onboarding/progressive-feature-unlock.md) - Gradual AI introduction · [demo](https://aiuxplayground.com/pattern/progressive-feature-unlock)
- [Use Case Wizard](patterns/onboarding/use-case-wizard.md) - Guided setup based on user goals · [demo](https://aiuxplayground.com/pattern/use-case-wizard)

### Navigation

[Try on the site](https://aiuxplayground.com/patterns/navigation) · [Folder](patterns/navigation/)

- [AI Capability Explorer](patterns/navigation/ai-capability-explorer.md) - Interactive feature guide · [demo](https://aiuxplayground.com/pattern/ai-capability-explorer)
- [AI Command History](patterns/navigation/ai-command-history.md) - Recent AI commands with quick replay · [demo](https://aiuxplayground.com/pattern/ai-command-history)
- [AI Feature Spotlight](patterns/navigation/ai-feature-spotlight.md) - Highlight AI capabilities · [demo](https://aiuxplayground.com/pattern/ai-feature-spotlight)
- [AI-Powered Search](patterns/navigation/ai-powered-search.md) - Semantic search across all features · [demo](https://aiuxplayground.com/pattern/ai-powered-search)
- [Contextual AI Suggestions](patterns/navigation/contextual-ai-suggestions.md) - Task-based AI prompts · [demo](https://aiuxplayground.com/pattern/contextual-ai-suggestions)
- [Contextual Shortcuts](patterns/navigation/contextual-shortcuts.md) - Shortcuts that adapt to current task · [demo](https://aiuxplayground.com/pattern/contextual-shortcuts)
- [Feature Discovery Feed](patterns/navigation/feature-discovery-feed.md) - Personalized feed of AI features to try · [demo](https://aiuxplayground.com/pattern/feature-discovery-feed)
- [Proactive Nudge](patterns/navigation/nudge.md) - Helpful hints · [demo](https://aiuxplayground.com/pattern/nudge)
- [Smart Bookmarks](patterns/navigation/smart-bookmarks.md) - AI-suggested bookmarks based on usage · [demo](https://aiuxplayground.com/pattern/smart-bookmarks)
- [Smart Tooltips](patterns/navigation/smart-tooltips.md) - Progressive AI hints · [demo](https://aiuxplayground.com/pattern/smart-tooltips)

### Performance

[Try on the site](https://aiuxplayground.com/patterns/performance) · [Folder](patterns/performance/)

- [Batch Processing Queue](patterns/performance/batch-processing-queue.md) - Queue multiple requests for efficiency · [demo](https://aiuxplayground.com/pattern/batch-processing-queue)
- [Caching Indicators](patterns/performance/caching-indicators.md) - Show when cached results are used · [demo](https://aiuxplayground.com/pattern/caching-indicators)
- [Cost Transparency](patterns/performance/cost-transparency.md) - Show operation costs · [demo](https://aiuxplayground.com/pattern/cost-transparency)
- [Cross-Session Budget](patterns/performance/cross-session-budget.md) - Spending caps that persist across chats and devices · [demo](https://aiuxplayground.com/pattern/cross-session-budget)
- [Hard Budget Ceilings](patterns/performance/hard-budget-ceilings.md) - Enforceable caps that stop the agent · [demo](https://aiuxplayground.com/pattern/hard-budget-ceilings)
- [Model Selection UI](patterns/performance/model-selection-ui.md) - Let users choose AI model (speed vs quality) · [demo](https://aiuxplayground.com/pattern/model-selection-ui)
- [Performance Optimization Tips](patterns/performance/performance-optimization-tips.md) - AI suggests ways to improve performance · [demo](https://aiuxplayground.com/pattern/performance-optimization-tips)
- [Processing Time Estimates](patterns/performance/processing-time-estimates.md) - Expected wait times · [demo](https://aiuxplayground.com/pattern/processing-time-estimates)
- [Rate Limit Warnings](patterns/performance/rate-limit-warnings.md) - API limit alerts · [demo](https://aiuxplayground.com/pattern/rate-limit-warnings)
- [Resource Usage Dashboard](patterns/performance/resource-usage-dashboard.md) - Visual dashboard of compute/memory usage · [demo](https://aiuxplayground.com/pattern/resource-usage-dashboard)
- [Running Meters](patterns/performance/running-meters.md) - Live token and cost counters during execution · [demo](https://aiuxplayground.com/pattern/running-meters)
- [Token Usage Indicator](patterns/performance/token-usage-indicator.md) - API quota display · [demo](https://aiuxplayground.com/pattern/token-usage-indicator)

## Something missing?

[Open an issue](https://github.com/slb2248/ai-ux-patterns/issues/new) with the pattern name, a one-liner, which products use it, and a screenshot if you have one. I usually add it on the site first (so there’s a demo), then sync it here.

Typos and small copy fixes via PR are welcome. Big new patterns are easier as issues.

## Elsewhere

- Site: [aiuxplayground.com](https://aiuxplayground.com)
- Patterns: [aiuxplayground.com/patterns](https://aiuxplayground.com/patterns)
- JSON dump of the catalog: [catalog.json](catalog.json)
- [X](https://x.com/aiuxplayground) · [LinkedIn](https://www.linkedin.com/company/aiuxplayground/) · [Newsletter](https://aiuxplayground.substack.com)

## License

MIT. Linking back to the site is appreciated if you reuse this.
