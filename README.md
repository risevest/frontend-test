# Frontend Engineer Test

Implement this [design](https://www.figma.com/design/B3a6Xc6F6ClAUUUGA1Kz2i/Test-file-rise-25?node-id=0-1&t=fS2VBwpekawscebc-1)  and publish it to any hosting platform of your choosing. 


---

## ✨ Part 1: Build a Feedback Dashboard

### 🎯 Goal

Create a mini web app that allows users to submit feedback and lets support agents view and filter submissions.

### ✅ Features

- A feedback form with:
  - Name (`text input`)
  - Email (`email input`)
  - Message (`textarea`)
  - Feedback Type (`select` with options: `bug`, `feature`, `other`)
- Submitted feedback should appear in a list below the form.
- Filter buttons to show:
  - All feedback
  - Only bugs
  - Only feature requests
  - Only other
- Persist feedback using `localStorage`.

### 🎁 Todo

- Use a component-based framework like React.
- Use Tailwind CSS or another styling framework.
- Mock an API request.
- Add search functionality for feedback messages.

---

## 🛠 Part 2: Debug a Broken Component

### 🐞 Scenario

A user reports that clicking the **"Submit Feedback"** button does nothing. You’ve been given the following snippet:

```jsx
export default function FeedbackForm() {
  const handleSubmit = (e) => {
    e.preventDefault;
  };

  return (
    <form onSubmit={handleSubmit}>
      <button type="button">Submit Feedback</button>
    </form>
  );
}
```
### 🧠 Your Tasks
- Identify and fix the bug.
- Explain what the issue was and how you investigated it , this be included in a README.

---
## Time Duration

1 day

## Submission

Reply to this email with your repo link and the hosted version.
