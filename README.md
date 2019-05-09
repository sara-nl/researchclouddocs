# researchclouddocs
Documentation for users of the Reseasrch Cloud at SURFsara.nl

Huisstijl:

- https://intranet.surf.nl/display/COM/Huisstijlhandboek
- https://intranet.surf.nl/display/COM/Kleurenpalet

Writing:

- Sphinx: http://www.sphinx-doc.org/en/master/contents.html
- ReST: http://www.sphinx-doc.org/en/master/usage/restructuredtext/

To compile locally:

.. code-block:: bash
    :linenos:

   cd docs
   rm -rf ../build
   ../helper_scripts/build_mac.sh ../build readthedocs/build
