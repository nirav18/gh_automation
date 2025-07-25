---
name: Create Nautobot Tag
description: Request to create a new tag in Nautobot
labels: ["nautobot", "tag"]
body:
  - type: input
    id: tag_name
    attributes:
      label: Tag Name
      description: Enter the desired tag name.
      placeholder: Tag name...
    validations:
      required: true
  - type: dropdown
    id: nautobot_env
    attributes:
      label: Nautobot Environment
      description: Select the Nautobot environment.
      options:
        - Production
        - Staging
        - Development
    validations:
      required: true
  - type: textarea
    id: why
    attributes:
      label: Why
      description: Explain why this tag is needed.
      placeholder: Reason for tag creation...
    validations:
      required: true
  - type: textarea
    id: assign_tag_to_devices
    attributes:
      label: Assign tag to devices
      description: List devices to assign this tag to, or describe the assignment criteria.
      placeholder: Device names or criteria...
    validations:
      required: false
  - type: textarea
    id: additional_context
    attributes:
      label: Additional Context
      description: Any other relevant information or requirements.
      placeholder: Additional details...
    validations:
      required: false