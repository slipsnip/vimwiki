# Adding packages #
        * cd .vim
        * git submodule add <repo> pack/<group>/start/<pkg_name>
        
# Remove package #
        * cd .vim
        * git submodule deinit pack/<group>/start/<pkg_name>
        * git rm pack/<group>/<start>/<pkg_name>
        * rm -Rf .git/modules/pack/<group>/start/<pkg_name>
        * git commit


