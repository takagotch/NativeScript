### NativeScript
---
https://github.com/NativeScript/NativeScript

```js
import { Component } from "@angular/core";
import { routerExtensions } from "nativescript-angular/router";

@Component({
  moduleId: module.id,
  templateUrl: "./navigation-button.component.html"
})
export class NavigationButtonComponent {
  constructor(private routerExtensions: RouterExtensions) { }
  public goBack() {
    this.routerExtensions.backToPreviousPage();
  }
}
```

```
<ActionBar title=" NativeScript" android.icon="res://icon" android.iconVisibility="always">
  <NatigationButton icon="res://ic_arrow_back_black_24dp" (tap)="goBack()"></NavigationButton>
</ActionBar>
```

```
```

