## HTML Forms

[Link to challenges & handout](https://github.com/neuefische/bo-web-23-1/tree/main/sessions/html-forms)

- `<form>` opens form and `</form>``
- `<input />` (self closing) allows input fields. There are others like `<textfield>`with `type="input"` can also be used
- Attribute `name="value"` is important so data can be recognized when it is submitted and e.g. stored in a web server
- Tag `<label>` can be used to add a label to an input field. It needs the `for="value"` attribute. The same `value` needs to be given to the corresponding `input` field with the `id="value"` attribute
- `<button>` should be used to submit forms with `type="submit"` -> per form only one submit button should be given
- `<select>` with the child `<option>` which has the attribute `value="value"` is used for dropdowns with predefined options
- `<fieldset>` is used to wrap parts of forms which belong together. Inside `<legend>` tag is used to give the part a headline
