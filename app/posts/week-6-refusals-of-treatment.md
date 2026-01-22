---
title: "Release 6: deep research into refusals of treatment"
date: 2026-08-03
description: Deep research into refusals of treatment.
author:
  name: Sarah Malik
  url: https://compassionindying.org.uk/staff-member/sarah-malik/
---

This week we did a **deep dive** into how refusals of treatment work within the advance decision form. This post is also a *showcase* of all the markdown components available for future posts.

## Headings

You can use headings from level 2 (`##`) down to level 4 (`####`) to structure your content. Level 1 is reserved for the page title.

### This is a level 3 heading

Use these for subsections within your main sections.

#### This is a level 4 heading

Use these sparingly, for smaller groupings within subsections.

## Text formatting

You can make text **bold** or *italic* or even ***bold and italic***. You can also use ~~strikethrough~~ for deleted content.

For technical content, you might need superscript like E=mc^2^ or subscript like H~2~O.

## Links

Here are different ways to add links:

- [Compassion in Dying website](https://compassionindying.org.uk/)
- [NHS guidance on advance decisions](https://www.nhs.uk/conditions/end-of-life-care/advance-decision-to-refuse-treatment/)
- Auto-linked URL: <https://www.gov.uk/>

## Lists

### Unordered list

Key findings from our research:

- Users found the terminology confusing
- The form was too long for mobile devices
- People wanted more examples
  - Specific medical scenarios
  - Real-life case studies
  - Video explanations

### Ordered list

Steps to complete the refusal of treatment section:

1. Read the guidance notes
2. Consider which treatments to refuse
3. Discuss with your GP if unsure
4. Complete the relevant sections
5. Have the form witnessed

### Description list

Key terms we're clarifying in this release:

Advance decision
: A legally binding document that lets you refuse specific medical treatments in advance.

Mental capacity
: The ability to make a specific decision at the time it needs to be made.

Lasting Power of Attorney
: A legal document that lets you appoint someone to make decisions on your behalf.

## Blockquotes

Feedback from user research:

> I didn't understand what 'life-sustaining treatment' meant. I needed more examples to help me decide what to include.

You can also nest blockquotes:

> The form was clear overall, but...
>
> > The section on CPR was confusing. I wasn't sure if I was refusing it or requesting it.

## Code

For technical documentation, you can use `inline code` for short snippets.

For longer blocks, use fenced code blocks with syntax highlighting:

```html
<button class="nhsuk-button" type="submit">
  Save and continue
</button>
```

```javascript
function validateForm(form) {
  const requiredFields = form.querySelectorAll('[required]');
  return Array.from(requiredFields).every(field => field.value);
}
```

## Tables

| Treatment type | Can be refused? | Notes |
| :--- | :---: | ---: |
| CPR | Yes | Most common refusal |
| Ventilation | Yes | Often linked to CPR |
| Antibiotics | Yes | Context dependent |
| Pain relief | Usually no | Comfort care typically continues |

## Images

You can add images with captions:

![Placeholder image description](/images/thank-you-nhs.jpeg "Example caption text for the image")

## Horizontal rules

Use horizontal rules to separate distinct sections:

---

## Alerts and callouts

> [!NOTE]
> This is a note callout - useful for additional information.

> [!TIP]
> This is a tip callout - useful for helpful suggestions.

> [!IMPORTANT]
> This is an important callout - useful for key information.

> [!WARNING]
> This is a warning callout - useful for cautions.

> [!CAUTION]
> This is a caution callout - useful for potential negative consequences.

## Footnotes

Our research showed that 73% of users wanted clearer examples[^1], and 45% requested video guidance[^2].

[^1]: Based on survey responses from 200 users in July 2026.

[^2]: From follow-up interviews with 50 users.

## What's next

In the coming weeks, we'll be:

- Testing the revised content with users
- Working with clinical advisors on the medical terminology
- Preparing for the Release 7 deployment

---

## Links

- [GOV.UK Eleventy Plugin markdown guide](https://govuk-eleventy-plugin.x-govuk.org/example/markdown/)
- [NHS Service Manual](https://service-manual.nhs.uk/)
- [Compassion in Dying resources](https://compassionindying.org.uk/resources/)

