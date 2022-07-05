# Links, tables and forms

## `<a>` tag

The `<a>` tag defines a hyperlink, which is used to link from one page to another.

The most important attribute of the `<a>` element is the href attribute, which indicates the link's destination.

By default, links will appear as follows in all browsers:

* An unvisited link is underlined and blue;
* A visited link is underlined and purple;
* An active link is underlined and red.

### Example

```html
<a href="https://oliota.com">
<img border="0" alt="Oliota" width="100" height="100">
</a>
```

<br>

## `<table>` tag
The `<table>` tag defines an HTML table.

An HTML table consists of one `<table>` element and one or more `<tr>`, `<th>`, and `<td>` elements.

The `<tr>` element defines a table row, the `<th>` element defines a table header, and the `<td>` element defines a table cell.

An HTML table may also include `<caption>`, `<colgroup>`, `<thead>`, `<tfoot>`, and `<tbody>` elements.

### Example

```html
<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>
</head>
<body>

<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$80</td>
  </tr>
</table>

</body>
</html>
```

Output:

<head>
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>
</head>
<body>

<table>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
  <tr>
    <td>January</td>
    <td>$100</td>
  </tr>
  <tr>
    <td>February</td>
    <td>$80</td>
  </tr>
</table>

</body>
</html>

<br>

## `<thead>` , `<tbody>` and `<tfoot>` tag

* The `<thead>` tag is used to group header content in an HTML table.

* The `<tbody>` tag is used to group the body content in an HTML table.

* The `<tfoot>` tag is used to group footer content in an HTML table.

<br>

## `<form>` tag
> <form> is a HTML element to collect input data with containing interactive controls. It provides facilities to input text, number, values, email, password, and control fields such as checkboxes, radio buttons, submit buttons, etc., or in other words, form is a container that contains input elements like text, email, number, radio buttons, checkboxes, submit buttons, etc. Forms are generally used when you want to collect data from the user. 

<br>

### `<form>` elements
These are the following HTML `<form>` elements:

* `<label>`: It defines label for `<form>` elements.

* `<input>`: It is used to get input data from the form in various types such as text, password, email, etc by changing its type.

* `<button>`: It defines a clickable button to control other elements or execute a functionality.

* `<select>`: It is used to create a drop-down list.

* `<textarea>`: It is used to get input long text content.

* `<fieldset>`: It is used to draw a box around other form elements and group the related data.

* `<legend>`: It defines caption for fieldset elements.

* `<datalist>`: It is used to specify pre-defined list options for input controls.

* `<output>`: It displays the output of performed calculations.

* `<option>`: It is used to define options in a drop-down list.

* `<optgroup>`: It is used to define group-related options in a drop-down list.

### Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GfG</title>
</head>
<body>
  <form>
    <fieldset>
      <legend>Personal Details</legend>
      <p>
        <label>
          Salutation
          <br />
          <select name="salutation">
            <option>--None--</option>
            <option>Mr.</option>
            <option>Ms.</option>
            <option>Mrs.</option>
            <option>Dr.</option>
            <option>Prof.</option>
          </select>
        </label>
      </p>
      <p>
        <label>First name: <input name="firstName" /></label>
      </p>
      <p>
        <label>Last name: <input name="lastName" /></label>
      </p>
      <p>
        Gender :
        <label><input type="radio" name="gender" value="male" /> Male</label>
        <label><input type="radio" name="gender" value="female" /> Female</label>
      </p>
      <p>
        <label>Email:<input type="email" name="email" /></label>
      </p>
      <p>
        <label>Date of Birth:<input type="date" name="birthDate"></label>
      </p>
      <p>
        <label>
          Address :
          <br />
          <textarea name="address" cols="30" rows="3"></textarea>
        </label>
      </p>
      <p>
        <button type="submit">Submit</button>
      </p>
    </fieldset>
  </form>
</body>
</html>
```

Output: 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GfG</title>
</head>
<body>
  <form>
    <fieldset>
      <legend>Personal Details</legend>
      <p>
        <label>
          Salutation
          <br />
          <select name="salutation">
            <option>--None--</option>
            <option>Mr.</option>
            <option>Ms.</option>
            <option>Mrs.</option>
            <option>Dr.</option>
            <option>Prof.</option>
          </select>
        </label>
      </p>
      <p>
        <label>First name: <input name="firstName" /></label>
      </p>
      <p>
        <label>Last name: <input name="lastName" /></label>
      </p>
      <p>
        Gender :
        <label><input type="radio" name="gender" value="male" /> Male</label>
        <label><input type="radio" name="gender" value="female" /> Female</label>
      </p>
      <p>
        <label>Email:<input type="email" name="email" /></label>
      </p>
      <p>
        <label>Date of Birth:<input type="date" name="birthDate"></label>
      </p>
      <p>
        <label>
          Address :
          <br />
          <textarea name="address" cols="30" rows="3"></textarea>
        </label>
      </p>
      <p>
        <button type="submit">Submit</button>
      </p>
    </fieldset>
  </form>
</body>
</html>


