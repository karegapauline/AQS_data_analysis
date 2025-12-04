name: 🌿 Blog Feedback
description: Share feedback on any blog post in the AQS-EA Wiki
title: "Feedback: "
labels: ["feedback"]
body:
  - type: textarea
    id: post
    attributes:
      label: Which blog post are you referring to?
      placeholder: e.g., Mazingira Day Overview, Air Quality Regulation 2024 Explained, Data Maturity Metric Concept
    validations:
      required: false

  - type: textarea
    id: feedback
    attributes:
      label: Your Feedback
      placeholder: Tell us what you liked, what we should improve, or any ideas you want to share…
    validations:
      required: true

  - type: input
    id: contact
    attributes:
      label: Optional — How can we reach you?
      placeholder: GitHub username / email (optional)
    validations:
      required: false
