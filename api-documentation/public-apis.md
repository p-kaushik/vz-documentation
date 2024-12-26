---
icon: globe-pointer
---

# Public APIs



#### Get Columns & Expressions of datasets

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/datamgmt/datasets/columns" method="post" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Get Contexts, Mappings, Formulae of datasets

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/thesaurus/main/all" method="post" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Get details of a dashboard

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/dashboard/{dashboardId}" method="get" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Get details of specific components

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/dashboard/components" method="post" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Get All components of a sheet

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/dashboard/modify/{dashboardId}/sheet/{sheetId}/components" method="get" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Get  Visual's Data

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/fetchstoredata/{dashboardId}/{sheetId}/{componentId}/data" method="post" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Handshake API for PIvot

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/fetchstoredata/pivot/{dashboardId}/{sheetId}/{componentId}/handshake" method="post" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Get Pivot visual's data&#x20;

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/fetchstoredata/pivot/{dashboardId}/{sheetId}/{componentId}/select" method="post" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Get statistics of dataset columns, expressions for filter visual

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/fetchstoredata/{dashboardId}/{sheetId}/{componentId}/stats" method="post" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}

#### Get statistics of dataset columns, expressions for end user filters

{% swagger src="../.gitbook/assets/swagger-sample (1).json" path="/api/{tenantId}/fetchstoredata/{dashboardId}/stats" method="post" %}
[swagger-sample (1).json](<../.gitbook/assets/swagger-sample (1).json>)
{% endswagger %}
