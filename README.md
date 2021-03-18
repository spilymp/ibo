# IBO - Icon Builder for Odoo

The provided [Configurator](https://spilymp.github.io/ibo/) can be used to quickly and easily create new appicons in the style of the
appicons of the ERP system [Odoo](https://www.odoo.com/).

But it is also possible to use the included js class elsewhere and create your own configurator based on it, for example.

For this purpose, the class offers a few more parameters for individualization in addition to the options shown in the documentation section.

## Documentation

The basis of the configurator is a JavaScript class "IBO_ICON", which creates a canvas and "paints" the icon on it (see file [`/js/ibo_icon.js`](https://github.com/spilymp/iob/blob/main/js/ibo_icon.js)).
If the existing class is used directly by means of a script, additional parameters can be passed.
If this class is instantiated, various parameters can be passed to it.
If not, default values are used in each case.
For more information please visit the [Project Website](https://spilymp.github.io/ibo/).
