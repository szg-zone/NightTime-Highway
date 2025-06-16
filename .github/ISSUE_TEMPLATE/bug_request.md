---
name: 🚨 Bug Request
about: Report a bug or unexpected behavior in NightTime-Highway
labels: bug
---  

## 🚨 Bug Request – NightTime-Highway
        
         Found something not working as expected?
         Help us squash it! Please fill in the details below.

 - type: input
    id: summary
    attributes:
      label: Bug Summary
      description: Briefly explain the issue.
      placeholder: "Crash when pressing restart after level 2"
    validations:
      required: true

  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: Provide a clear, step-by-step guide on how to reproduce the bug.
      placeholder: |
        1. Start the game
        2. Play until level 2
        3. Press 'Restart'
        4. Game crashes with error message
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      description: What did you expect to happen?
      placeholder: "The game should restart the level normally without crashing."
    validations:
      required: true

  - type: textarea
    id: actual
    attributes:
      label: Actual Behavior
      description: What actually happened instead?
      placeholder: "The game froze and exited with a traceback error."
    validations:
      required: true

  - type: textarea
    id: logs
    attributes:
      label: Screenshots / Logs (Optional)
      description: Upload any error logs or screenshots that show the problem.
      placeholder: "Paste your console error output here..."
    validations:
      required: false

  - type: checkboxes
    id: confirm
    attributes:
      label: Checklist
      options:
        - label: I’ve searched for existing bugs before reporting this one.
          required: true
        - label: I’m using the latest version of the game.
          required: true
