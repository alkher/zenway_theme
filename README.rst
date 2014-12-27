**************************
Nikola theme for zenway.es
**************************

:Source theme: `bootstrap3`_
:Additional font: `awesome font`_
:Cookie consent: `silktide cookie consent`_

`Nikola`_ theme for `zenway`_ site. 

.. contents::

bootstrap3
==========

Changed `bootstrap3`_ theme with:

.. code-block:: shell
   :number-lines:

   nikola bootswatch_theme -n amedida -s united -p bootstrap3

awesome font
============

Added `awesome font`_ files to fonts folder:

	theme_folder/assets/fonts/

Added *awesome css*, ``font-awesome.min.css``, to css folder:

	theme_folder/assets/css/

cookie consent
==============

Added *cookie consent css*, ``style.min.css``, to css folder:

	theme_folder/assets/css/

Added *cookie consent js*, ``plugin.min.js``, to js folder:

	theme_folder/assets/js/

Changed base and base_helper templates (``base.tmpl`` and ``base_helper.tmpl``) in templates folder:

	 theme_folder/templates/

.. _bootstrap3: http://themes.getnikola.com/#bootstrap3
.. _awesome font: http://fontawesome.io
.. _silktide cookie consent: http://silktide.com/cookieconsent
.. _Nikola: http://getnikola.com
.. _zenway: http://zenway.es