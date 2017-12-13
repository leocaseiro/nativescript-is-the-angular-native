### NativeScriptRouterModule

```
import {
    NativeScriptRouterModule
} from "nativescript-angular/router";

@NgModule({
    imports: [
        NativeScriptModule,
        NativeScriptRouterModule,
        NativeScriptRouterModule.forRoot(routes),
    ]
})
class AppModule {}
```

```
<router-outlet></router-outlet>
```

```
<page-router-outlet></page-router-outlet>
```

