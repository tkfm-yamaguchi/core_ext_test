
# Active Support's core_ext test

Since version 4, we should require the "active_support" before requiring "active_support/core_ext" otherwise the error below was throws.

```
NameError: uninitialized constant ActiveSupport::Autoload
```

I want to check the backward compatibility whether it is OK if we require the "active_support" before requiring "active_support/core_ext" using ActiveSupport whose version is lower than 4.
This do that.

