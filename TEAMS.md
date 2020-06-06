# Defund12.org Team Organization

## 1. User that submits issue

Anyone that would like to add an email for their locale. They create issue in adherence to [email guidelines](https://github.com/teddywilson/defund12.org/blob/gh-pages/EMAIL_TEMPLATE_STYLE_GUIDE.md).

## 2. Triage Team [Needs people!]

A person on the triage team is the first to review newly created issues. Look over all issues that have the tag `[new-request]`

**Responsibilities**

- Check if issue has all required data
  - Does it meet basic data requirements?
    - Subject line
    - Recipients
    - CC addresses
    - Body text
  - If not, **close issue** and reply with the contents of the [email request template](https://github.com/teddywilson/defund12.org/blob/gh-pages/.github/ISSUE_TEMPLATE/EMAIL_REQUEST.md)
  - If yes, tag as ready to review. Add tag `[ready-for-review]` and remove all previous tags

## 3. Review, Editing, and Approval Team [Needs people!]

Ensure the email roughly adheres to [email guidelines](https://github.com/teddywilson/defund12.org/blob/gh-pages/EMAIL_TEMPLATE_STYLE_GUIDE.md).

**Responsibilities**

- If body content is not salvageable, **close issue**.
- Is it _good enough_?
  - Does it have locale specific info?
  - Is the core statement in regards to defunding local police departments
  - Add tag `[ready-for-pr]` and remove all otehr tags
- Even though the issue is _good enough_ and you added the `[ready-for-pr]`, do you still think the email template needs work or editing?
  - Add tag `[email-needs-work]` and leave comment on what the outstanding tasks are.

## 4. Email Addition Development Team

This team will pick up issues that have the `[ready-for-pr]` tag. Issues should only be assigned to a developer for less 24 hrs to ensure emails get added to the site quickly.

**Responsibilities**

- Assign issue to yourself so no other developer begins working on it
- Create a PR for the email issue
- Ensure the email markdown is correct and properly linted.
- Once PR is up, someone will review and merge!

## Join the conversation

If you'd like to help out, please join our discord [here](https://discord.gg/YMxndzd) and say hello. We'd love your help!