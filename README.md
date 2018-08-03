This gem did not have a github that could be forked, so I unpacked the gem
from rubygems and re-added a gemspec so we can patch it.

Previously, the gem monkeypatched the Time#to_json method, which started to break
our code in rails 4.

The original code is distributed under the Apache 2.0 license.
