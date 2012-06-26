# DESCRIPTION:

This cookbook provides a way to easily tune JRuby. There are defaults for
different instance sizes but you may want to further customize the settings.

# USAGE:

1. Modify `main/recipes/default.rb` to `require_recipe "jruby"`
2. Upload your new recipes to the environment `ey recipes upload -e <ENV>`
3. Apply recipes

