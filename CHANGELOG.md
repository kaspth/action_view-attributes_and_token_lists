# Changelog

The noteworthy changes for each ActionView::AttributesAndTokenLists version are
included here. For a complete changelog, see the [commits] for each version via
the version links.

[commits]: https://github.com/seanpdoyle/action_view-attributes_and_token_lists

## main

* Enable chaining `#with_attributes` and `#tag` off of `Attributes` instances
  and instances of `AttributeMerger` returned by other `#with_attributes` calls

* Ensure that `Attributes` are compliant with Action View-provided `tag` helpers

* Add `Attributes#with_attributes` and `Attributes#with_options` alias to enable
  decorating and chaining
