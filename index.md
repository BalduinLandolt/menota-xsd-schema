## About this Repo
For more information, see the [readme](README.md). Please also check the [Github Repository](https://github.com/BalduinLandolt/menota-xsd-schema).

## Style Sheets

Here is a list of the hosted files:

- [Menota P5 RelaxNG Schema](https://raw.githubusercontent.com/BalduinLandolt/menota-xsd-schema/master/menotaP5.rng)
- [menota.xsd](https://raw.githubusercontent.com/BalduinLandolt/menota-xsd-schema/master/menota.xsd)
- [dcr.xsd](https://raw.githubusercontent.com/BalduinLandolt/menota-xsd-schema/master/dcr.xsd)
- [ns1.xsd](https://raw.githubusercontent.com/BalduinLandolt/menota-xsd-schema/master/ns1.xsd)
- [teix.xsd](https://raw.githubusercontent.com/BalduinLandolt/menota-xsd-schema/master/teix.xsd)
- [xml.xsd](https://raw.githubusercontent.com/BalduinLandolt/menota-xsd-schema/master/xml.xsd)

## XML Template

A template XML file can be downloaded [here](template.xml) (if your browser opens the file directly, right-click on the link and hit "Save Link As..." or something similar) or viewed in the repository [here](https://github.com/BalduinLandolt/menota-xsd-schema/blob/master/template.xml).

This template validates not only in Oxygen XML, but also in Visual Studio Code, using the "XML Language Support by Red Hat" Extension. Thus, a freeware alternative to Oxygen can be used for working with Menota files.

Generally, this works when declaring the schema in the document root by adding the attributes `xsi:schemaLocation` and defining the namespace `xsi`.  
Simply use the following root element:
```XML
<TEI  xmlns="http://www.tei-c.org/ns/1.0"
    xmlns:me="http://www.menota.org/ns/1.0"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="http://www.tei-c.org/ns/1.0 https://raw.githubusercontent.com/BalduinLandolt/menota-xsd-schema/master/menota.xsd">
    ...
</TEI>
```
