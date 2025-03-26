---
description: Gobal configuration of ViewZen Components
icon: gear-complex
---

# Configuration

## Import

Import <mark style="color:blue;">VisualModule</mark> in your app.module.ts

```typescript
@NgModule({
  ...
  imports: [
    ...
    VisualModule
  ],
  ...
})
export class AppModule { }
```

## Set ViewZen Environment URL

Configure the library API URL to an on-premise or cloud hosted ViewZen Environment.

```typescript
import { Component } from '@angular/core';
import { ViewzenEnvironment } from '@viewzen/visual';

@Component({
  selector: 'app-root',
  templateUrl: './app.component.html',
  styleUrl: './app.component.scss'
})
export class AppComponent {
  ...
  constructor(){
    /* ---- MANDATORY ----- */
    /* To point to one of ViewZen's Analytics environment. */
    ViewzenEnvironment.apiURL = "https://analytics.viewzenlabs.in"
  }
}
```
