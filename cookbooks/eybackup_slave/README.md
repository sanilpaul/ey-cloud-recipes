# Description

Moves `eybackup` from the `db_master` to the `db_slave`.

# Installation

To install this, you will need to add the following to cookbooks/main/recipes/default.rb:

    require_recipe "eybackup_slave"

Make sure this and any customizations to the recipe are committed to your own fork of this 
repository.
