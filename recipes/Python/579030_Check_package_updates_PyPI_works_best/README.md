## Check for package updates on PyPI (works best in pip+virtualenv)

Originally published: 2015-03-04 11:01:43
Last updated: 2015-03-04 11:01:44
Author: migonzalvar 

Pip has an option to upgrade a package (_pip install -U_), however it always downloads sources even if there is already a newest version installed. If you want to check updates for all installed packages then some scripting is required.