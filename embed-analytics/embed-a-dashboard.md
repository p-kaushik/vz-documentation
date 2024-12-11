---
icon: rectangle-vertical-history
---

# Embed a dashboard

Dashboard is a collection of sheets to represent all analysis related to specific topic

## Dashboard

Visual can be embedded using <mark style="color:blue;">\<viewzen-dashboard></mark> component.

{% tabs %}
{% tab title="app.component.ts" %}
```typescript
import { Component } from "@angular/core";
import { ViewzenEnvironment } from "@viewzen/visual";

@Component({
	selector: "app-root",
	templateUrl: "./app.component.html",
	styleUrl: "./app.component.scss",
})
export class AppComponent {
	public tenantId: string = "6627466466f7c7271de37edd";
	public dashboardId: string = "667121614b6547001c8a7757";

	constructor() {
		ViewzenEnvironment.apiURL = "https://analytics.viewzenlabs.in";
	}
}
```
{% endtab %}

{% tab title="app.component.html" %}
```html
<viewzen-dashboard
	[tenantId]="tenantId"
	[dashboardId]="dashboardId">
</viewzen-dashboard>
```
{% endtab %}
{% endtabs %}

<figure><img src="../.gitbook/assets/Screenshot from 2024-12-10 17-47-54.png" alt=""><figcaption><p>Embedded Dashboard view</p></figcaption></figure>
