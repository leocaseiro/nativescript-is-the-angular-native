## RouterExtensions

```
export class MainComponent {
    constructor(private routerExtensions: RouterExtensions) {}
}
```

```
login() {
    this.routerExtensions.navigate(["/main"], {
        clearHistory: true
    });
}
```
```
back() {
    // backToPreviousPage() - goes back to the previous page ignoring child router-outlet.
    this.routerExtensions.backToPreviousPage();

    // back() - goes back to the previous router location even if the navigation occurred inside the child router outlet on the current page.
    this.routerExtensions.back();
}
```
