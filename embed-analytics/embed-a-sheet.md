---
icon: file-spreadsheet
---

# Embed a Sheet

Sheet is a collection of Visuals and Filters arranged in a specific layout to represent analysis.&#x20;

## Sheet

Visual can be embedded using <mark style="color:blue;">\<viewzen-sheet></mark> component.

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

	constructor() {
		ViewzenEnvironment.apiURL = "https://analytics.viewzenlabs.in";
	}
}
```
{% endtab %}

{% tab title="app.component.html" %}
```html
<viewzen-sheet
	[tenantId]="tenantId"
	[dashboardId]="dashboardId"
	[sheetId]="sheetId">
</viewzen-sheet>
```
{% endtab %}
{% endtabs %}

<figure><img src="../.gitbook/assets/Screenshot from 2024-12-10 17-38-28.png" alt=""><figcaption><p>Embedded Sheet view</p></figcaption></figure>
