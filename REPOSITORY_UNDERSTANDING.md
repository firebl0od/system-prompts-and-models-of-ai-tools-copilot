# Complete Repository Understanding Document
## System Prompts and Models of AI Tools Collection

**Generated**: 2025-10-20  
**Repository**: firebl0od/system-prompts-and-models-of-ai-tools-copilot  
**Purpose**: Comprehensive collection of system prompts, tool configurations, and operational guidelines from 30+ AI coding assistants and development platforms

---

## Executive Summary

This repository serves as an extensive archive documenting the inner workings of modern AI coding assistants. It contains approximately **30,820 lines** across **96 documentation files** organized into **33 directories**. Each directory represents a different AI tool or platform, providing insights into their system prompts, available tools, operational guidelines, and behavioral instructions.

### Key Value Propositions:
1. **Transparency**: Reveals how major AI coding assistants are instructed to behave
2. **Education**: Teaches prompt engineering and AI agent design patterns
3. **Comparison**: Enables side-by-side comparison of different AI platforms
4. **Research**: Provides data for studying AI agent architectures

---

## Repository Structure Analysis

### Core Components

#### 1. README.md
- Main documentation hub with links to all 30+ AI tools
- Sponsorship information and contribution guidelines
- Over 30,000+ lines of insights claim
- Discord community information
- Star history visualization

#### 2. LICENSE.md
- CC0-1.0 Universal Public Domain Dedication
- Allows free use, modification, and distribution

#### 3. .github/FUNDING.yml
- PayPal, cryptocurrency, Patreon, Ko-fi support options
- Community funding configuration

---

## AI Tools and Platforms Covered

### 🏢 Enterprise/Commercial Platforms

#### **1. Amp (Sourcegraph)**
- **Location**: `/Amp/`
- **Files**: 4 (README, claude-4-sonnet.yaml, gpt-5.yaml, screenshot)
- **Key Features**:
  - Built by Sourcegraph for VS Code integration
  - Oracle tool powered by OpenAI's o3 reasoning model
  - Task management with todo lists
  - Codebase search agent for intelligent code discovery
  - Parallel tool execution capability
  - Mermaid diagram generation
  - Supports both Claude Sonnet 4 and GPT-5 models

**Tools Available**:
- File Operations: Read, Edit, Write, create_file, edit_file, format_file
- Search: Grep, glob, codebase_search_agent
- Execution: Bash, Task (subagent spawning)
- Advanced: Oracle (planning/review), mermaid (diagrams), web_search, read_web_page
- Management: todo_write, todo_read, get_diagnostics, undo_edit

**Communication Style**:
- Concise and direct (< 4 lines typically)
- No unnecessary preamble or postamble
- Professional tone without emojis
- Links to code using file:// protocol

#### **2. Anthropic Claude Code**
- **Location**: `/Anthropic/` and `/Claude Code/`
- **Files**: 4 total
- **Versions**: 
  - Claude Code 2.0.0 (released 2025-09-29)
  - Sonnet 4.5 general conversational prompt

**Claude Code 2.0 Features**:
- Interactive CLI tool for software engineering tasks
- Defensive security focus (refuses malicious code assistance)
- Git safety protocol (never force push, check authorship before amend)
- Specialized agent system:
  - general-purpose: Research and multi-step tasks
  - statusline-setup: Status line configuration
  - output-style-setup: Output style creation
- Artifact system for code, documents, React components
- Jupyter notebook support
- Web search and fetch integration
- PR creation with gh CLI

**Tools Available**:
- Bash (with extensive git integration and safety checks)
- Edit, Read, Write (file operations)
- Glob, Grep (pattern matching and search)
- Task (subagent spawning with specialized types)
- TodoWrite (task management)
- WebFetch, WebSearch (internet access)
- NotebookEdit (Jupyter notebooks)
- SlashCommand (command execution)
- BashOutput (background process monitoring)
- KillShell (terminate background processes)

**Communication Guidelines**:
- Extremely concise (often 1-2 sentences)
- No flattery or unnecessary affirmations
- Professional objectivity over emotional validation
- Never use emojis unless explicitly requested
- Uses markdown for formatting
- Explains non-trivial bash commands

#### **3. GitHub Copilot / VS Code Agent**
- **Location**: `/VSCode Agent/`
- **Files**: 9 (including model-specific prompts)
- **Models Supported**:
  - Claude Sonnet 4
  - Gemini 2.5 Pro
  - GPT-4.1
  - GPT-4o
  - GPT-5
  - GPT-5-mini

**Key Features**:
- Chat titles configuration
- NES tab completion support
- Model-specific behavioral tuning
- Integrated with VS Code ecosystem

#### **4. Cursor**
- **Location**: `/Cursor Prompts/`
- **Files**: 9 (multiple versions tracked)
- **Versions**:
  - Agent Prompt v1.0
  - Agent Prompt v1.2
  - Agent Prompt (current)
  - Agent Prompt 2025-09-03
  - Agent CLI Prompt 2025-08-07

**Features**:
- Memory system (Memory Prompt, Memory Rating Prompt)
- Agent and Chat modes
- CLI-specific agent version
- Tool configurations in JSON format

#### **5. Windsurf**
- **Location**: `/Windsurf/`
- **Files**: 2 (Wave 11 release)
- **Features**: Complete prompt and tools for Wave 11 version

#### **6. Augment Code**
- **Location**: `/Augment Code/`
- **Files**: 4 (prompts and tools for both Claude and GPT)
- **Models**: Claude 4 Sonnet and GPT-5
- **Size**: 11K-29K per file

#### **7. Devin AI**
- **Location**: `/Devin AI/`
- **Files**: 1 (34K prompt file)
- **Focus**: Autonomous AI software engineer

#### **8. Lovable**
- **Location**: `/Lovable/`
- **Files**: 2 (Agent Prompt 20K, Agent Tools 28K)

#### **9. Manus**
- **Location**: `/Manus Agent Tools & Prompt/`
- **Files**: 4 (Agent loop, Modules, Prompt, tools)
- **Features**: Modular agent architecture with explicit loop control

#### **10. Replit**
- **Location**: `/Replit/`
- **Files**: 2 (Prompt 8K, Tools 25K)
- **Focus**: In-browser IDE and AI assistant

#### **11. Same.dev**
- **Location**: `/Same.dev/`
- **Files**: 2 (Prompt 35K, Tools 22K)

#### **12. NotionAI**
- **Location**: `/NotionAi/`
- **Files**: 2 (Prompt 32K, tools 35K)
- **Focus**: Document-centric AI assistance

#### **13. Perplexity**
- **Location**: `/Perplexity/`
- **Files**: 1 (9.4K prompt)
- **Focus**: Search-augmented responses

#### **14. Warp.dev**
- **Location**: `/Warp.dev/`
- **Files**: 1 (15K prompt)
- **Focus**: Terminal-based AI assistant

#### **15. Leap.new**
- **Location**: `/Leap.new/`
- **Files**: 2 (Prompts 52K, tools 17K)

#### **16. Orchids.app**
- **Location**: `/Orchids.app/`
- **Files**: 2 (System Prompt 58K, Decision-making 6.7K)
- **Features**: Sophisticated decision-making system

#### **17. Qoder**
- **Location**: `/Qoder/`
- **Files**: 3 (prompt, Quest Action, Quest Design)
- **Features**: Quest-based task system

#### **18. Trae**
- **Location**: `/Trae/`
- **Files**: 3 (Builder Prompt, Builder Tools, Chat Prompt)
- **Features**: Separate builder and chat modes

#### **19. Traycer AI**
- **Location**: `/Traycer AI/`
- **Files**: 3 (phase_mode prompts/tools, plan_mode tools)
- **Features**: Multi-phase operation (phase mode vs plan mode)

#### **20. Emergent**
- **Location**: `/Emergent/`
- **Files**: 2 (Prompt 37K, Tools 7.7K)

#### **21. Cluely**
- **Location**: `/Cluely/`
- **Files**: 2 (Default 4.5K, Enterprise 21K)
- **Features**: Separate default and enterprise configurations

#### **22. CodeBuddy**
- **Location**: `/CodeBuddy Prompts/`
- **Files**: 2 (Chat 1.6K, Craft 40K)
- **Features**: Lightweight chat mode, comprehensive craft mode

#### **23. Comet Assistant**
- **Location**: `/Comet Assistant/`
- **Files**: 1 (System 11K)

#### **24. Junie**
- **Location**: `/Junie/`
- **Files**: 1 (6.1K prompt)

#### **25. Kiro**
- **Location**: `/Kiro/`
- **Files**: 3 (Mode Classifier, Spec, Vibe)
- **Features**: Three distinct operational modes

#### **26. Poke**
- **Location**: `/Poke/`
- **Files**: 7 (agent + p1-p6 segments)
- **Features**: Segmented prompt architecture

#### **27. v0 (Vercel)**
- **Location**: `/v0 Prompts and Tools/`
- **Files**: 2 (Prompt, Tools)
- **Focus**: UI/UX generation

#### **28. Z.ai Code**
- **Location**: `/Z.ai Code/`
- **Files**: 1 (prompt)

#### **29. dia**
- **Location**: `/dia/`
- **Files**: 1 (prompt)

#### **30. Xcode (Apple)**
- **Location**: `/Xcode/`
- **Files**: 6 (System, multiple action types)
- **Action Types**:
  - DocumentAction
  - ExplainAction
  - MessageAction
  - PlaygroundAction
  - PreviewAction
- **Focus**: Native iOS/macOS development integration

---

### 🌐 Open Source Tools

#### **Location**: `/Open Source prompts/`
**Sub-directories** (each with dedicated prompts):

1. **Bolt**: Web application builder
2. **Cline**: VS Code extension
3. **Codex CLI**: OpenAI Codex CLI (20250820 version)
4. **Gemini CLI**: Google Gemini CLI
5. **Lumo**: AI assistant
6. **RooCode**: Code generation tool

---

## Common Patterns Across Tools

### Tool Categories

Most AI coding assistants provide similar categories of tools:

#### 1. **File Operations**
- Read: View file contents
- Write: Create new files
- Edit: Modify existing files (string replacement, line-based)
- Delete: Remove files (less common)

#### 2. **Code Search**
- Grep: Pattern matching in files
- Glob: File name pattern matching
- Semantic Search: Concept-based code search
- Symbol Navigation: Find definitions, references

#### 3. **Execution**
- Bash/Shell: Run terminal commands
- Task/Agent: Spawn sub-agents for complex tasks
- Background Processes: Long-running command support

#### 4. **Advanced Features**
- Web Search: Internet information retrieval
- Web Fetch: Download and parse web pages
- Diagram Generation: Mermaid, visual representations
- Oracle/Reasoning: Deep analysis and planning

#### 5. **Management**
- Todo Lists: Task tracking and planning
- Diagnostics: Linter and compiler error detection
- Git Integration: Version control operations

### Communication Style Patterns

#### Conciseness Spectrum:
1. **Ultra-Concise** (Claude Code, Amp): 1-4 lines typical, no preamble
2. **Moderate** (Most tools): Brief explanations with context
3. **Verbose** (Some prompts): Detailed explanations and reasoning

#### Common Directives:
- "Never apologize unnecessarily"
- "Avoid emojis unless requested"
- "Use markdown for formatting"
- "Be professional and objective"
- "Provide complete solutions, not partial answers"

#### Proactiveness Balance:
- Do what's asked without surprising the user
- Don't make assumptions about unstated requirements
- Ask for clarification when ambiguous
- Take initiative within the scope of the request

### Security Patterns

#### Common Security Guidelines:
1. **No Malicious Code**: Refuse to create malware, exploits, viruses
2. **No Credential Harvesting**: Don't help bulk extract SSH keys, cookies, wallets
3. **Defensive Security Only**: Support security analysis and defensive tools
4. **Git Safety**: 
   - Never force push without explicit request
   - Check authorship before amending commits
   - Avoid --no-verify flags
   - Never skip hooks without permission
5. **Secret Protection**: Don't commit or log secrets, API keys, credentials

### Task Management Patterns

Many tools use todo/task list systems:

#### Task States:
- **pending**: Not yet started
- **in_progress**: Currently working (usually only ONE at a time)
- **completed**: Finished successfully

#### Best Practices:
- Create todos for multi-step tasks (3+ steps)
- Mark todos as completed immediately after finishing
- Don't batch completions
- Break complex tasks into smaller steps
- Provide visibility to users on progress

---

## Tool Configuration Formats

### JSON Tool Schemas

Most tools define their capabilities using JSON schemas with:

```json
{
  "name": "tool_name",
  "description": "What the tool does",
  "parameters": {
    "type": "object",
    "properties": {
      "param_name": {
        "type": "string",
        "description": "Parameter description"
      }
    },
    "required": ["param_name"]
  }
}
```

### Common Parameters:

#### File Operations:
- `file_path` / `path`: Absolute path (not relative)
- `content`: File contents
- `old_string` / `new_string`: For replacements
- `offset` / `limit`: For pagination
- `read_range`: Line number ranges

#### Search:
- `pattern`: Regex or text pattern
- `glob`: File name pattern
- `path`: Directory to search
- `case_sensitive`: Boolean flag
- `output_mode`: content / files_with_matches / count

#### Execution:
- `command` / `cmd`: Shell command
- `timeout`: Maximum execution time
- `cwd`: Working directory
- `run_in_background`: Async execution flag

---

## Model-Specific Tuning

### Claude-Specific Features:
- Thinking blocks (budget_tokens: 4000)
- Artifacts system (code, markdown, React, SVG, Mermaid)
- Streaming responses
- Tool use formatting with XML-style tags
- Citation requirements for web search

### GPT-Specific Features:
- Function calling format
- System message optimization
- Temperature and top_p controls
- Completion tokens management

### Model Strings Referenced:
- `claude-sonnet-4-5-20250929`
- `gpt-5`
- `gpt-5-mini`
- `gpt-4.1`
- `gpt-4o`
- `gemini-2.5-pro`

---

## Behavioral Psychology Patterns

### User Interaction Principles:

1. **Professional Objectivity**: Prioritize technical accuracy over validation
2. **Respectful Disagreement**: Correct errors honestly even if not what user wants to hear
3. **Emotional Intelligence**: Provide empathy for emotional/advice queries
4. **Appropriate Detail**: Match complexity of response to complexity of query
5. **Natural Conversation**: Vary language, avoid repetitive phrases

### Refusal Handling:

#### When to Refuse:
- Malicious code creation
- Credential harvesting
- Child safety concerns (anyone under 18)
- Harmful content promotion
- Copyright violation

#### How to Refuse:
- Don't explain why or what it could lead to
- Offer alternatives when possible
- Keep response short (1-2 sentences)
- Maintain conversational tone

---

## Git Integration Patterns

### Commit Best Practices:

1. **Safety Checks**:
   - Never update git config
   - Never force push to main/master
   - Never skip hooks without permission
   - Check authorship before amending
   - Only commit when explicitly asked

2. **Commit Message Format**:
   ```
   Brief summary of changes (why, not what)
   
   🤖 Generated with [Tool Name](url)
   
   Co-Authored-By: Assistant <email>
   ```

3. **Process**:
   - Run `git status` to see changes
   - Run `git diff` to review changes
   - Run `git log` to match commit style
   - Stage relevant files
   - Create commit
   - Verify with `git status`
   - Handle pre-commit hook failures appropriately

### Pull Request Creation:

1. **Gather Context**:
   - `git status` for current state
   - `git diff` for changes
   - Check remote tracking status
   - `git log` for full commit history
   - `git diff [base]...HEAD` for all changes

2. **PR Format**:
   ```markdown
   #### Summary
   - Bullet point 1
   - Bullet point 2
   - Bullet point 3
   
   #### Test plan
   - [ ] Test item 1
   - [ ] Test item 2
   
   🤖 Generated with [Tool Name](url)
   ```

---

## Artifact Systems

### Artifact Types (primarily Claude):

1. **Code**: `application/vnd.ant.code`
   - Language-specific syntax highlighting
   - Complete, executable code snippets

2. **Documents**: `text/markdown`
   - Plain text and formatted documents
   - READMEs, documentation

3. **HTML**: `text/html`
   - Single-file HTML+CSS+JS
   - External scripts only from cdnjs.cloudflare.com
   - Never use localStorage/sessionStorage

4. **React Components**: `application/vnd.ant.react`
   - Pure functional components
   - Hooks support (useState, useEffect, etc.)
   - No required props (or default values)
   - Tailwind CSS core utilities only
   - Available libraries: lucide-react, recharts, mathjs, lodash, d3, plotly, three.js (r128), papaparse, sheetjs, shadcn/ui, chart.js, tone, mammoth, tensorflow

5. **SVG**: `image/svg+xml`
   - Scalable vector graphics
   - Rendered directly

6. **Mermaid**: `application/vnd.ant.mermaid`
   - Flowcharts, sequence diagrams
   - Architecture diagrams

### Artifact Guidelines:

#### When to Create:
- Custom code >20 lines
- Content for use outside conversation (reports, emails, articles)
- Creative writing of any length
- Structured reference content (meal plans, schedules)
- Content to be edited/reused
- Text-heavy documents >1500 characters

#### When NOT to Create:
- Simple code snippets <20 lines
- Conversational responses
- Brief answers
- Temporary explanations

#### Update vs Rewrite:
- **Update**: <20 lines changed, <5 locations
- **Rewrite**: Structural changes or exceeds update thresholds
- Maximum 4 updates per message, then rewrite

---

## Search and Web Integration

### Web Search Guidelines:

#### When to Search:
- Information past knowledge cutoff (post-January 2025)
- Frequently changing information
- Current events, news, weather
- Technical info that may be outdated
- User explicitly requests search

#### When NOT to Search:
- General knowledge rarely changes
- Fundamental definitions/theories
- Casual conversation
- Established historical facts

#### Search Query Format:
- Concise: 1-6 words
- Include year/date for specific events
- Use 'today' for current info
- Never use operators: '-', 'site:', quotes (unless asked)
- Privacy: Never include names when identifying people from images

### Web Fetch Patterns:

1. **Direct URL Fetch**: Exact URLs from user or search results only
2. **Content Extraction**: Convert HTML to markdown
3. **AI Analysis**: Optional prompt parameter for summarization
4. **Rate Limiting**: Track per conversation/user
5. **Redirect Handling**: Follow redirects, inform user

---

## Special Features by Tool

### Unique Capabilities:

#### **Amp**:
- Oracle tool (o3 reasoning) for planning and review
- Task tool spawning sub-agents
- Parallel tool execution emphasis

#### **Claude Code**:
- Background bash with BashOutput monitoring
- Jupyter notebook editing
- SlashCommand execution
- Specialized subagent types

#### **Cursor**:
- Memory system with rating
- Multiple prompt versions tracked
- CLI-specific agent

#### **Windsurf**:
- Wave versioning system
- Wave 11 latest

#### **Kiro**:
- Mode classifier
- Spec mode
- Vibe mode

#### **Traycer AI**:
- Phase mode
- Plan mode
- Separate tool sets per mode

#### **Orchids.app**:
- Sophisticated decision-making system
- 58K system prompt (largest single file)

#### **Poke**:
- Segmented architecture (p1-p6)
- Modular prompt design

#### **Qoder**:
- Quest system
- Quest Action and Quest Design separation

#### **Xcode**:
- Action-based architecture
- Native Apple platform integration
- Multiple action types (Document, Explain, Message, Playground, Preview)

---

## File Size Analysis

### Largest Prompts:
1. Amp claude-4-sonnet.yaml: 65K
2. Amp gpt-5.yaml: 61K
3. Orchids.app System Prompt: 58K
4. Leap.new Prompts: 52K
5. Claude Code tools: 48K

### Largest Tool Definitions:
1. Claude Code tools: 48K
2. NotionAi tools: 35K
3. Windsurf Tools Wave 11: 33K
4. Augment Code claude-4-sonnet-tools: 29K
5. Lovable Agent Tools: 28K

### Smallest Files:
1. Xcode MessageAction: 235 bytes
2. Xcode ExplainAction: 245 bytes
3. Xcode DocumentAction: 374 bytes
4. Xcode PlaygroundAction: 414 bytes
5. VSCode chat-titles: 765 bytes

---

## Versioning and Evolution

### Tools with Version Tracking:

1. **Cursor**: Multiple versions (v1.0, v1.2, 2025-08-07, 2025-09-03, current)
2. **Claude Code**: Version 2.0.0 (2025-09-29)
3. **Codex CLI**: Dated version (20250820)
4. **Windsurf**: Wave 11

This suggests active development and iteration on prompts and capabilities.

---

## Licensing and Community

### License: CC0-1.0 Universal
- Public domain dedication
- No rights reserved
- Free to use, modify, distribute

### Community:
- **Discord**: LeaksLab (1.4M+ members implied by badge)
- **Early Access**: New prompts released on Discord first
- **Contributions**: Open to community submissions
- **Star History**: Tracked and visualized

### Sponsorship:
- PayPal
- Cryptocurrency (BTC, LTC, ETH)
- Patreon
- Ko-fi
- Corporate sponsorship opportunities

---

## Key Insights and Patterns

### 1. Convergence of Design
Most AI coding assistants share similar core capabilities:
- File operations (read/write/edit)
- Search (grep/glob/semantic)
- Execution (bash/shell)
- Task management (todos)
- Web access (search/fetch)

### 2. Differentiation Strategies
Tools differentiate through:
- **Specialized Modes**: Kiro (3 modes), Traycer (2 modes), CodeBuddy (2 modes)
- **Advanced Reasoning**: Amp's Oracle (o3), sophisticated planning systems
- **Platform Integration**: Xcode actions, VS Code extensions, Replit IDE
- **Agent Architecture**: Manus modules, Poke segments, Cursor memory system

### 3. Security-First Mentality
Consistent across all tools:
- Refuse malicious code assistance
- Protect credentials and secrets
- Git safety protocols
- Defensive security support only

### 4. User Experience Focus
- Concise communication preference
- Professional objectivity
- Appropriate proactiveness
- Clear error messages
- Progress visibility (todo lists)

### 5. Evolution Towards Autonomy
Progression from:
- **Simple Assistance**: Answer questions, explain code
- **Interactive Coding**: Edit files, run commands
- **Task Execution**: Multi-step autonomous work
- **Agent Systems**: Spawning specialized sub-agents
- **Reasoning Integration**: Oracle, planning systems

### 6. Prompt Engineering Complexity
- Smallest: 1-6K (simple tools)
- Medium: 10-30K (standard tools)
- Large: 40-65K (comprehensive systems like Amp, Orchids)

### 7. Tool Definition Scales
- Simple: 7-10K (basic tool sets)
- Standard: 15-25K (typical capabilities)
- Comprehensive: 30-48K (extensive tool suites)

---

## Technical Implementation Details

### Common Tech Stack References:

#### Languages:
- Python
- JavaScript/TypeScript
- Go
- Rust
- Java
- C/C++

#### Frameworks:
- React (extensively in artifacts)
- Node.js
- Three.js
- Next.js (implied in v0)

#### Tools:
- Git (universal)
- npm/pip/cargo (package managers)
- Bash/Shell (command execution)
- ripgrep (fast search)
- gh CLI (GitHub operations)

#### Libraries Available in Artifacts:
- lucide-react: Icons
- recharts: Charts
- mathjs: Math operations
- lodash: Utilities
- d3: Data visualization
- plotly: Scientific plots
- three.js (r128): 3D graphics
- papaparse: CSV parsing
- sheetjs: Excel files
- shadcn/ui: UI components
- chart.js: Charts
- tone: Audio
- mammoth: Word documents
- tensorflow: ML

---

## Usage Recommendations

### For Developers:
1. **Study Prompt Patterns**: Learn from 30+ professional implementations
2. **Understand Tool Design**: See how tools are structured and described
3. **Compare Approaches**: Multiple solutions to same problems
4. **Security Practices**: Industry-standard security guidelines

### For Researchers:
1. **Evolution Study**: Track changes in Cursor versions, Windsurf waves
2. **Design Patterns**: Analyze common patterns across implementations
3. **Capability Mapping**: Understand tool capability evolution
4. **UX Principles**: Study communication style guidelines

### For AI Engineers:
1. **Prompt Engineering**: Learn from production-grade prompts
2. **Tool Integration**: See how tools are integrated into workflows
3. **Agent Architecture**: Study sub-agent spawning patterns
4. **Error Handling**: Learn from established error handling practices

### For Users:
1. **Feature Comparison**: Understand what different tools offer
2. **Workflow Optimization**: Learn how to work effectively with AI
3. **Capability Awareness**: Know what's possible with each tool
4. **Best Practices**: Adopt established interaction patterns

---

## Future Directions

Based on the repository contents, likely evolution paths:

### 1. Enhanced Reasoning
- More tools adopting Oracle-like reasoning systems
- Deeper planning and analysis capabilities
- Multi-step reasoning chains

### 2. Specialized Agents
- More granular agent specialization
- Dynamic agent selection
- Cross-tool agent communication

### 3. Multimodal Integration
- Image understanding (already in some)
- Video processing
- Audio transcription
- PDF analysis

### 4. Memory Systems
- Cursor's memory approach may become standard
- Long-term context retention
- User preference learning

### 5. Collaborative Features
- Multi-agent collaboration
- Real-time pair programming
- Team knowledge sharing

---

## Conclusion

This repository represents a comprehensive snapshot of the state of AI coding assistants as of 2025. It reveals both the convergence of design patterns across the industry and the unique innovations each platform brings to the table.

### Key Takeaways:

1. **Maturity**: AI coding assistants have evolved from simple autocomplete to sophisticated autonomous agents
2. **Standardization**: Core capabilities are converging around common patterns
3. **Innovation**: Differentiation through specialized features and agent architectures
4. **User-Centric**: Strong focus on UX, communication style, and user control
5. **Security-Conscious**: Universal emphasis on security and responsible AI use
6. **Open Knowledge**: This repository democratizes understanding of AI systems

### Impact:

- **Transparency**: Shows what's "under the hood" of AI tools
- **Education**: Teaches prompt engineering at scale
- **Research**: Enables academic study of AI assistants
- **Development**: Helps build better AI tools
- **Comparison**: Allows informed tool selection

This repository is an invaluable resource for anyone interested in AI coding assistants, whether as a user, developer, researcher, or engineer. The 30,820+ lines of documented prompts and configurations represent thousands of hours of engineering work by leading AI companies and open-source projects, now available for study and learning.

---

## Appendix: Quick Reference

### By File Count:
- Cursor Prompts: 9 files
- VSCode Agent: 9 files
- Poke: 7 files
- Xcode: 6 files
- Augment Code, Manus, Amp: 4 files each
- Most others: 1-3 files

### By Documentation Size:
- Total: ~30,820 lines
- Largest single file: 65K (Amp claude-4-sonnet)
- Smallest: 235 bytes (Xcode MessageAction)
- Average: ~320 lines per file

### By Model Support:
- Claude Sonnet 4/4.5: Most platforms
- GPT-4/5 series: Many platforms
- Gemini 2.5: Limited (VSCode Agent)
- Model-agnostic: Some platforms

### By Platform Integration:
- VS Code: Amp, Cursor, Cline, RooCode
- CLI: Claude Code, Codex CLI, Gemini CLI, Warp.dev
- Web: Replit, v0, Bolt, Leap.new, Lovable
- IDE-specific: Xcode
- Standalone: Devin, Emergent, others

---

**Document Version**: 1.0  
**Generated**: 2025-10-20  
**Total Understanding**: Complete coverage of 96 files across 33 directories  
**Analysis Depth**: Comprehensive with patterns, insights, and recommendations
