# 201 Reading 09

## HTML Forms & JS Events

### HTML Forms

Forms are important because they are one of the main ways to interact between user & website/application.

A few things to keep in mind are to keep the form short & concise - too long and the user will be frustrated.

Form Elements:

- `<form>` element defines a form and attributes that determines the form's behavior. You must always start a form with this element & nest components inside.
- `<fieldset>` is a good way to create groups of widgets that share the same purpose, styling & semantic.
- `<legend>` you can label a `<fieldset>` by including the `<legend>` tag. The legend tag formally describes the purpose of the fieldset.
- `<label>` is a formal way to define a label for an HTML form widget. This is important for accessibility like screen readers.
- `<input>` will take the type and defines the way that `<input>` appears & behaves. For example, value of text would be the default & represents a single-line text field that accepts any kind of input. But a value of email would define a single line text field that only accepts a well-formed email address.

### JS Events

Events are an effect of a cause, essentially. Like a user clicks on something, then something happens. Or a user enters information, then something happens. And event causes this to happen if the criteria is met and the system produces a signal.

When using the `addEventListener()` method you must also provide two parameters: what is the event (like a click) and the function when that event happens.

Event objects automatically are passed to event handlers to provide extra features & information (Mozilla.org) Using the target is useful because it will focus on the object used in the event rather than the whole page/app.

Event bubbling will show you the inner most targeted element, and then on successively less nested elements but the event capturing will do the opposite, starting with least nested and then into the more nested until target is reached. (Mozilla.org)

## Things I want to know more about

Event bubbling & capturing - what is this used for most often?