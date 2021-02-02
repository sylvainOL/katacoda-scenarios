Validate RST files

Execute `doc8` to verify the RST file syntax.

Run the following command. In this example, we ignore the long lines (DOO1).

```
doc8 --ignore D001
``{{execute}}

Verifyj that everyfile is ok.

Use `Sphinx` to test that all links are OK

```
sphinx-build -n -b linkcheck docs docs/build/linkcheck 
``{{execute}}
