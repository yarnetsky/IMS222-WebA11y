# Better Tables

## The Interaction

{% hint style="info" %}
For tabular data, the screen readers will announce the column headers to provide the listener with information on the tables' content and structure.
{% endhint %}

## Solutions

* Use tables for data that fits well into rows and columns.
* Always use table headers to describe the contents of the table columns.
* The table headers should clearly communicate the data below them.
* Avoid spanned rows as screen readers may be able to read them properly.
* Avoid using tables for page layouts. \(It's possible, but requires additional HTML markup to do it properly\)

### Example

Note that the State and Capital headers are encoded with `<th>` and not `<td>` cells.

```markup
<table>
    <tr>
        <th>State</th>
        <th>Capital</th>
    </tr>
    <tr>
        <td>Ohio</td>
        <td>Columbus</td>
    </tr>
    <tr>
        <td>Indiana</td>
        <td>Indianapolis</td>
    </tr>
    <tr>
        <td>Kentucky</td>
        <td>Frankfort</td>
    </tr>
</table>
```

| State | State Capital |
| :--- | :--- |
| Ohio | Columbus |
| Indiana | Indianapolis |
| Kentucky | Frankfort |

Source: [Boston College LibGuides Accessibility Guide](http://libguides.bc.edu/guidestandards/accessibility)

## Read more...

* [Table Best Practices](http://webaim.org/techniques/tables/): A WebAIM tutorial

