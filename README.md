# react-common-components
🛠 Frequently used react components

* HOC:
  * withData - HOC for setting the data to the child component, returns Spinner if the data is loading.
  * withErrorHandler - HOC for axios errors, shows Modal with error message if axios gets error in response.
  * withService - HOC for wrapping the child component with service consumer and binding service instance to it's props
 
 * Errors-handling:
   * error-boundry - Component for catching errors, renders the error if catch something.
   * error-indicator - Simple error message with image.
   * error-thrower - Component for throwing a error on button click.
  
 * UI:
   * backdrop - Simple backdrop with click event.
   * form - Exapmle of the form with validation controled by the state.
   * input - Customized input component (text, select, textarea etc) with label and validation errors output.
   * modal - Simple modal with backdrop and a little animation.
   * navigation - Navigation example with toolbar and side-drawer (for mobiles).
   * spinner - simple spinner.
