What's this?
------------
Instead of using the issues/ticket functionality of GitHub, I'd rather have a short list of ideas that might be integrated into the script at some time.


Priority "Would love to have that in"
-------------------------------------
✔ asking for the package name that should be packaged into this distribution (and it's git repo URL so it can be directly hooked in as a submodule)
✔ asking for the Distribution name to build
✔ asking whether the Admin-Package should be integrated and activated
✔ remove the routes for the welcome package from the routes.yaml file
✔ adding the admin routes to routes.yaml if the Admin Package is included
- ask for database credentials (see https://github.com/markusbucher/installFlow3.sh)
	- to create the neccessary Settings.yaml file
	- to create an empty database
- ask the user for his name/e-mail for the initial commit


Priority "May be"
-----------------
- send a nice greeting message to the author whenever this script is run :-)
- asking for the target, where this newly created distribution shall be pushed to (e.g. to directly publish it on github or the like)
- asking for the FLOW3 release (tag name) that should be taken to build the distribution instead of HEAD