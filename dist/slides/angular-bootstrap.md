#### Angular bootstrap (works with AOT)

```
import {
    NgModule, NO_ERRORS_SCHEMA
} from '@angular/core';

import {
    platformNativeScriptDynamic, NativeScriptModule
} from "nativescript-angular/platform";
```

```
@NgModule({
    imports: [
        NativeScriptModule
    ],
    schemas: [NO_ERRORS_SCHEMA]
}) export class AppModule {}

platformNativeScriptDynamic().bootstrapModule(AppModule);
```
