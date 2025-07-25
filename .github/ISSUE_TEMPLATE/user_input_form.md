name: Create AAP Job Template
description: Create AAP Job Template
labels: ["AAP", "NOA"]
body:
  - type: textarea
    id: job_template_name
    attributes:
      label: Job Template Name
      description: A clear and concise Name of the Job Template.
      placeholder: Description...
    validations:
      required: true
  - type: input
    id: credential_id
    attributes:
      label: 
      description: Provide clear steps to reproduce the issue.
      placeholder: Credential
    validations:
      required: true
  - type: dropdown
    id: inventory
    attributes:
      label: Inventory
      description: Inventory
      options:
        - Nautobot
        - NNM
        - NetBrain
    validations:
      required: true