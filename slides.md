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
2. AI as Your Study Buddy

---

## Why Context Matters

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
