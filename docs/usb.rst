
USB library configuration
-------------------------

concept
=======

blablabla.

pyusb
=====

PyUSB provides for easy access to the host machine's Universal Serial Bus (USB) system for Python 3.

libusb1
=======

You can now visit http://pypi.python.org/pypi?:action=files&name=an_example_pypi_project&version=0.0.4
to see the files that were uploaded to pypi.

.. note::

   You'll still need to enter a few 'y' commands, but the amount of interaction
   is pretty minimal.  If anyone has found away around this, please, email me.

Contents of ``upload.bat``::

	set HOME=C:\Users\Owner\
	cd C:\eclipse\workspace\HG_AN_EXAMPLE_PYPI_PROJECT
	C:\Python24\python.exe setup.py bdist_egg upload --identity="Andrew Carter" --sign --quiet
	C:\Python25\python.exe setup.py bdist_egg upload --identity="Andrew Carter" --sign --quiet
	C:\Python26\python.exe setup.py bdist_egg upload --identity="Andrew Carter" --sign --quiet
	C:\Python24\python.exe setup.py bdist_wininst --target-version=2.4 register upload --identity="Andrew Carter" --sign --quiet
	C:\Python25\python.exe setup.py bdist_wininst --target-version=2.5 register upload --identity="Andrew Carter" --sign --quiet
	C:\Python26\python.exe setup.py bdist_wininst --target-version=2.6 register upload --identity="Andrew Carter" --sign --quiet
	C:\Python26\python.exe setup.py sdist upload --identity="Andrew Carter" --sign
	C:\Python26\python.exe setup.py build_sphinx
	C:\Python26\python.exe setup.py upload_sphinx
	pause


usb library
===========

blablabla.

linux OS
________

blablabla.

windows OS
__________

blablabla.

mac OS
______

blablabla.

