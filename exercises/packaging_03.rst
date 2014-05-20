Create a file: MANIFEST.in next to setup.py with the content::

  i nclude README.md
  include LICENSE.txt
  recursive-include interactionu *

Then run::

  $ python setup.py sdist
