# be-referential

Climb up the ShadowDOM hierarchy searching for element with matching id, and create a weak reference to it.

```html
<template id=my-id be-referential></template>
```

Accessible via oTemplate.beDecorated.referential.ref

Emits event 'be-decorated.referential.resolved' when found.

Emits event 'be-decorated.referential.rejected' when not found.
