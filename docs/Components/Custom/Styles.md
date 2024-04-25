[Home](index) > [Components](Components) > [Custom](Custom) > **Styles**
***

## Working Examples

> Try a working example<br>
> [View example](https://submit.digital.gov.bc.ca/app/form/submit?f=6ff5ba7d-ed8b-433e-a063-162f56627586)

> Download this example file and [import](Importing-and-exporting-form-designs) it into your design<br>
> [example_styles_schema.json](../examples/example_styles_schema.json){:download="example_styles_schema.json"}
***

## Styles (Tutorial)

Create visually pleasing designs with built-in formatting styles using our version of [Bootstrap](https://getbootstrap.com/docs/4.5/components/).

<!-- **On this page:**

* [Styles(Tutorial)](#Styles(Tutorial))
   * [Components](#Components)
   * [Utilities](#Utilities)
   * [Columns](#Columns)
   * [Icons](#Icons)
     * [Button icons](#Button-icons)
     * [Input icons or text](#Input-icons-or-text) -->

## Styles(Tutorial)

### Components
[Bootstrap Components](https://getbootstrap.com/docs/4.5/components/) can be added using the `Layout > HTML Element` in Advanced Fields. Copy and paste components from the examples on the Bootstrap site. There are also a few samples implemented here in the working example.

You can either paste examples directly into the `content` field or into the `HTML Tag` and `CSS Class` fields like this:

![HTML Tag: div, CSS Class: alert alert-primary](images/bs_alert_example.png)

You'll find some components built into simple and advanced fields like Panel. Other options are also available in components like adding prefix and suffix to input groups.

### Utilities
<!-- **[Back to top](#top)** -->

Experiment with [Bootstrap Utilities](https://getbootstrap.com/docs/4.0/utilities/) to add custom styles to your form.

![Custom CSS Class: border border-danger rounded](images/bs_utilities.png)

### Columns
<!-- **[Back to top](#top)** -->

Use [Bootstrap Grids](https://getbootstrap.com/docs/4.0/layout/grid/) to customize columns. A form is 12 columns wide, divide it up any way you like (6x2, 4x3, 10+2, etc). There are some pre-set column widths in Simple Fields. In Advanced Fields, here's an example of 4 columns of width 3 (4 X 3 = 12):

![Settings for 4 columns of width 3](images/bs_columns.png)

You can also nest columns, that is to say put columns inside of other components like a panel or even another parent column component.

### Icons
<!-- **[Back to top](#top)** -->

Add icons to buttons and input fields from [Font Awesome](https://fontawesome.com/v4.7.0/icons/).

#### Button Icons

Example, enter “fa fa-plus” in one of the button icon fields.
![](images/bs_icons.png)

#### Input Icons or Text
You can add an input icon in front of a field by adding an HTML tag into the “Prefix” field. <I class=”fa fa-phone”></i>.
![](images/bs_prefix_suffix.png)

#### Custom CSS
In certian scenarios where form needs be customized to look certian way. Custom CSS can be added to the form by defining CSS in HTML Elemennt component and refer back the CSS class in other advanced components.

Default CSS classes from Boorstrap can be overriden in Html Element compoenent. Also mark the component as hidden as it not be visible in the form.

![](images/customCssClass.jpg)

[picture]

Customm CSS classes can also be defined in the HTML element component. Reference to this class can be provided in the Custom CSS class property of the advanced components. Like the following example CSS class {replace name} defined in the HTML element component can be used in Text Feild Advanced compoenent to make the text in text field bold. 

[picture]

It is recomended to adhere to BC govt style guidelines available here



***
[Terms of Use](Terms-of-Use) | [Privacy](Privacy) | [Security](Security) | [Service Agreement](Service-Agreement) | [Accessibility](Accessibility)