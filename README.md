# Git Naming Conventions

In collaborative coding, a clear naming convention acts as a roadmap. It guides teams through features,
fixes, and enhancements, fostering teamwork and efficient code management.

Explore the following examples for best
practices that enhance your development journey.

## Branch naming convention

Effective Git branch naming simplifies collaboration by offering a snapshot of a feature or fix. A thoughtfully chosen
name sets the stage for efficient teamwork and seamless code management.

Additionally, it's common to use dashes `-` or underscores `_` to represent multiple words within branch names,
enhancing both clarity and aesthetics.


### Features

When naming branches for new features, incorporating specific keywords like `feature` or `feat` provides an immediate
context for collaborators.

**Naming convention:** The `feature` (or `feat`) keyword + `_` (or `-`) for representing multiple words.

**If you have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; feature/{{ Jira ticket ID }}_{{ Jira ticket name }}
>
> Example:&nbsp;&nbsp;&nbsp; feature/SP-2023_Implement_the_products_page

\
**If you don't have a JIRA ticket:**

See the _**Custom changes**_ section.


&nbsp;
### Subtasks

When naming branches for subtasks, we don't use any specific keywords.
If the feature was split into several subtasks, we should branch from the feature branch with the name in following formats.

**Naming convention:** The `_` (or `-`) for representing multiple words.

**If you have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {{ Jira ticket ID }}_{{ Jira ticket name }}
>
> Example:&nbsp;&nbsp;&nbsp; SP-2023_Implement_the_products_page

\
**If you don't have a JIRA ticket:**

See the _**Custom changes**_ section.


&nbsp;
### Bugs

When naming branches for bugs, incorporating specific keywords like `bugfix` or `fix` provides an immediate
context for collaborators.

**Naming convention:** The `fix` (or `bugfix`) keyword + `_` (or `-`) for representing multiple words.

**If you have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; fix/{{ Jira ticket ID }}_{{ Jira ticket name }}
>
> Example:&nbsp;&nbsp;&nbsp; fix/SP-2023_Incorrect_page_colors

\
**If you don't have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; fix/{{ What you want to do }}
>
> Example:&nbsp;&nbsp;&nbsp; fix/Incorrect_page_colors


&nbsp;
### Refactoring

When naming branches for refactoring, incorporating specific keywords like `ref` provides an immediate
context for collaborators.

**Naming convention:** The `ref` keyword + `_` (or `-`) for representing multiple words.

**If you have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ref/{{ Jira ticket ID }}_{{ Jira ticket name }}
>
> Example:&nbsp;&nbsp;&nbsp; ref/SP-2023_Refactor_the_products_page

\
**If you don't have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ref/{{ What you want to do }}
>
> Example:&nbsp;&nbsp;&nbsp; ref/Refactor_the_products_page


&nbsp;
### Hotfixes

When naming branches for urgent bugs, incorporating specific keywords like `hotfix` provides an immediate
context for collaborators.

**Naming convention:** The `hotfix` keyword + `_` (or `-`) for representing multiple words.

**If you have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; hotfix/{{ Jira ticket ID }}_{{ Jira ticket name }}
>
> Example:&nbsp;&nbsp;&nbsp; hotfix/SP-2023_Page_infinite_loading

\
**If you don't have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; hotfix/{{ What you want to do }}
>
> Example:&nbsp;&nbsp;&nbsp; hotfix/Page_infinite_loading


&nbsp;
### Custom changes

When naming branches for not existing tasks or your own features, incorporating specific keywords like `custom` provides an immediate
context for collaborators.

**Naming convention:** The `custom` keyword + `_` (or `-`) for representing multiple words.

**If you don't have a JIRA ticket:**

See the _**Features**_ section.

**If you don't have a JIRA ticket:**

> Format:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; custom/{{ What you want to do }}
>
> Example:&nbsp;&nbsp;&nbsp; custom/Align_the_button_text



## Commit naming convention

// TODO

## Pull request naming convention

// TODO
