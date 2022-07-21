# hubspot-boolean-checkbox-to-toggle
CSS that takes a HubSpot boolean checkbox field and makes it a toggle!

HubSpot Forms render with default markup that cannot be manipulated without Javascript. The styles specified in the styles.css file cooperate with the default markup to create a the toggle.

When creating the form in the HubSpot Form Builder interface, DO NOT:
- specify booleancheckbox field label text (leave the label BLANK)
- include Help Text IF you want to place a psuedo "label" to the right of the toggler

NOTE:
- making the field required may require additional styling to handle positioning of error messages
