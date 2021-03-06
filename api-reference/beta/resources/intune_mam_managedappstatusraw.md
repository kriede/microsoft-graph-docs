﻿# managedAppStatusRaw resource type> **Note:** Using the Microsoft Graph APIs to configure Intune controls and policies still requires that the Intune service is [correctly licensed](https://www.microsoft.com/en-us/cloud-platform/microsoft-intune-pricing) by the customer.

Represents an un-typed status report about organizations app protection and configuration.

Inherits from [managedAppStatus](../resources/intune_mam_managedappstatus.md)

### Methods
|Method|Return Type|Description|
|---|---|---|
|[List managedAppStatusRaws](../api/intune_mam_managedappstatusraw_list.md)|[managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md) collection|List properties and relationships of the [managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md) objects.|
|[Get managedAppStatusRaw](../api/intune_mam_managedappstatusraw_get.md)|[managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md)|Read properties and relationships of the [managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md) object.|
|[Create managedAppStatusRaw](../api/intune_mam_managedappstatusraw_create.md)|[managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md)|Create a new [managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md) object.|
|[Delete managedAppStatusRaw](../api/intune_mam_managedappstatusraw_delete.md)|None|Deletes a [managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md).|
|[Update managedAppStatusRaw](../api/intune_mam_managedappstatusraw_update.md)|[managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md)|Update the properties of a [managedAppStatusRaw](../resources/intune_mam_managedappstatusraw.md) object.|

### Properties
|Property|Type|Description|
|---|---|---|
|displayName|String|Friendly name of the status report. Inherited from [managedAppStatus](../resources/intune_mam_managedappstatus.md)|
|id|String|Key of the entity. Inherited from [managedAppStatus](../resources/intune_mam_managedappstatus.md)|
|version|String|Version of the entity. Inherited from [managedAppStatus](../resources/intune_mam_managedappstatus.md)|
|content|[managedAppSummary](../resources/intune_mam_managedappsummary.md)|Status report content.|

### Relationships
None
### JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.managedAppStatusRaw"
}
-->
```json
{
  "@odata.type": "#microsoft.graph.managedAppStatusRaw",
  "displayName": "String",
  "id": "String (identifier)",
  "version": "String",
  "content": {
    "@odata.type": "microsoft.graph.managedAppSummary"
  }
}
```



