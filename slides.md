# Using AI (LLM) as a Programming Student

---

## Who Am I?

- Lars De Richter
- Programming Teacher at Thomas More University of Applied Sciences, Belgium (Antwerp)

---

## Why come to Belgium? 🇧🇪

- Bad weather 🌧️ (but not as bad as in Finland)
- Quiet, sturdy people 🤐 (but not as quiet or sturdy as Fins)
- Never alone 👥: 11mio people in a very small country (2/3d Estonia)
- World's best beers 🍺 (and cheap)
- Famous for its chocolate 🍫
- French fries 🍟 are really Belgian

---

## Topics

1. Writing Better AI Prompts
2. Learning vs Just Getting Answers
3. Understanding Things in Different Ways
4. Practice with AI
5. Checking Your Progress
6. Planning Projects with AI Help

---

## 1. Writing Better AI Prompts

---

### Why Context Matters

- AI needs to know your background
- AI needs to know what you want
- AI needs to know your limitations
- You can tell AI all of these things!

---

### Parts of a Good Prompt

1. Context: Your Situation
2. Role: Who You Want AI to Be
3. Task: What You Want to Do
4. Format: How You Want the Answer (when needed)
5. Audience: Who It's For
6. Scope: What's Included/Not Included (when needed)
7. Step-by-Step (when needed)

---

### Your Situation (Context)

Tell AI about yourself and what you know

Example:
"I'm a first-year web student. I know how to:

- Write basic HTML
- Style with CSS
- Use JavaScript variables and functions"

---

### Who You Want AI to Be (Role)

Tell AI what kind of expert you need

Example:
"Please be like a patient teacher who's really good at
explaining things to beginners..."

"Be like an experienced web developer who always
writes clean, simple code..."

---

### What You Want (Task)

Be specific about what you need

❌ Bad: "Make a form"  
✅ Good: "Help me create a simple contact form that:

- Gets the user's name and email
- Checks if the email looks right
- Shows a message when sent"

---

### How You Want It (Format)

Tell AI how to present the solution

Example:  
"Please show me:

- HTML first
- Then CSS
- Add helpful comments
- Keep it simple - no frameworks"

---

### Who It's For (Audience)

Tell AI who will use your code

Example:  
"This needs to work for:

- Phone users
- People using screen readers
- Older people who aren't tech experts"

---

### What's Included (Scope)

Be clear about what you need (and don't need)

Example:  
"For now, I just need:

- The form layout
- Basic styling
- Simple checks
- No fancy features yet"

---

### Step by Step (When Needed)

Ask AI to break down complex tasks

Example:  
"Can you help me build this form by:

1. First showing the basic HTML
2. Then adding simple CSS
3. Finally adding basic checks
4. Explain each part before moving on"

---

### Bad Example

❌ "Fix this code"

```html
<div class="card">
  <h2>Title</h2>
  <p>Text</p>
</div>
```

Problems:

- Doesn't say what's wrong
- Doesn't say what you want
- Doesn't mention your skill level

---

### Better Example

✅ "I'm learning CSS and this card won't center on the page.
I know about flexbox but I'm not sure how to use it here.
Can you explain what I need to add and why it works?"

```html
<div class="card">
  <h2>Title</h2>
  <p>Text</p>
</div>
```

---

### Practice Exercise

Make this basic prompt better:

❌ "Help me make a website header with a logo and menu"

Take 5 minutes to improve it!

---

### Example Solution

"Hi! I'm a first-year web student learning HTML and CSS.

Could you be like a helpful teacher and show me how to make
a simple website header that has:

- A logo on the left
- A menu on the right
- Works on phones too

---

I know about:

- Basic HTML
- CSS flexbox
- Simple styling

Please show me:

- Clean HTML first
- Simple CSS using flexbox
- Helpful comments
- No complex features yet

---

I want it to:

- Look good on all screens
- Be easy to read
- Be simple to maintain"

---

### Keep Improving Your Prompts (~ iterative development)

- If AI's answer isn't quite right, tell it why
- Save good conversations to reuse later
- Stay patient - it might take a few tries
- Remember AI can make mistakes

---

### Stay Critical

Remember:

- AI is like a helpful but imperfect assistant
- Always check if the code works
- Verify if the explanations make sense
- Test solutions yourself

---

### 🚸 Tip: use memory

- Put your context in ChatGPT Custom Instructions or claude.ai project
- Keep conversations with good responses, and continue using them (with Claude it is important not to get too long conversations)
- Save prompts that have worked really well for you in a text file

---

## 2. Learning vs Just Getting Answers

How to use AI to really understand things

---

### Two Ways to Use AI

❌ "Just give me the code"  
✅ "Help me understand how to do this"

---

### Example: The Wrong Way

❌ "Write code for a menu that shows on phone screens"

Problems:

- You get code but don't learn
- You might not understand how to fix bugs
- You can't adapt it for other projects
- You miss learning opportunities

---

### Example: The Learning Way

✅ "I'm learning about phone-friendly menus. Could you:

1. Explain what makes a good phone menu
2. Show me the basic HTML we need
3. Help me understand how the CSS works
4. Guide me through simple JavaScript
5. Check if I understand each part"

---

### Ask for Learning Help

Good questions to ask:

- "Can you explain this simpler?"
- "What are the main things to understand?"
- "Could you guide me step by step?"
- "Why is this better than other ways?"
- "What mistakes should I avoid?"
- "Explain this code line by line"

---

### Learning by Doing

Instead of:  
❌ "Give me code for checking email addresses"

Try:  
✅ "I want to learn about checking email addresses in forms:

1. Show me the simplest way to check one email
2. Let me try writing code for the next part
3. Help me find mistakes in my code
4. Give me tips to make it better"

---

### When Your Code Doesn't Work

Instead of:  
❌ "Fix this code"

Try:  
✅ "My code isn't working right. Could you:

1. Help me understand what each part does
2. Guide me to find the problem
3. Explain why it's not working
4. Help me fix it myself"

---

### Practice Time!

Make this request better:  
"Write a function that adds tax to a price"

Change it to focus on learning:

- Ask for explanations
- Break it into steps
- Include practice
- Check understanding

(5 minutes to try!)

---

### Sample Answer

"I'm learning Java functions and math operations.

Could you help me learn how to calculate prices with tax by:

1. Explaining how to work with prices and percentages
2. Showing a simple example that adds one tax rate
3. Helping me modify it for different rates
4. Checking if I understand by asking questions
5. Giving me similar small problems to practice

Please point out common mistakes I should avoid!"

---

### Hardcore Learning Mode: Socratic Method

Want to really understand something?

Tell AI:  
"You are like a Socratic teacher: please don't give me answers right away.
Instead, ask me questions that help me
figure it out myself."

---

### Example: Regular Way

"How do I center something with CSS?"

vs.

### Socratic, Question-Based Learning

"I'm learning CSS layout. Use the Socratic teaching method and instead of telling me how,
you ask me questions that help me discover
how to center elements by myself?"

---

AI might ask:

- "What CSS properties do you know for positioning?"
- "How does display:flex work?"
- "What have you tried so far?"

---

### Try It!

Pick something you're learning and:

1. Ask AI to be your question-asking teacher
2. Try to answer its questions
3. See what you discover!
4. How did you feel about this?

(10 minutes)

---

### Why Questions Work Better

- You understand deeper
- You remember longer
- You learn to solve problems
- Learning is more fun
- You feel more confident (afterwards)

---

## 3. Understanding Things Different Ways

Getting Help When You're Stuck

---

### Why Get Different Explanations?

- Everyone learns differently
- Complex things need different views
- Different examples help understanding
- Connects ideas together
- Shows hidden connections

---

### Ways to Understand Things

1. Pictures and Diagrams
2. Real-Life Examples
3. Simple Code Examples
4. Step-by-Step Guides
5. Practice Exercises

---

### Example: Learning About Arrays

Ask AI:
"I'm learning about Java ArrayLists. Could you:

1. Compare them to something from real life
2. Show a simple drawing/diagram
3. Give basic code examples
4. Break it down step by step
5. Connect it to things I already know"

---

### Real-Life Example

Java ArrayList = Student Register

- Creating register = Creating array
- Adding students = Adding to ArrayList
- Removing graduates = Removing from ArrayList
- Finding student = Using indexOf/contains
- Checking class size = Using size() method

---

### From Real Life to Code

Instead of:

```java
ArrayList<String> students = new ArrayList<>();
students.add("Alice");
students.remove("Alice");
```

---

Think:

- Creating class register
- Adding new student
- Removing graduated student

---

### Breaking Down Hard Topics

"I don't understand CSS flexbox. Could you:

1. Compare it to something I know
2. Show how it organizes things
3. Give simple examples
4. Show common patterns
5. Let me practice"

---

### Start Simple, Add More

Start with:

```css
.container {
  display: flex;
}
```

---

Build up to:

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

---

### Practice: Get Different Views

Take this topic:
"JavaScript click events"

Write a request asking for:

- Real-life comparison
- Visual explanation
- Simple code example
- Practice exercise

---

### Example Solution

"I'm learning about JavaScript click events.
Could you help me understand through:

1. A real-life example (like pressing a doorbell)
2. A simple drawing showing what happens
3. The most basic code example that works
4. Easy exercises to practice with:
   - Simple button clicks
   - Changing text
   - Basic interactions

Please explain any new words you use!"

---

### Make It Stick

After getting different explanations:

1. Try explaining it yourself and ask AI to check your answer
2. Make your own examples
3. Mix different ways of understanding
4. Try new situations
5. Teach someone else (teaching is the best way to learn, I am always learning 😊)

---

## 4. Practice with AI

Using AI as Your Sparring Partner

---

### Break Down Big Problems

Ask AI to help you:

- Look at what you need to do
- Split it into smaller parts
- List what you need to learn
- Suggest learning order

Example:
"Can you help me break this project into
small pieces so I can learn one at a time?"

---

### Step by Step Solutions

For each small part:

1. Understand the basics
2. See a simple example
3. Try it yourself
4. Check if it works

---

Example:
"Let's work on the form part first.
Could you explain how it works,
then guide me through building it?"

---

### When You're Stuck

Share with AI:

- Your code
- What you wanted to happen
- What's happening instead
- Ask for hints before answers

---

Example:
"My form isn't working. Here's my code and what I expected.
Can you give me hints about what might be wrong?"

---

### Making Small Changes

When something works:
"Now that this works, could we:

- Add another feature?
- Change how it works?
- Make it better for users?
- Make it work for everyone?

Help me understand each change!"

---

### Practice More

Ask AI to:
"Could you make a similar but different exercise that:

- Uses the same programming concepts
- Has slightly different needs
- Helps me practice more?"

---

### Learning Loop

👉 Understand the problem  
👉 Break it down  
👉 Solve step by step  
👉 Fix problems  
👉 Make changes  
👉 Try similar things  
🔄 Repeat until confident

---

### Example: Learning Forms

Start small, build up:

1. Basic name input
2. Add email check
3. Add phone number
4. Add different checks
5. Make signup form
6. Make multi-step form

---

### You Know You've Got It When

You can:

- Explain it to others
- Solve similar problems
- Make changes confidently
- Fix problems yourself
- Know why things work

---

### Practice Time!

Take this task:
"Make a simple photo gallery"

Write a request that:

- Asks to break it down
- Asks for step-by-step help
- Plans future changes
- Suggests practice projects

(5 minutes)

---

## 5. Checking Your Progress

Making Sure You Really Understand

---

### Ways to Check Learning

1. Knowledge Checks
2. Building Tests
3. Code Review
4. Problem Solving
5. Putting Things Together

---

### Knowledge Checks

Ask AI to test you:

"Can you quiz me on:

- How flexbox works
- Basic array methods
- Form basics
- Simple DOM changes"

---

Example Questions:

- "How do you center with flexbox?"
- "What's different about forEach and map?"
- "Why check forms before sending?"

---

### Building Tests

Small tasks to check skills:

"Before building comments, can I:

1. Make a basic form ✓
2. Check input ✓
3. Show data ✓
4. Style it ✓
5. Handle errors ✓

---

### Code Review Checks

Regular code checks:

"Look at my code for:

- Good practices
- Common mistakes
- Works for everyone
- Runs fast
- Clean organization"

---

Example Code Check:

```javascript
// My code
function addComment() {
  let comment = document.getElementById("comment").value;
  comments.push(comment);
  showComments();
}
```

---

### Problem Solving Checks

Try new situations:

"Now that I have comments working:

1. How would I add names?
2. What about sorting by time?
3. How about replies?
4. What about editing?"

---

### Putting Things Together

Combining features:

Blog Project Progress:

1. ✓ Make blog layout
2. ✓ Add comment box
3. □ Connect posts & comments
4. □ Add user stuff
5. □ Add sorting

---

### Real Example: Blog Comments

Check Knowledge:

- How events work
- Where to store data
- How to check input

---

Check Building:

- Comment form works
- Data saves right
- Comments show up
- Checking works

---

Check Code Quality:

- Functions do one thing
- Handles errors
- Has good comments
- No repeated code

---

### Make Your Own Checks

For each feature, ask:

1. What must I understand?
2. What can I build to prove it?
3. What could go wrong?
4. What changes show I get it?
5. How does it fit together?

---

### Using AI to Check

"I'm at check point 3. Could you:

1. Test what I know
2. Check my code
3. Suggest better ways
4. Point out what I missed
5. Tell me what's next"

---

### Progress Tracker

Comment System:

Learning:

- [ ] Understand forms
  - [ ] Test form works
  - [ ] Know how events work
  - [ ] Input checking works

Building:

- [ ] Add comments works
- [ ] Show comments works
- [ ] Checking works

Making Better:

- [ ] Add time
- [ ] Add sorting
- [ ] Add replies

---

## 6. Planning Projects with AI

From Ideas to Working Code

---

### Why Plan with AI?

- Break big projects down
- Find what you need to learn
- Make realistic schedules
- See possible problems
- Track your progress

---

### Starting the Plan

"I need to build a portfolio website.
I'm a first-year student who knows basic HTML, CSS,
and some JavaScript. Could you help me:

1. Break down what I need to do
2. List what I need to learn
3. Make a timeline that works
4. Suggest what to do first"

---

### Breaking Down the Project

Ask AI to list:

- Must-have features
- Nice-to-have features
- Technical needs
- Design needs
- Possible problems

Example:
"For each part, can you list:

- Skills needed
- How hard it is
- What it depends on
- What I need to learn"

---

### Making a Learning Path

Ask for a clear path:

1. Basics you need
2. Main features
3. Extra features
4. Testing
5. Making it better
6. Getting ready to show

---

### Example: Portfolio Website Plan

Step 1: Basics

- HTML structure
- Simple layout
- Basic styles

Step 2: Main Parts

- Navigation
- Project gallery
- Contact form

Step 3: Make It Better

- Simple animations
- Dark/light mode
- Speed improvements

---

### Planning Time

Ask AI to help plan:

- Learning time
- Building time
- Testing time
- Extra time for problems
- Check-in points

"How long should I plan for each part based on:

- What I know now
- Part-time coding
- Learning new things"

---

### Finding Learning Resources

Ask AI to suggest:

- Main things to learn
- Practice exercises
- Good documentation
- Common problems
- Best ways to do things

---

### Track Progress

Use AI to make:

- Feature checklists
- Knowledge checks
- Progress markers
- Review questions
- Success celebrations

---

### Example Chat

"I need to add a filterable project gallery.
Could you:

1. List all the parts I need
2. Order them by how hard they are
3. Tell me what to learn
4. Suggest how long it'll take
5. Make learning checkpoints"

---

### Practice Exercise

Take this project:
"Make a blog with comments"

Write a planning request that:

- Breaks down needs
- Lists learning needs
- Suggests timeline
- Includes checkpoints

(5 minutes)

---

### Sample Solution

"Hi! I'm a first-year web student planning a blog with comments.
I know HTML, CSS basics, and simple JavaScript.

Could you help me plan by:

---

1. Breaking it down:

- What must it have?
- What would be nice to have?
- What technical things does it need?
- What problems might come up?

---

2. Making a learning plan:

- What do I already know?
- What do I need to learn?
- What depends on what?
- What resources will help?

---

3. Suggesting a timeline for:

- 10 hours per week coding
- Learning as I build
- Working around classes

---

4. Making checkpoints:

- Knowledge checks
- Working versions
- Testing times
- Code reviews

---

Please help me decide:

- What to build first
- What to learn first
- What to save for later
- What's optional"

---

### Why This Works

- Clear about what you know
- Realistic about time
- Asks for specific parts
- Thinks about learning
- Tracks progress
- Knows limits
- Builds step by step

---

### Watch Out For

When AI responds, check it:

- Doesn't add too many features
- Keeps things simple
- Includes learning time
- Has clear checkpoints
- Focuses on basics
- Includes practice

---

### Next Steps

After getting your plan:

1. Review the timeline
2. Break down first step
3. Start first learning task
4. Begin with smallest part
5. Track your progress
6. Check progress regularly

---

# Check with University policy what you can upload and use!!!

---

### Follow-up

Try out custom GPT’s or better yet ask your teachers to create custom GPT tailored to their course.

---

## Thank You!

Questions? Let's talk!
