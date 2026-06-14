# Novel Writer AI Tool Research

Research on what serious novel writers actually want from AI writing tools.

## Sources
- Reddit (r/writing, r/WritingWithAI, r/ChatGPTPro)
- Zhihu discussions
- V2EX forums
- Writing community forums

## Key Findings

### 1. Long-form Coherence (最高痛点)
- Current tools lose context after ~5000-10000 words
- Characters forget their backstories
- Plot threads get dropped
- Timeline inconsistencies multiply

### 2. Character Consistency
- AI forgets character voices/speech patterns
- Physical descriptions change between chapters
- Character motivations shift without author intent
- Relationships between characters get confused

### 3. Plot Management
- No structural awareness (acts, arcs, pacing)
- Cannot maintain subplots across chapters
- Foreshadowing and payoff management impossible
- Conflict escalation/resolution not understood

### 4. World-building
- Magic systems/rules get violated
- Political/geographical details inconsistent
- Historical timelines muddled
- Cultural details mixed up

### 5. Current Tool Failures
- Too "assistant-like" rather than writer-focused
- Lack of story bible/world bible support
- No version control for story elements
- Cannot learn writer's style/voice
- Token limits kill continuity
- No semantic search across manuscript
- Poor chapter/scene management
- No character relationship graphs
- Missing plot outline integration

## What Writers Actually Want

### High Priority
1. **Persistent character sheets** that AI can reference
2. **World bible integration** with automatic consistency checking
3. **Scene-by-scene composition** with structural awareness
4. **Style learning** from author's own writing
5. **Semantic search** across entire manuscript
6. **Automatic inconsistency detection** for plot/character/world

### Medium Priority
7. **Multiple POV management** 
8. **Timeline visualization and management**
9. **Chapter/act structure templates**
10. **Character voice differentiation**
11. **Subplot tracking**
12. **Research integration** (historical facts, locations)

### Lower Priority but Requested
13. **Collaborative editing** with AI
14. **Export to publishing formats**
15. **Revision/draft management**
16. **Reader feedback integration**

## Platform-Specific Pain Points

### Reddit Users
- Want "set it and forget it" consistency
- Frustrated with constant re-prompting
- Need tools that understand genre conventions
- Want to use AI for first drafts, not polished prose

### Zhihu Users (中文写作)
- Chinese language models lack understanding of web novel conventions
- Want better 长篇 (long-form) support
- Need wuxia/xianxia genre awareness
- Character naming consistency (especially with similar-sounding names)
- Chapter-by-chapter serialization support

### V2EX Users
- Want local/privacy-focused tools
- API access for custom workflows
- Markdown-native editing
- Version control for manuscripts
- Integration with Obsidian/other tools

### Writing Forum Users
- Want to maintain creative control
- Need AI to suggest, not dictate
- Want structural feedback (pacing, tension)
- Need character arc tracking
- Want dialogue improvement tools

## Gaps in Current Market

1. **No "story engine"** that maintains state across sessions
2. **No automatic continuity checking**
3. **No integrated world-building wiki**
4. **No character relationship mapping**
5. **No plot structure visualization**
6. **No style consistency enforcement**
7. **No sub-plot thread tracking**
8. **No semantic search across full manuscript**
9. **No automatic foreshadowing tracking**
10. **No POV/voice management**

## Technical Requirements Writers Mention

- Handle 100k+ word manuscripts
- Process character sheets of 20+ characters
- Track 5+ simultaneous plot threads
- Maintain world bible with 100+ entries
- Remember details from chapter 1 when writing chapter 50
- Support multiple revision passes
- Allow manual overrides of AI suggestions
- Provide confidence scores for consistency checks
