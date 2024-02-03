# FORMS IN HTML

The `<form>` element is used to create a form in HTML. Forms are
used to gather user input.

Some attributes associated with the `<form>` element include:

- The `action` attribute specifies where the form data should be
  sent when the form is submitted.
- The `target` attribute specifies where to display the form's
  response.
- The `autocomplete` attribute can have a value of `on` or `off`
  and determines whether the browser should automatically
  fill in the form.
- The `novalidate` attribute specifies that the form should not
  be validated.
- The `method` attribute specifies the HTTP method to use
  when sending form data.
- The `name` attribute specifies the name of the form.
- The `required` attribute specifies that an input element
  cannot be left blank.
- The `autofocus` attribute gives focus to the input elements
  when the page loads.
- The `disabled` attribute disables an input element, preventing
  the user from interacting with it.
- The `placeholder` attribute is used to provide a hint to the
  user about what information is required for the input
  element.

Other input elements that can be used in forms include:

- `<textarea>`: allows users to enter multiple lines of text as
  input.
- `<select>`: provides a list of options for users to choose from.
- `<option>`: creates a single option within a `<select>` element.
- `<input>`: provides an input field for users to enter data. The
  `type` attribute specifies the type of data that can be entered.
- `<button>`: creates a button that can be clicked to perform an
  action.

```html
<form action="/Submit_URL/" method="post">
 <label for="FirstName"> First Name: </label>
 <input type="text"
 name="FirstName"
 placeholder="First Name"
 required >
 <label for="LastName"> Last Name: </label>
 <input type="text"
 name="LastName"
 placeholder="Last Name"
 required >
 <label for="add"> Address: </label>
 <textarea name="add"></textarea>
 <label for="age"> Age: </label>
 <select id="age">
 <option value="11-20">11-20</option>
 <option value="21-30">21-30</option>
 <option value="31-40">31-40</option>
 <option value="41-40">41-50</option>
 </select>
 <input type="submit" value="Submit">
 </form>