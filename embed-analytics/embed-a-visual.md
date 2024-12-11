---
icon: chart-mixed
---

# Embed a visual

Visuals in ViewZen Analytics can be Charts, Grids, Pivot, Cards, Images, Text, Maps etc.

## Visual

Visual can be embedded using <mark style="color:blue;">\<viewzen-visual></mark> component.

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
	public sheetId: string = "6671bcb74b6547001c8a784d";
	public componentId: string = "6671be964b6547001c8a7f23";

	constructor() {
		ViewzenEnvironment.apiURL = "https://analytics.viewzenlabs.in";
	}
}
```
{% endtab %}

{% tab title="app.component.html" %}
```html
<viewzen-visual
	[tenantId]="tenantId"
	[dashboardId]="dashboardId"
	[sheetId]="sheetId"
	[componentId]="componentId">
</viewzen-visual>
```
{% endtab %}
{% endtabs %}

<figure><img src="../.gitbook/assets/Screenshot from 2024-12-10 17-18-23.png" alt=""><figcaption><p>Embedded Visual view</p></figcaption></figure>
