Object models of Gateway System

- __[HOME](../../index.html)
- __[MODELS](../../models.html)
- __[CONTRIBUTE](../../contribute.html)
- __[ABOUT US](../../aboutUs.html)


#### Gateway System

#### LWM2M

#### object version

#### descripton

#### Resource fields

| Resource        | ID | Access Type | Multiple Instances | Mandatory | type   | Description |
| --------------- |--- | ----------- | -----------------  | ----------| -------| ----------- |
| Hostname        | 0  | R,W         | Single             | Mandatory | String | This resource type returns the hostname of the gateway. |
| Timezone        | 1  | R,W         | Single             | Optional  | String | This resource type returns the default timezone. |
| DNS Server List | 2  | R,W         | Single             | Optional  | String | This resource type returns a list of DNS Servers used by this system. |
| NTP Server List | 3  | R,W         | Single             | Optional  | String | This resource type returns a list of NTP Servers. |

#### Example usage

The gateway system object contains the most basic functionalities for a gateway such as its name, timezone and so on. All properties are represented as readable and writable resources using standard LWM2M operations.

#### XML

#### JSON

#### Example usage

#### Code

#### Wakaama

#### UCI

#### Description

OpenWRT gateway native data model for the whole gateway

#### Config

#### URL

#### System

