## UserPermission

Represents the Portal user permission.

| MIME type                                 |
|-------------------------------------------|
| application/vnd.iris.portal.user-permission+json |

| Name               | Description                                   | Type                                    |
|--------------------|-----------------------------------------------|-----------------------------------------|
| userIdentity       | the user identifier                           | Identity                                |
| permissionId       | the id of the permission                      | string                                  |
| updateDate         | the date that the permission has last changed | DateTimeOffset                          |
| actions            | the action of the permission                  | PermissionAction array                  |