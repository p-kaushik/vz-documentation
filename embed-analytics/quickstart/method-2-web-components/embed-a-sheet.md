---
icon: file-spreadsheet
---

# Embed a Sheet

Sheet is a collection of Visuals and Filters arranged in a specific layout to represent analysis.&#x20;

## Sheet

Visual can be embedded using <mark style="color:blue;">\<vz-sheet></mark> component.

````html
```
<vz-sheet
    properties='{
	"apiUrl":"https://analytics.viewzenlabs.in",
	"tenantId":"6627466466f7c7271de37edd",
	"dashboardId":"667121614b6547001c8a7757",
	"sheetId":"6671bcb74b6547001c8a784d"
    }'>
</vz-sheet>
```
````

<figure><img src="../../../.gitbook/assets/Screenshot from 2024-12-10 17-38-28.png" alt=""><figcaption><p>Embedded Sheet view</p></figcaption></figure>
