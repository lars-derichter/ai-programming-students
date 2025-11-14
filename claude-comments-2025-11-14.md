# Review of AI Programming Slides - November 14, 2025

## Executive Summary

Overall, the slides present a **solid, pedagogically sound approach** to
teaching first-year programming students how to use AI tools effectively. The
structure is clear, examples are appropriate for the target audience, and the
emphasis on learning vs. copy-pasting is crucial. However, there are areas that
need updating to reflect recent AI developments (2024-2025) and some
redundancies that could be streamlined.

---

## 1. Relevance Assessment

### Still Highly Relevant ✅

- Core principles of prompt engineering remain valid
- Focus on learning vs. getting answers is timeless
- Socratic method approach is excellent
- Breaking down complex problems is fundamental
- Project planning methodology is sound

### Needs Updating ⚠️

- **AI capabilities have evolved significantly** since this was written
- **New AI tools and features** have emerged (Claude Projects, ChatGPT Canvas,
  GitHub Copilot improvements)
- **Context about AI models** is missing (students should know which models
  exist)
- **Multi-modal capabilities** (image analysis, code screenshots) not mentioned
- **AI-assisted IDEs** (Cursor, VS Code with Copilot) not discussed

---

## 2. Parts That Need Updating

### Section 1: Writing Better AI Prompts (lines 34-259)

**Current Issues:**

- Line 255-258: Memory/Custom Instructions section is outdated
  - ChatGPT now has better memory features
  - Claude has Projects with custom instructions
  - Should mention conversation length limits more clearly

**Recommended Updates:**

```markdown
### 🚸 Tip: Use Memory and Projects

**ChatGPT:**

- Use Memory feature (automatically remembers context)
- Set Custom Instructions for persistent preferences
- Use GPTs (custom ChatGPT versions) for specific tasks

**Claude:**

- Create Projects with custom instructions
- Add project knowledge (upload relevant files)
- Keep conversations focused (< 50 messages for best performance)

**General:**

- Save successful prompts in a personal prompt library
- Use version control for complex prompts
```

### Section 2: Learning vs Just Getting Answers (lines 261-439)

**Needs Addition:**

- Discussion about **AI hallucinations** and verification
- How to **test AI-generated code** before trusting it
- Mention that AI can be confidently wrong

**Suggested Addition (around line 350):**

```markdown
### ⚠️ AI Can Make Mistakes

Remember:

- AI sometimes "hallucinates" (makes up facts)
- Always test code before trusting it
- Verify explanations against official docs
- If something seems wrong, ask AI to double-check
- Learn to spot common AI errors

Example: "Can you verify this code works? Are there any edge cases I should
test?"
```

### Section 3: Understanding Things Different Ways (lines 442-589)

**Missing Modern Capabilities:**

- AI can now generate diagrams (Mermaid, ASCII art)
- Can analyze screenshots of code/errors
- Can explain code in images

**Suggested Addition (around line 465):**

```markdown
6. Visual Diagrams (flowcharts, architecture)
7. Screenshots Analysis (AI can read code from images)
8. Animated Examples (request step-by-step walkthroughs)
```

**Example Update for line 471:**

```markdown
### Example: Learning About Arrays

Ask AI: "I'm learning about Java ArrayLists. Could you:

1. Compare them to something from real life
2. Create a simple diagram (using Mermaid or ASCII art)
3. Show a visual representation of how items are stored
4. Give basic code examples with comments
5. Break it down step by step
6. Connect it to things I already know (like regular arrays)"
```

### Section 4: Practice with AI (lines 592-723)

**Good as is, but could add:**

- Reference to AI-assisted debugging
- Mention of explaining error messages
- How to share error messages effectively

**Suggested Addition (around line 640):**

```markdown
### Sharing Error Messages

When something goes wrong:

1. Copy the FULL error message
2. Include relevant code (not your entire project)
3. Explain what you expected to happen
4. Share what you've already tried

Example: "I'm getting this error: [paste error] Here's the relevant code: [paste
code] I expected it to [explain], but instead [what happens] I've tried [what
you tried] Can you help me understand what's wrong?"
```

### Section 5: Checking Your Progress (lines 726-906)

**Missing:**

- How to use AI for **code review**
- Asking AI to **generate test cases**
- Using AI to **find edge cases**

**Suggested Addition (around line 777):**

```markdown
### Ask AI to Generate Tests

"Can you create test cases for this function that check:

1. Normal inputs
2. Edge cases (empty, very large, negative)
3. Invalid inputs
4. Boundary conditions"

Then implement these tests yourself to verify your code works!
```

### Section 6: Planning Projects (lines 908-1125)

**Missing Modern Context:**

- How to use AI with **real development tools** (Git, package managers)
- Integration with **actual project workflows**
- Using AI for **documentation**

**Suggested Addition (around line 1010):**

```markdown
### Using AI in Your Workflow

Ask AI to help with:

- Writing clear commit messages
- Creating README files
- Documenting your code
- Understanding npm/Maven error messages
- Learning Git commands

Example: "I'm about to commit these changes: [describe changes] Can you suggest
a clear commit message following best practices?"
```

---

## 3. Redundant Parts

### Moderate Redundancy (Acceptable for Pedagogy) ⚠️

1. **Lines 59-150**: Prompt components are explained individually, then repeated
   in examples

   - **Verdict:** Keep it - repetition helps learning, but could be slightly
     condensed

2. **Lines 280-351**: "Wrong way vs. right way" appears multiple times

   - **Suggestion:** Consolidate into a single strong example, then refer back
     to it

3. **Lines 732-906**: Multiple "checking" frameworks overlap
   - **Suggestion:** Create one comprehensive checking framework instead of 5
     similar ones

### Specific Recommendations for Reduction:

**Lines 732-775 (Knowledge Checks, Building Tests, Code Review):** Could be
consolidated into one unified section:

```markdown
### Multi-Level Progress Checks

For any feature, check these levels:

**Level 1: Concept Understanding**

- Can you explain the concept?
- Quiz yourself with AI-generated questions

**Level 2: Basic Implementation**

- Can you build a minimal version?
- Does it work for the happy path?

**Level 3: Code Quality**

- Is your code clean and readable?
- Does it follow best practices?
- Ask AI for a code review

**Level 4: Problem Solving**

- Can you handle edge cases?
- Can you debug issues?
- Can you extend the feature?

Example prompt: "I've finished [feature]. Can you check my understanding by:

1. Asking me 3 questions about the concepts
2. Reviewing my code for best practices
3. Suggesting 2 edge cases I should test
4. Proposing a small extension to verify I can adapt it"
```

---

## 4. Missing Parts

### Critical Missing Content 🚨

#### A. **AI Tool Ecosystem (2024-2025)**

**Where to add:** After line 31 (Topics section) or as separate section

```markdown
### Which AI Tools Can You Use?

**Chat Interfaces:**

- ChatGPT (OpenAI) - GPT-4, GPT-4o
- Claude (Anthropic) - Claude 3.5 Sonnet
- Gemini (Google)
- Copilot (Microsoft)

**IDE Integration:**

- GitHub Copilot (VS Code, IntelliJ)
- Cursor AI
- Codeium (free alternative)

**Specialized:**

- v0.dev (UI components)
- Phind (developer search)

**Important:** Always check your university's policy on which tools you can use
for assignments!
```

#### B. **Code Ownership and Academic Integrity**

**Where to add:** Before line 1154 or as Section 7

```markdown
## 7. AI, Academic Integrity, and Code Ownership

### Understanding the Rules

**Check with your instructors:**

- Which AI tools are allowed for which assignments?
- Do you need to cite AI-generated code?
- Are there assignments where AI is not allowed?

### When AI is Allowed

**Best Practices:**

- Always understand any code you submit
- Be ready to explain your code line-by-line
- Modify AI suggestions to fit your needs
- Use AI as a tutor, not a replacement for learning

### When AI is NOT Allowed

**Alternatives:**

- Use official documentation
- Read textbooks and course materials
- Ask classmates (if collaboration is allowed)
- Attend office hours
- Use non-AI resources (MDN, Stack Overflow archives)

### The Bottom Line

**You are responsible for:**

- Understanding all code you submit
- Following your university's AI policy
- Learning the concepts, not just getting solutions
- Being honest about how you solved problems
```

#### C. **Limitations and Pitfalls**

**Where to add:** After Section 1 or as Section 2.5

````markdown
## AI Limitations You Should Know

### What AI Gets Wrong

**Common Issues:**

1. **Hallucinations:** AI confidently states incorrect "facts"
2. **Outdated Information:** Training data has a cutoff date
3. **Context Limitations:** AI can't see your entire project
4. **Inconsistency:** Different responses to same question
5. **Security Issues:** May suggest vulnerable code patterns

### How to Protect Yourself

**Always:**

- Test every piece of code AI generates
- Verify "facts" against official documentation
- Check for security vulnerabilities (SQL injection, XSS)
- Ask AI: "Are there any problems with this code?"
- Get a second opinion (another AI, instructor, peer)

**Red Flags:**

- AI suggests deprecated features
- Code has no error handling
- Solution seems too simple for complex problem
- AI can't explain why something works
- Code includes hardcoded credentials

### Example: Catching AI Mistakes

❌ **Bad:** Copy AI code directly

```java
// AI suggested code
String query = "SELECT * FROM users WHERE name = '" + userName + "'";
```
````

✅ **Good:** Question and improve "This code looks vulnerable to SQL injection.
Can you show me a safer way using PreparedStatement?"

````

#### D. **Working with Java (Your Students' Context)**
**Where to add:** Throughout examples - currently too HTML/CSS/JavaScript focused

**Current problem:** Lines 64-68, most examples use JavaScript. Students at this point know Java better.

**Suggested Java Examples to Add:**

```markdown
### Example: Learning Java Methods (Section 2)

Instead of:
❌ "Write a method to calculate tax"

Try:
✅ "I'm learning Java methods and parameters.

Could you help me understand how to calculate prices with tax by:

1. Explaining what a method signature means
2. Showing how parameters and return types work
3. Creating a simple example that calculates total price with tax
4. Helping me modify it to handle different tax rates
5. Asking me questions to check I understand
6. Giving me a similar problem to practice (e.g., calculating discounts)

Please explain any terminology I might not know yet!"
````

```markdown
### Example: Java ArrayList Practice (Section 4)

"I need to build a simple student grade tracker. Could you help me:

1. Understand which collection type to use (ArrayList vs array)
2. Break down the problem into small methods:
   - Adding a grade
   - Calculating average
   - Finding highest/lowest
3. Guide me through implementing ONE method at a time
4. Help me test each method before moving on

I know: basic Java syntax, loops, conditionals I'm learning: ArrayLists,
methods, data structures"
```

#### E. **Debugging with AI**

**Where to add:** New section between 4 and 5, or extend Section 4

```markdown
## Debugging with AI: From Error to Solution

### Reading Error Messages

Java error messages can be intimidating! AI can help translate them.

**Good debugging prompt:**
```

I'm getting this error when I run my Java program:

```
Exception in thread "main" java.lang.IndexOutOfBoundsException: Index 5 out of bounds for length 5
    at java.base/java.util.ArrayList.get(ArrayList.java:427)
    at StudentGrades.getGrade(StudentGrades.java:23)
```

I'm trying to [explain what you're doing] Here's the relevant code: [paste code
around line 23]

Can you:

1. Explain what this error means in simple terms
2. Help me understand WHY it's happening
3. Guide me to find the problem myself (don't just fix it)
4. Suggest how to prevent this in the future

```

### The Debugging Loop

1. **Read the error carefully**
2. **Find the line number** in the stack trace
3. **Share context with AI** (error + relevant code)
4. **Ask for guidance**, not solutions
5. **Test your fix**
6. **Understand why it works**

### Common Java Errors AI Can Help With

- `NullPointerException`: Trying to use something that doesn't exist
- `IndexOutOfBoundsException`: Accessing array/list position that doesn't exist
- `ClassCastException`: Trying to convert types incorrectly
- Compilation errors: Syntax mistakes, wrong imports
```

#### F. **Comparing AI Responses**

**Where to add:** Section 1 or 2

```markdown
### Getting Multiple Perspectives

Different AI models have different strengths:

- Try asking the same question to ChatGPT AND Claude
- Compare their explanations
- See which teaching style works better for you
- Use one to verify the other

Example: "I got this explanation from another AI: [paste explanation] Can you
verify if it's correct and add anything missing?"
```

#### G. **Practical Workflow Integration**

**Where to add:** New section or extend Section 6

```markdown
## Daily AI Workflow for Programming Students

### Morning Coding Session

1. **Review yesterday's code** with AI
   - "Here's what I built yesterday. Can you review it for improvements?"
2. **Plan today's work**
   - "Today I want to add [feature]. Can you help me break it down?"

### During Coding

3. **Understand new concepts**
   - "I encountered [concept] in the assignment. Can you explain it?"
4. **Debug issues**
   - Share errors, get guided help
5. **Check your work**
   - "Does this code follow best practices?"

### End of Day

6. **Reflect on learning**
   - "Quiz me on what I learned today about [topic]"
7. **Plan next steps**
   - "What should I practice next to strengthen this knowledge?"

### Before Submitting Assignments

8. **Final review checklist:**
   - Does my code work for all test cases?
   - Do I understand every line?
   - Can I explain it to my instructor?
   - Have I followed the assignment requirements?
   - Have I checked my university's AI usage policy?
```

---

## 5. Suggestions for Improvement

### Content Structure

#### 1. Add a Quick Reference Section

**Location:** After Topics, before Section 1

```markdown
## Quick Prompt Templates

### For Learning a New Concept

"I'm a first-year programming student learning [topic]. I know: [list what you
know] I don't understand: [specific confusion] Could you explain [topic] using:

1. A real-life analogy
2. Simple code example
3. Common mistakes to avoid"

### For Debugging

"I'm getting this error: [error message] Relevant code: [code snippet] Expected:
[what should happen] Actual: [what's happening] Already tried: [what you've
tried] Can you help me understand what's wrong?"

### For Code Review

"Please review this [Java/HTML/CSS] code for:

- Best practices
- Potential bugs
- Readability
- Performance issues Keep in mind I'm a beginner."

### For Project Planning

"I need to build [project description] I know: [your skills] Timeline:
[available time] Can you help me:

1. Break it into phases
2. Identify what I need to learn
3. Suggest a realistic timeline
4. Spot potential problems"
```

#### 2. Reorganize for Better Flow

**Current:** 1. Prompts → 2. Learning → 3. Different Ways → 4. Practice → 5.
Checking → 6. Planning

**Suggested:**

1. **Introduction & Tool Landscape** (new)
2. **Writing Better Prompts** (current 1)
3. **Learning vs. Getting Answers** (current 2) + **AI Limitations** (new)
4. **Daily AI Workflow** (new) combining current 3, 4, 5
5. **Project Planning** (current 6)
6. **Academic Integrity** (mostly new, expand current line 1154)
7. **Quick Reference & Resources** (new)

#### 3. Add Interactive Elements

After each major section:

```markdown
### 💡 Try This Now

[5-minute exercise with specific task]

### 🤔 Reflection Questions

- What surprised you about this approach?
- How will you use this in your next assignment?
- What questions do you still have?
```

#### 4. Add Success Stories / Anti-Patterns

```markdown
### ✅ Success Story

"I was stuck on a loop problem for 2 hours. Instead of asking AI for the
solution, I asked it to explain how different loop types work. That helped me
realize I needed a while loop, not a for loop. Then I wrote it myself!" -
Previous Student

### ❌ Anti-Pattern to Avoid

"I copied AI code for my ArrayList assignment without understanding it. During
the practical exam, I couldn't do similar problems because I never actually
learned it. Had to retake the course." - Anonymous
```

### Language and Clarity

#### 1. Current Strengths

- Clear, simple language appropriate for beginners
- Good use of examples
- Emoji use is minimal and purposeful ✅

#### 2. Minor Improvements

**Line 387-394:** "Hardcore Learning Mode" is informal

- Consider: "Advanced Learning: The Socratic Method"

**Line 485:** "Student Register" example is excellent

- Add: Similar examples for other Java concepts (inventory system for HashMaps,
  playlist for LinkedList)

**Lines 794-800:** JavaScript example

- Change to Java to match student knowledge

### Pedagogical Improvements

#### 1. Add Learning Objectives

Before each section:

```markdown
### Learning Objectives

By the end of this section, you will be able to:

- [ ] Explain why context matters in prompts
- [ ] Write prompts that include context, role, task, and format
- [ ] Identify weak prompts and improve them
```

#### 2. Add Knowledge Checks

After each section:

```markdown
### Check Your Understanding

1. What are the 4 essential parts of a good prompt?
2. Why is asking AI for direct answers problematic?
3. Try explaining [concept] to a classmate

[Show answers button in presentation]
```

#### 3. Progressive Complexity

Currently jumps around in difficulty. Suggest:

- Section 1-2: Basic concepts (current level ✅)
- Section 3-4: Intermediate application (needs slight elevation)
- Section 5-6: Advanced integration (good, but add more depth)

### Visual and Format Improvements

#### 1. Add Diagrams

**Line 673-681 (Learning Loop):** Create actual flowchart visual

**Suggested addition at line 456:**

```markdown
### The Learning Pyramid (How to use AI at each level)
```

         [Remember]           → Ask AI for facts, definitions
            ↓
        [Understand]         → Ask AI for explanations, examples
            ↓
         [Apply]             → Ask AI to guide you through practice
            ↓
        [Analyze]            → Ask AI to help you debug, review
            ↓
        [Evaluate]           → Use AI to check your work
            ↓
         [Create]            → Use AI to plan, then build yourself

```

```

#### 2. Color Coding for Examples

Use consistent formatting:

- ❌ Bad examples: Always use this emoji
- ✅ Good examples: Always use this emoji
- 💡 Tips: Use this for pro tips
- ⚠️ Warnings: Use for common mistakes
- 🚸 Advanced/Careful: Use for complex topics

#### 3. Side-by-Side Comparisons

Currently some comparisons are on separate slides. Consider:

```markdown
### Before and After

| ❌ Weak Prompt       | ✅ Strong Prompt                                                                                                                                    |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- |
| "Help me with forms" | "I'm learning HTML forms. I know basic HTML. Can you explain how the <form> element works and show me a simple example with name and email fields?" |
```

---

## 6. Technology-Specific Updates

### Update for 2024-2025 AI Features

#### Claude-Specific Features

```markdown
### Using Claude Effectively

**Strengths:**

- Long conversations with good context retention
- Excellent at explaining complex concepts
- Strong code review capabilities
- Good at following structured instructions

**Tips:**

- Use Projects for course-specific contexts
- Upload assignment instructions as project knowledge
- Create separate projects for different courses
- Use Artifacts feature for code generation

**Limitations:**

- No code execution (can't run Java for you)
- Can't access external resources during conversation
- May need reminders in very long conversations
```

#### ChatGPT-Specific Features

```markdown
### Using ChatGPT Effectively

**Strengths:**

- Large ecosystem of custom GPTs
- Good at step-by-step tutorials
- Code Interpreter for testing Python (not Java)
- DALL-E for creating diagrams

**Tips:**

- Use Memory for persistent preferences
- Try Canvas feature for code editing
- Explore GPTs created for programming education
- Use voice mode for conversational learning

**Limitations:**

- Memory can sometimes include incorrect info
- May confidently provide outdated information
- Shorter effective context than Claude
```

### IDE Integration Update

**New section needed:**

```markdown
## AI in Your Code Editor

### GitHub Copilot (If Your School Provides It)

**What it does:**

- Suggests code as you type
- Can generate entire functions
- Understands context from your project

**How to learn with it:**

- Read suggestions before accepting
- Try writing code yourself first, then compare
- Use comments to guide suggestions
- Ask yourself: "Why did it suggest this?"

**Warning:**

- Don't blindly accept suggestions
- Copilot can suggest buggy or insecure code
- Always review and understand
- Test everything

### Free Alternatives

- **Codeium:** Free Copilot alternative
- **Tabnine:** Free tier available
- **VS Code + Chat:** Use AI chat extensions
```

---

## 7. Content for Each Student Knowledge Level

### Current State

- Good for Q2 students (HTML, CSS, basic Java) ✅
- Could add tracks for different speeds

### Suggested Additions

**For Struggling Students:**

```markdown
### If You're Finding Programming Hard

AI can help, but it's not a replacement for fundamentals.

**Use AI to:**

- Explain concepts in different ways
- Get extra practice problems
- Understand error messages
- Review before exams

**Don't use AI to:**

- Skip understanding basics
- Complete assignments you can't explain
- Avoid doing practice exercises
- Replace asking your instructor

**Red flag:** If you can't do basic problems without AI, you need to strengthen
fundamentals first.
```

**For Advanced Students:**

```markdown
### If You're Ahead

Use AI to go deeper:

- "What are advanced [topic] patterns?"
- "How would this work in a large application?"
- "What are the performance implications?"
- "Show me industry best practices"
- "What are common interview questions about this?"

Challenge yourself:

- Build features beyond assignment requirements
- Ask AI about concepts not yet covered
- Compare multiple approaches
- Learn additional technologies
```

---

## 8. Assessment and Practice

### Currently Missing: Self-Assessment Tools

Add section:

```markdown
## How to Know You're Using AI Right

### Green Flags 🟢

- You can explain all your code without AI's help
- You spot errors before AI does
- You know when AI is wrong
- You can solve similar problems alone
- You understand why solutions work
- Your skills improve over time

### Yellow Flags 🟡

- You need AI for every small problem
- You can't spot AI mistakes
- You copy without understanding
- You struggle without AI access
- Your code works but you don't know why

### Red Flags 🔴

- You submit code you can't explain
- You panic during exams (no AI allowed)
- You can't solve basic problems independently
- You've stopped reading documentation
- You don't understand error messages

### If You See Yellow/Red Flags

1. Take a break from AI for simple problems
2. Redo earlier exercises without AI
3. Focus on fundamentals
4. Ask your instructor for help
5. Form study groups (human learning!)
```

---

## 9. Cultural and Contextual Adjustments

### Belgian/European Context

**Good:** Lines 12-19 establish cultural context ✅

**Could add:**

```markdown
### Why This Matters in Belgium/Europe

**GDPR Awareness:**

- Be careful what code you paste into AI (no personal data!)
- Your university may have preferred AI tools (data protection)
- Some tools store conversations, others don't

**European AI Act:**

- AI is being regulated in the EU
- Your university must balance innovation with compliance
- Policies may change - stay informed

**Multilingual Advantage:**

- You can ask AI in Dutch, French, English
- Try explaining concepts in your strongest language
- Use AI to help translate technical terms
```

---

## 10. Specific Line-by-Line Issues

### Minor Errors/Inconsistencies

1. **Line 256:** "Claude it is important not to get too long conversations"

   - Update: "with Claude, keep conversations focused (under 50 messages
     recommended)"

2. **Line 589:** "(teaching is the best way to learn, I am always learning 😊)"

   - This is good personal touch! Keep it.

3. **Line 1154:** "# Check with University policy what you can upload and
   use!!!"

   - This is critical but buried. Move to earlier and expand significantly.

4. **Line 1160:** "custom GPT's" should be "custom GPTs" (no apostrophe)

5. **Lines 64-68:** Lists "JavaScript variables and functions" but students know
   Java
   - Change example to reflect Java knowledge
   - Or explicitly state: "If you were learning JavaScript..." to show
     transferability

### Tone Inconsistencies

**Generally good and consistent. Minor notes:**

- Lines 267-275: Image references (lazy.png, work.png) - ensure these are
  available
- Most slides are 2-3 items, some have 7-8 (cognitive overload)
  - Example: Line 47-56 has 7 parts - consider splitting

---

## 11. Practical Implementation Suggestions

### For the Presentation

1. **Timing:** With practice exercises, this is 90-120 minutes

   - Consider 2-session format
   - Session 1: Sections 1-3 (Prompting + Learning)
   - Session 2: Sections 4-6 (Practice + Planning) + New Academic Integrity

2. **Interactive Elements:**

   - Use live demos of ChatGPT/Claude
   - Show real examples from past student work (anonymized)
   - Do one exercise together as a class

3. **Follow-up Materials:**
   - Create printable "prompt template cheat sheet"
   - Provide example conversation transcripts
   - Share curated list of practice problems

### For Students After Presentation

**Create takeaways:**

```markdown
## Your AI Learning Action Plan

### This Week

- [ ] Set up ChatGPT and/or Claude account
- [ ] Add your student context to memory/project
- [ ] Try one assignment using the learning approach
- [ ] Save one successful conversation

### This Month

- [ ] Build personal prompt library
- [ ] Compare AI responses for accuracy
- [ ] Use Socratic method for one difficult topic
- [ ] Review AI usage in 3 assignments

### This Quarter

- [ ] Complete one project with AI assistance
- [ ] Can explain all submitted code
- [ ] Identify areas where you're too dependent
- [ ] Teach approach to classmate
```

---

## 12. Resource Additions

### Currently Missing: Further Learning

Add section before "Thank You":

```markdown
## Resources for Continued Learning

### Official Documentation

- Java: https://docs.oracle.com/en/java/
- MDN Web Docs: https://developer.mozilla.org/
- W3Schools: https://www.w3schools.com/

### AI-Specific Learning

- OpenAI Prompt Engineering Guide
- Anthropic's Claude Documentation
- GitHub Copilot Best Practices

### Recommended Approach

1. Use official docs for reference
2. Use AI to explain what you don't understand
3. Practice without AI regularly
4. Join study groups (humans + AI = best)

### When AI Isn't Enough

- Stack Overflow (read, don't just copy)
- Your textbook (yes, really!)
- Office hours with instructors
- Peer study groups
- Online courses (Coursera, edX)
```

---

## Summary of Action Items

### High Priority (Must Do)

1. ✅ **Add Section on Academic Integrity** (lines 1154 expansion)
2. ✅ **Update AI Tool Landscape** (new section after Topics)
3. ✅ **Add AI Limitations Section** (after Section 1)
4. ✅ **Convert More Examples to Java** (throughout)
5. ✅ **Update Memory/Projects Info** (line 255-258)
6. ✅ **Add Debugging with AI Section** (new section)
7. ✅ **Add Self-Assessment Framework** (new section)

### Medium Priority (Should Do)

8. ✅ **Add Quick Reference Section** (beginning)
9. ✅ **Reorganize for Better Flow** (see Section 5)
10. ✅ **Add Learning Objectives** to each section
11. ✅ **Create Printable Cheat Sheet** (supplementary)
12. ✅ **Add IDE Integration Section** (GitHub Copilot)
13. ✅ **Expand Practice Exercises** with solutions
14. ✅ **Add Success/Failure Stories**

### Low Priority (Nice to Have)

15. ✅ **Add Diagrams** (learning pyramid, workflow)
16. ✅ **Create Comparison Tables** (side-by-side)
17. ✅ **Add Multi-Level Tracks** (struggling/advanced)
18. ✅ **Add GDPR/European Context** (data privacy)
19. ✅ **Create Follow-up Materials** (action plan)
20. ✅ **Add Resources Section** (further learning)

### Optional Enhancements

21. Record video examples of good AI conversations
22. Create custom GPT specifically for your course
23. Build interactive web version of slides
24. Develop automated prompt evaluator
25. Create student showcase of AI-assisted projects

---

## Conclusion

This is a **strong foundation** for teaching AI literacy to programming
students. The pedagogical approach is sound, examples are relevant, and the
emphasis on learning over copying is crucial for student success.

**Key strengths:**

- Structured, logical flow
- Emphasis on understanding over answers
- Practical exercises throughout
- Socratic method introduction
- Project planning focus

**Key gaps:**

- Missing 2024-2025 AI landscape
- Insufficient academic integrity coverage
- Too few Java-specific examples
- No debugging section
- Limited discussion of AI limitations

**Estimated update effort:**

- High priority items: 4-6 hours
- Medium priority items: 6-8 hours
- Low priority items: 4-6 hours
- Total: 14-20 hours for comprehensive update

**Impact potential:** By addressing the high-priority items, you'll have a
**significantly more effective** presentation that:

1. Prepares students for the current AI landscape
2. Sets clear ethical boundaries
3. Provides practical, context-appropriate examples
4. Teaches sustainable learning habits
5. Builds student confidence and competence

The slides are good now; with these updates, they'll be **excellent** and remain
relevant through 2025-2026.

---

## Appendix: Example Updated Slides

### Example 1: Updated Section 1 Opener

```markdown
## 1. Understanding AI Tools & Writing Better Prompts

### What We'll Cover

- Which AI tools are available (and allowed!)
- What AI can and cannot do
- How to write prompts that help you learn
- Common AI mistakes to avoid

### By the End

You'll be able to get helpful, educational responses from AI tools while
building real understanding.
```

### Example 2: New Academic Integrity Section

```markdown
## 7. Academic Integrity and AI

### The Core Principle

**You must understand and be able to explain any code you submit.**

### Thomas More's Policy

[INSERT YOUR SPECIFIC POLICY HERE]

### General Guidelines

✅ Allowed:

- Using AI to understand concepts
- Getting explanations of error messages
- Asking for different approaches
- Code review and suggestions

⚠️ Check First:

- Generating code snippets
- Debugging assistance
- Project planning help

❌ Never Allowed Without Permission:

- Submitting AI code as your own
- Using AI during exams (unless specified)
- Copying without understanding

### When in Doubt

**ASK YOUR INSTRUCTOR**

Better to ask than to face academic misconduct charges.

### The Real Test

"Can I complete this work during an exam without AI?" If no, you're relying too
much on AI.
```

### Example 3: Updated Java Example

```markdown
## Example: Learning Java Methods (Better)

### Context

"I'm a first-year student at Thomas More, and I'm learning Java methods. I
understand:

- Basic syntax (variables, if-statements, loops)
- How to write simple programs
- Basic data types (int, String, double)

I'm currently learning:

- How methods work
- Parameters and return types
- Method overloading"

### Task

"I need to create a method that calculates the final price of a product after
applying tax. Instead of just giving me the code, could you:

1. Explain what a method signature is
2. Show me what parameters I'll need
3. Guide me through writing it step-by-step
4. Help me understand what each part does
5. Give me a similar problem to practice (e.g., calculating discount)

Please keep it simple - no advanced features yet!"

### Why This Works

- Clear context (year, knowledge level)
- Specific task related to coursework
- Asks for guidance, not solutions
- Includes practice component
- Appropriate scope for skill level
```

---

_Review completed: November 14, 2025_ _Reviewer: Claude (Anthropic)_ _Next
review recommended: September 2025 (before next academic year)_
