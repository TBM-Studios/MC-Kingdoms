name: Bug report
description: Create a report to help us improve
title: '[Bug]: '
body:
  - type: textarea
    id: what_happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
    validations:
      required: true
  - type: input
    id: version
    attributes:
      label: Version
      description: Which version are you using?
      placeholder: 0.0.0
    validations:
      required: true
  - type: textarea
    id: log
    attributes:
      label: Provide the log
      description: Please provide us with the crash-report.log and latest.log here.
      placeholder: >-
        You can upload it (e.g. Bytebin) and post the link
        here.
