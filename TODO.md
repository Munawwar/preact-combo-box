Priority
- Test preservation props of allowedOptions
- Test remote options
- Test label transformers

Nice to have
- Option level disabling
- Specialized mobile design - full width, bottom aligned popup
- Use signal for hover class change (and keyboard up / down arrow key class change). But then remove react and use only preact.

Questions
- Add "remove all" button again? Optional?
- Virtualization of options? Or way to limit options to X amount and show a "type to load more" message?
  - Future proof: How will this work with native customizable selects that is being shipped by browsers?
  - Also optional feature? Virtualization will cause more a11y issues?
- Package this as a web component?