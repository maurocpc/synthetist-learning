1. What does "semantic HTML" mean?
   It means using HTML elements that clearly describe meaning and role.
   Semantic HTML helps both humans (reading your code) and machines (screen readers, search engines) understand what each part of your page means, not just how it looks.

2. What's the difference between <div> and <section>?
   <div> is a generic container while <section> has semantic meaning.

3. What does CSS stand for, and what is it used for?
   Cascading Style Sheets are used to control and format the visuals of HTML pages.
   The "Cascading" part means styles can override each other based on specificity and order.

##Git Questions
1. git add vs git commit 
   git add moves the edited files to staging area. git commit saves a snapshot of all staged changes with a message and timestamp. This creates a point in history you can return to later.

2. Why use commit messages?
   By using messages we know exactly what's happening to the files, which is very important when working in a team.

      - Future-you won't remember what you changed 3 months ago
      - Helps you find when bugs were introduced
      - Shows employers your communication skills

3. What does .gitignore do?
   Git ignores files/folders listed in .gitignore—they won't be tracked, staged, or committed. This prevents:
   
      - Accidentally committing secrets (API keys)
      - Bloating your repo with 10,000 node_modules files
      - Tracking system files that differ per computer

4. Selective staging.
   I use git add + the names of the files to be committed.