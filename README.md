# git-stream-fullstack
# This project is from Advanced Node.JS by Foyzul Karim vai from interactive cares

## User Stories

### Repository Owner Stories

* As a repository owner, I want to connect my GitHub repositories to GitStream using webhooks so that repository's activity can be automatically reflected on the platform.
* As a repository owner, I want to configure which GitHub events trigger updates on GitStream (e.g. commits , pull requests, issues ,stars) so that I can tailor the level of information shared.
* As a repository owner, I want to see analytics dashboard that provides an aggregated overview of interactions across all my repositories so that I can understand my overall community engagement.
* As a repository owner , I want to drill down into detailed analytics for each of my repositories so that I can compare activity levels, identify patterns, and track the impact of specific changes.
* As a repository owner , I want to see a breakdown of followers (for both my profile and individual repositories) along with timestamps so that I can track community growth over time.
* As a repository owner, I want to receive notifications about significant events on my repository with GitStream (e.g. new PRs requiring review, highly discussed commits ) so that I can respond promptly.
* As a repository owner, I want to have the ability to export my analystics data in a downloadable format (CSV, JSON) for further analysis in other tools.


### User Subscription Stories

* As a user, I want to subscribe to repositories on GitStream so that I can receive updates about their activity within my feed.
* As a user, I want to see a clear indication of which repositories I am currently subscribed to so that I can easily manage my subscriptions.
* As a user, I want to be able to customize my notification preferences for subscried repositories so that I can control the frequency and types of updates I receive.
* As a user, I want to able to unsubscribe from a repository  if I am no longer interesed in receiving its updates.

### Feed Interaction Stories

* As a user, I want to click a "Like" button on posts in my feed so that I can express appreciation for the content.
* As a user, I want to click a "Bookmark" button on posts so that I can save them for later reference.
* As a user, I want to write comments on posts to engage in disucssions, provide feedback, or ask questions.
* As a user, I want to click a "View Details" button on posts to see more in-depth information, view the original code on GitHub, and access related discussions.
* As a user, I want to click an "Add Note" button to create a new note linked to the specific code section I'm viewing.
* As a user, I want to be able to upvote or downvote notes and comments on posts so that I can help surface high-qualtiy content.

### Details Page Story

* As a user, I want to be navigated to a dedicated Details page when I click the "View Details" button on a post so that I can focus on the specific code charges, discussions and relatd information.
* This page should display the following based on the post type:
    - Commit: Full commit message, diff with syntax highlighting , associated notes/comments.
    - Pull Request: PR title & description. list of files changed with diffs, threaded discussions, status (open ,closed, merged), associated notes/comments.
    - Note: Note content (rich text), code snippet it's linked to (with diff), threaded comments tied to the note.

### Repository Analytics Stories

* As a repository owner, I want to see an analytics dashboard that provides an aggregated overview of interactions across all my repositories so that I can understand my overall community engagement.

    - This dashboard should include visualizations for : 
        * Activity trends over time (commits , PRs, notes, comments)
        * Top contributors by various metrics (commits, PRs opened, discussions)
        * Contetn popularity (most discussed commits/PRs , most upvoted notes)

* As a repository owner, I want to drill down into detailed analytics for each of my repositories so that I can compare activity levels, identify patterns, and track the impact of specific changes.

* 

