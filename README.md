# Fieldwire

![](https://rawgit.com/addpixel/Fieldwire/master/logo.svg)

Conditional Input-Fields for [Processwire](https://github.com/ryancramerdesign/ProcessWire) Frontend – ***without jQuery UI***.

Fieldwire is a replacement for [Processwires Inputfield Dependencies](http://processwire.com/api/selectors/inputfield-dependencies/ "Inputfield Dependencies"). It supports all [comparison-operators used by Processwire](http://processwire.com/api/selectors/inputfield-dependencies/#operators) (`=`, `!=`, `>`, `<`, `>=`, `<=`, `%=` and `*=`).

## Examples

```
age>=18
email*=@gmail.com
textfield!=''
checkbox=1
price>=10,price<100
```

## Support

Fieldwire depends on [jQuery](http://jquery.com) (2.x.x or 1.x.x) but eliminates the need of jQuery UI. Fieldwire works with the following FormBuilder field types.

*   Fieldset
*   Text
*   Textarea
*   Radio Buttons
*   Checkbox
*   Select
*   File
*   E-Mail
*   URL
*   Integer
*   Float
*   Datetime

Other field-types may work, but are not (yet) officially supported by Fieldwire.