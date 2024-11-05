# AI for programming students

---

## Who Am I?

- Lars De Richter
- Teach programming at Thomas More University of Applied Sciences in Belgium (Antwerp)

---

## Why you should come to Belgium?

- Bad weather (but not as bad as in Finland)
- Quiet, sturdy people (but not as quiet as Finns)
- Very many people (11mio) in a very small country (2/3d Estonia)
- The best beer in the world (and cheap)
- The best chocolate in the world
- French fries are really Belgian!

---

Longer intorduction tomorrow

---

## Topics

1. Prompt Techniques
2. Learning vs Solving
3. Using AI as a Learning Buddy
4. Learning Checkpoints
5. AI for Project Planning(as a Student)

---

## 1. Prompt Techniques

---

### Why Context Matters

- AI doesn't know what you know
- AI doesn't know what you want
- AI doesn't know your constraints
- But you can tell it all of these things!

---

### Elements of an Effective Prompt

- General Context
- Role
- Task
- Format
- Audience
- Scope
- Steps (when needed)

---

### General Context

Explains your situation and background

Example:
"I'm a first-year web development student working on my portfolio project.
I know HTML and CSS basics, and I'm learning JavaScript fundamentals
(variables, loops, functions)."

---

### Role

Defines who you want the AI to be

Example:
"As an expert web developer with experience in teaching beginners,
please help me understand..."

"Acting as a senior front-end developer who specializes in
writing clean, maintainable code..."

"Take the role of an accessibility expert who helps developers
make their websites WCAG compliant..."

---

### Task

Clearly states what you want to achieve

Example:  
❌ "Make a form"  
✅ "I need to create a contact form that collects a visitor's name,  
email, and message. The form should validate that the email is properly
formatted before submission."

---

### Format

Specifies how you want the information presented

Example:
"Please provide the solution as:

- HTML structure first
- CSS in a separate block
- Comments explaining each major section
- No frameworks - just vanilla HTML/CSS"

---

### Audience

States who will use your code/solution

Example:
"This needs to be accessible for:

- Mobile users
- Screen readers
- Elderly users who might not be tech-savvy
  Please keep the interface simple and intuitive."

---

### Scope

Defines the boundaries of what you need

Example:
"For now, I only need the front-end part:

- Form layout and styling
- Basic JavaScript validation
- No backend/database code yet
- No advanced features like auto-complete"

---

### Steps (When Needed)

Break down complex tasks into smaller parts

Example:
"Please help me build this form in these steps:

1. First, show me the basic HTML structure
2. Then, add CSS for layout and styling
3. Finally, add JavaScript for validation
   Explain each step before moving to the next one."

---

### Bad Prompt Example

"Fix this code"

```html
<div class="card">
  <h2>Title</h2>
  <p>Text</p>
</div>
```

❌ No context about the problem  
❌ No information about desired outcome  
❌ No mention of skill level

---

### Better Prompt Example

"I'm a first-year web development student learning about CSS flexbox.
This card component should be centered on the page, but it's not working.
Can you explain what I need to add and why it works?"

```html
<div class="card">
  <h2>Title</h2>
  <p>Text</p>
</div>
```

✅ Mentions learning context  
✅ States the problem  
✅ Asks for explanation

---

### Bad Prompt Example

"Write JavaScript code for a todo list"

❌ No specification of features  
❌ No mention of code complexity  
❌ No indication of current knowledge

---

### Better Prompt Example

"I'm learning JavaScript basics (variables, functions, if-else statements).
Can you help me create a simple todo list where I can:

1. Add items to a list
2. Display them on the page

Please use basic DOM manipulation without advanced concepts.
Explain each part of the code so I can learn from it."

✅ States knowledge level  
✅ Specifies features  
✅ Asks for explanations

---

### Key Takeaways

1. Always provide your context as a student
2. Specify what concepts you know
3. Ask for explanations, not just solutions
4. Break down complex requests into steps
5. Be clear about what you want to learn

---

### Practice Exercise

Take this basic prompt and improve it using all elements we discussed:

❌ "Help me make a website header with a logo and navigation"

Take 5 minutes to rewrite it!

---

### Example Solution

"As an expert web developer and accessibility specialist,

I'm a first-year web development student building my first portfolio site.
I understand HTML basics and CSS flexbox.

I need help creating a responsive header with:

- A logo on the left
- Navigation menu on the right
- Mobile-friendly design

---

Please provide:

- HTML structure with semantic tags
- CSS using flexbox
- Comments explaining the layout choices
- No frameworks or complex features

The site will be used by potential employers and should work well on all devices.

---

Could you guide me through this in these steps:

1. Basic HTML structure
2. Desktop styling
3. Mobile responsive adjustments"

---

### Your Turn!

Improve this prompt:

❌ "How do I make a photo gallery?"

Use:

- General Context
- Role
- Task
- Format
- Audience
- Scope
- Steps

(5 minutes)

---

### Photo Gallery - Example Solution

"As a senior front-end developer with expertise in responsive design and image optimization,

I'm a first-year web development student working on my photography portfolio. I know HTML, basic CSS (including flexbox and grid), and basic JavaScript (loops, functions).

I need to create a responsive photo gallery that:

- Displays a grid of photos
- Shows photo titles on hover
- Works well on both desktop and mobile

---

Please provide the solution using:

- Semantic HTML
- CSS Grid for layout
- Basic JavaScript for image loading
- Detailed comments explaining each technique
- No external libraries or frameworks

---

The gallery will be viewed by:

- Photography enthusiasts
- Potential clients
- Mobile users
- People with various internet speeds

---

Scope:

- Maximum 12 images
- Simple hover effects
- Basic lazy loading
- No lightbox or advanced features yet

---

Please guide me through:

1. HTML structure for the gallery
2. CSS Grid layout and hover effects
3. Basic JavaScript for image loading
4. Mobile responsive considerations
5. Performance optimization tips"

---

### What Makes This Better?

- Clear about skill level
- Specific features needed
- Considers performance
- Mentions target audience
- Sets realistic scope
- Asks for explanations
- Breaks down the process

---

### Refine and repeat

- When the answer is not exactly what you want, tell AI what is wrong with it.
- If you have a conversation with a good answer, reuse it to create similar answers.

---

### 🚸 Tip: Custom instructions

Add some of this to ChatGPT's custom instructions or create a Claude.ai project with custom instructions.

---

### Stay critical

Treat AI as a (somewhat dumb) assistant that always tries to do its hardest to help you, but needs guidance and quality controll

---

### Key Takeaways

1. More detail = better results
2. Be clear about your knowledge level
3. Break down complex features
4. Think about your end users
5. Ask for explanations to learn
6. Refine and repeat
7. Stay critical

---

## 2. Learning vs Solving

---

### Two Approaches

❌ "Give me the solution"
✅ "Help me learn how to solve this"

---

### Example: Bad Approach

"Write code for a responsive navigation menu with a hamburger button"

- Gets you a solution
- But what have you learned?
- Can you modify it later?
- Will you understand similar problems?

---

### Example: Learning Approach

"I'm learning about responsive navigation menus. Could you:

1. First explain the key components needed
2. Guide me through the basic HTML structure
3. Help me understand the CSS principles involved
4. Show me how the JavaScript part works

Please check my understanding at each step."

---

### Prompt Elements for Learning

- "Can you explain the concept first?"
- "What are the important principles to understand?"
- "Could you guide me step by step?"
- "Why does this approach work better than alternatives?"
- "What common mistakes should I watch out for?"

---

### Interactive Learning Example

Instead of:
❌ "Code a form validation function"

Try:
✅ "I'm learning form validation. Could you:

1. Explain what we need to validate and why
2. Show me a simple example for one field
3. Let me try to write validation for the next field
4. Review my attempt and suggest improvements"

---

### Debugging Approach

Instead of:
❌ "Fix this code"

Try:
✅ "This code isn't working as expected. Could you:

1. Help me understand what each part does
2. Guide me in finding the problem
3. Explain why the error occurs
4. Suggest how I might fix it myself"

---

### Practice Makes Perfect

Turn this request:
"Create a function that calculates the total price with tax"

Into a learning-focused prompt that:

- Asks for explanations
- Breaks down the concept
- Includes practice steps
- Requests verification of understanding

---

### Sample Solution

"I'm learning JavaScript functions and calculations.

Could you help me understand how to create a function that calculates total price with tax by:

1. First explaining the basic concepts involved (functions, parameters, calculations)
2. Showing me a simple example with one fixed tax rate
3. Guiding me to modify it for different tax rates
4. Asking me questions to check my understanding
5. Giving me similar small challenges to practice

Please point out any common mistakes or best practices along the way."

---

### Hardcore: Socratic Method

When you really want to learn

---

### The Socratic Approach

Tell AI:
"Please use the Socratic method. Don't give me direct answers.
Instead, guide me with questions that will help me discover
the solution myself."

---

### Example: Regular Prompt

"How do I center a div with CSS?"

vs.

### Socratic Version

"I'm learning CSS layout. Could you use the Socratic method to help me
discover how to center a div? Ask me questions that will guide my thinking. Under no circumstances give me the straight-up."

AI might respond:

- "What properties do you know that affect element positioning?"
- "How does the display property affect layout?"
- "What have you tried so far?"

---

### Socratic Learning Example

Instead of:
❌ "How do I make this responsive?"

Try:
✅ "I want to understand responsive design principles.
Could you ask me guiding questions that will:

- Help me analyze my current layout
- Lead me to discover breakpoints
- Guide me to find solutions myself"

---

### Exercise

- Ask for the next topic on your course and try Socratic method for 10 minutes.
- What have you learned?
- How was the experience?

---

### Benefits of Socratic Learning

- Deeper understanding
- Better retention
- Improved problem-solving skills
- More engaging learning process
- Builds confidence in your abilities

---

### Remember

- Learning > Solution
- Understanding > Copy-Pasting
- Process > Result
- Questions > Answers
- Practice > Theory

---

## 3. Using AI as a Learning Buddy

From understanding to mastery

---

### Breaking Down the Problem

Instead of diving in, ask AI to:

- Analyze the requirements
- Identify key components
- List necessary skills/concepts
- Suggest a learning sequence

Example:
"Can you help me break down this assignment into smaller,
manageable parts and identify what I need to learn for each part?"

---

### Step-by-Step Solution

For each component:

1. Explain the concept
2. Show a basic example
3. Guide through implementation
4. Verify understanding

Example:
"Let's focus on the form validation part first.
Could you explain the basic concept, then guide me
through implementing it step by step?"

---

### Debugging & Understanding

When stuck:

- Share your code
- Explain what you expected
- Describe what's happening instead
- Ask for hints before solutions

Example:
"My form validation isn't working. Here's my code and what I expected.
Can you help me understand where my logic might be wrong?"

---

### Making Small Changes

Once it works:

"Now that this works, could we:

- Add another field?
- Change the validation rules?
- Improve the user feedback?
- Make it more accessible?

Help me understand how each change affects the code."

---

### Creating Similar Problems

Build confidence through practice:

"Could you create a similar but different assignment that:

- Uses the same concepts
- Has slightly different requirements
- Requires small modifications to the solution
- Helps me practice what I learned?"

---

### Practice Loop

👉 Understand the problem
👉 Break it down
👉 Solve step by step
👉 Debug if needed
👉 Make changes
👉 Try similar problems
🔄 Repeat until confident

---

### Example Learning Loop

Learning Forms:

1. Start: Basic contact form
2. Add: Email validation
3. Change: Add phone field
4. Modify: Different validation rules
5. Create: Registration form
6. Challenge: Multi-step form

---

### Signs of Understanding

You know you've mastered it when you can:

- Explain it to others
- Solve similar problems alone
- Modify solutions confidently
- Debug issues independently
- Know why things work

---

### Real Example

Starting Point:
"Create a simple to-do list"

Progressive Learning:

1. Basic list with add/remove
2. Add completion status
3. Include due dates
4. Add categories
5. Implement filtering
6. Add local storage

---

### Practice Time!

Take this simple requirement:
"Create a photo gallery"

Write a prompt that:

- Asks for it to be broken down
- Requests step-by-step guidance
- Includes plans for modifications
- Suggests similar practice projects

(15 minutes)

---

## 4. Learning Checkpoints

Verifying Understanding & Progress

---

### Types of Checkpoints

1. Knowledge Checkpoints
2. Implementation Checkpoints
3. Code Review Checkpoints
4. Problem-Solving Checkpoints
5. Integration Checkpoints

---

### Knowledge Checkpoints

Ask AI to verify understanding:

"Can you quiz me on:

- CSS Flexbox concepts I'll need
- JavaScript array methods
- Form validation principles
- Basic DOM manipulation"

---

Example Questions:

- "Explain how flexbox direction works"
- "What's the difference between map and forEach?"
- "Why do we prevent form default behavior?"

---

### Implementation Checkpoints

Mini-challenges to verify skills:

"Before building the blog comments:

1. Create a simple form ✓
2. Add basic validation ✓
3. Display submitted data ✓
4. Style the components ✓
5. Handle error states □"

---

### Code Review Checkpoints

Regular code checks:

"Review my code for:

- Best practices
- Common pitfalls
- Accessibility issues
- Performance concerns
- Code organization"

---

Example:

```javascript
// My current code
const addComment = () => {
  const comment = document.getElementById("comment").value;
  comments.push(comment);
  displayComments();
};
```

---

### Problem-Solving Checkpoints

Scenario challenges:

"Now that I've built the comment feature:

1. How would I add user names?
2. What if I need timestamp sorting?
3. How could I add comment replies?
4. What about comment editing?"

---

### Integration Checkpoints

Combining features:

Blog Project Example:

1. ✓ Create blog post layout
2. ✓ Add comment form
3. □ Combine posts + comments
4. □ Add user interaction
5. □ Implement sorting

---

### Real Project Example: Blog Comments

Knowledge Checkpoints:

- Explain DOM event handling
- Describe data storage options
- List validation requirements

---

Implementation Checkpoints:

- Basic comment form works
- Data correctly stored
- Comments display properly
- Validation functioning

---

Code Quality Checkpoints:

- Functions are single-purpose
- Error handling exists
- Code is well-commented
- DRY principles applied

---

### Creating Your Own Checkpoints

For each feature, ask:

1. What concepts must I understand?
2. What can I build to prove it?
3. How can I test edge cases?
4. What modifications show mastery?
5. How does it fit with other features?

---

### Using AI for Verification

"I've reached checkpoint 3. Could you:

1. Review my understanding of concepts
2. Verify my implementation
3. Suggest improvements
4. Point out blind spots
5. Recommend next steps"

---

### Progress Tracking Template

Feature: Comment System

- [ ] Understand form handling
  - [ ] Create test form
  - [ ] Explain event handling
  - [ ] Handle validation
- [ ] Build basic version
  - [ ] Add comment works
  - [ ] Display comments works
  - [ ] Validation works
- [ ] Enhance functionality
  - [ ] Add timestamps
  - [ ] Add sorting
  - [ ] Add replies

---

## 5. AI for Project Planning(as a Student)

From Requirements to Learning Roadmap

---

### Why Use AI for Project Planning?

- Break down complex projects
- Identify knowledge gaps
- Create learning timelines
- Spot potential challenges
- Track your progress

---

### Starting the Conversation

"I have a project to build a portfolio website.
As a first-year student who knows HTML, CSS basics, and some JavaScript,
could you help me:

1. Break down the requirements
2. Identify what I need to learn
3. Create a realistic timeline
4. Suggest a learning order"

---

### Breaking Down Requirements

Ask AI to help identify:

- Must-have features
- Nice-to-have features
- Technical requirements
- Design requirements
- Potential challenges

Example:
"For each feature, can you list:

- Required skills
- Difficulty level
- Dependencies
- Learning resources needed"

---

### Creating a Learning Roadmap

Request a structured path:

1. Prerequisites
2. Core concepts
3. Advanced features
4. Testing & debugging
5. Optimization
6. Launch preparation

---

### Example: Portfolio Website Roadmap

Phase 1: Foundation

- HTML structure
- Responsive layout
- Basic styling

Phase 2: Core Features

- Navigation
- Project gallery
- Contact form

Phase 3: Enhancements

- Animations
- Dark mode
- Performance optimization

---

### Timeline Planning

Ask AI to help estimate:

- Learning time for new concepts
- Development time for features
- Testing periods
- Buffer for challenges
- Review points

"How long should I plan for each phase based on:

- My current skill level
- Part-time development
- Learning new concepts"

---

### Identifying Learning Resources

Ask AI to suggest:

- Key concepts to study
- Practice exercises
- Documentation to read
- Common pitfalls
- Best practices

For each project component

---

### Progress Tracking

Use AI to create:

- Checklists for features
- Knowledge verification points
- Progress markers
- Review questions
- Milestone celebrations

---

### Example Conversation

"I need to add a filterable project gallery to my portfolio.
Could you:

1. List all required components
2. Order them by complexity
3. Identify what I need to learn
4. Suggest a timeline
5. Create learning checkpoints"

---

### Practice Exercise

Take this project:
"Build a blog with comments"

Create a planning prompt that:

- Breaks down requirements
- Identifies learning needs
- Suggests timeline
- Includes checkpoints

(5 minutes)

---

### Example Solution

"As an experienced web developer and project manager,

I'm a first-year web development student planning to build a blog with comments.
I know HTML, CSS basics, and JavaScript fundamentals (variables, loops, functions, DOM manipulation).

Could you help me plan this project by:

---

1. Breaking down the requirements into components:

- What are the must-have features?
- What are optional enhancements?
- What are the technical requirements?
- What are potential challenges?

---

2. Creating a learning roadmap that identifies:

- Skills I already have
- Skills I need to learn
- Dependencies between features
- Resources needed for each part

---

3. Suggesting a realistic timeline considering:

- 10 hours per week development time
- Complete beginner in backend concepts
- Need to learn as I build
- University schedule constraints

---

4. Establishing checkpoints:

- Knowledge verification points
- Working prototype milestones
- Testing phases
- Code review moments

---

Please help me prioritize features and identify which parts I should:

- Build first
- Learn first
- Leave for later versions
- Consider optional"

---

### Why This Works

- Clear about current knowledge
- Realistic about time constraints
- Asks for specific breakdowns
- Considers learning needs
- Includes progress tracking
- Acknowledges limitations
- Plans for gradual development

---

### Red Flags to Watch For

In the AI's response, ensure it:

- Doesn't suggest too many features
- Keeps tech stack beginner-friendly
- Includes learning time in estimates
- Suggests concrete checkpoints
- Maintains focus on core features
- Includes practice exercises

---

### Next Steps

After getting the plan:

1. Review and adjust timeline
2. Break down first milestone
3. Identify first learning task
4. Start with smallest component
5. Set up progress tracking
6. Schedule regular reviews
