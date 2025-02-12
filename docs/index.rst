.. meta::
   :description: Create functional and beautiful websites for your documentation with Sphinx and the Awesome Sphinx Theme.
   :twitter:description: Create functional and beautiful websites for your documentation with Sphinx and the Awesome Sphinx Theme.

Awesome Sphinx Theme
====================

.. rst-class:: lead

   Create functional and beautiful websites for your documentation with Sphinx.

----

Get started
-----------

.. note::

   You're viewing the documentation for version |current| of the |product|,
   which is a **beta** release.
   That's why you have to add ``--pre`` to the installation command.
   To read the documentation for the latest stable release, see :doc:`v4:index` (version 4).

#. Install the theme:

   .. literalinclude:: how-to/install/includes/install.sh
      :language: sh

   .. seealso::

      :doc:`how-to/install/index`

#. Add the theme to your Sphinx configuration:

   .. literalinclude:: how-to/add/includes/configure.inc
      :language: python
      :caption: |conf|

   .. seealso::

      :doc:`how-to/add/index`

#. Build your documentation.

   .. seealso::

      `Get started with Sphinx <https://docs.readthedocs.io/en/stable/intro/getting-started-with-sphinx.html>`_

Upgrade
-------

If you want to upgrade to version |current| of the theme, see :ref:`sec:upgrade-to-5.0`.
If you don't want to upgrade, you can read the `documentation for version 4 <https://v4--sphinxawesome-theme.netlify.app/>`_.

Explore
-------

.. tab-set::

   .. tab-item:: How To

      In the **How-to** section, you can learn more about using and customizing the theme.

      .. toctree::
         :caption: How To
         :titlesonly:

         how-to/install/index
         how-to/add/index
         how-to/configure/index
         how-to/customize/index
         how-to/build-your-own/index

   .. tab-item:: Demo

      The **Demo** section shows how various elements will look like.

      .. toctree::
         :caption: Demo
         :glob:
         :titlesonly:

         demo/*
