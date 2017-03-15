.. Test Project Sphinx documentation master file, created by
   sphinx-quickstart on Wed Mar 15 20:41:02 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Data Dictionary
===============================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Test Heading 1
--------------
This is a text block

Small heading
^^^^^^^^^^^^^
Another *hello*, **hello**

| quoation
| hello

.. warning:: This is a warning

.. seealso:: See also

.. code-block:: html
   :linenos:

   <h1>code block example</h1>

.. code-block:: sql
   :linenos:

   select * from tables;
   insert into tables values ('a','b');

Some links
----------

`python <www.python.org>`_

`Westpac <http://www.westpac.com.au>`_

`How to install Read The Doc <https://github.com/rtfd/sphinx_rtd_theme>`_

Let's see a table
-----------------

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
