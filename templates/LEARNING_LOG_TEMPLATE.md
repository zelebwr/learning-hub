---
topic: "Primary Learning Topic"
status: "In Progress" # In Progress | Completed
learner: "@username"
---

# 📖 Learning Log: [Primary Learning Topic]

> _This document is a living journal of the journey, discoveries, and outcomes of this learning project. It's a space for reflection and a guide for future learners._

---

## 🎯 **1. Learning Objectives**

_What are the specific, measurable goals for this project? What will I be able to do when this is complete?_

-   [ ] **Objective 1:** _(e.g., Understand and use all major CSS Flexbox properties)_
-   [ ] **Objective 2:** _(e.g., Build a fully responsive image gallery using a Flexbox-first approach)_
-   [ ] **Objective 3:** _(e.g., Confidently explain the difference between `justify-content` and `align-items`)_

---

## 🗺️ **2. Process & Discoveries**

_A journal of the build. This is where the "aha!" moments, roadblocks, and key decisions are recorded._

### **`[Date]` - Day 1: Setup & The "Aha!" Moment**

I started by setting up the basic HTML structure. My initial attempt to center items was failing. I discovered that I needed `align-items: center` for the vertical axis on the container. **Big takeaway:** Flexbox properties are applied to the _container_, not always the _items_.

> **Code Snippet:**
>
> ```css
> .container {
>     display: flex;
>     justify-content: center; /* Horizontal alignment */
>     align-items: center; /* Vertical alignment */
> }
> ```

---

## ✨ **3. Key Takeaways & "What I Got"**

_A summary of the most valuable knowledge gained. If someone could only read one section, this would be it._

-   **💡 Takeaway 1:** Flexbox is a one-dimensional layout system. For two dimensions (rows _and_ columns), CSS Grid is the more powerful tool.
-   **💡 Takeaway 2:** The `flex-grow`, `flex-shrink`, and `flex-basis` properties are a shorthand for the `flex` property and control how items handle extra or limited space. `flex: 1` is a powerful shortcut.
-   **💡 Takeaway 3:** ...

---

## ❓ **4. Challenges & Unresolved Questions**

_What was difficult? What concepts are still fuzzy? This is a map for future learning._

-   **Challenge:** I still find it difficult to remember all the different values for `align-content`. It seems to only work when there are multiple lines of flex items.
-   **Question for Later:** How does Flexbox interact with CSS Grid when a grid item is also a flex container?
