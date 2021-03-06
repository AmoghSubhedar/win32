---
Description: Enumerations that are used with authorization applications.
ms.assetid: e2f22838-102e-432c-9c82-06a3e0741374
title: Authorization Enumerations
ms.topic: article
ms.date: 05/31/2018
---

# Authorization Enumerations

The following enumerations are used with authorization applications.

## In this section



| Topic                                                                                          | Description                                                                                                                                                                                                                                                                           |
|------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [**ACCESS\_MODE**](https://msdn.microsoft.com/library/Aa374899(v=VS.85).aspx)<br/>                                                 | Contains values that indicate how the access rights in an [**EXPLICIT\_ACCESS**](/windows/desktop/api/AccCtrl/ns-accctrl-explicit_access_a) structure apply to the trustee.<br/>                                                                                                                                      |
| [**ACL\_INFORMATION\_CLASS**](/windows/desktop/api/Winnt/ne-winnt-acl_information_class)<br/>                            | Contains values that specify the type of information being assigned to or retrieved from an [access control list](https://docs.microsoft.com/windows/desktop/SecGloss/a-gly) (ACL).<br/>                                                               |
| [**AUDIT\_EVENT\_TYPE**](/windows/desktop/api/Winnt/ne-winnt-audit_event_type)<br/>                                      | Defines values that indicate the type of object being audited. The [**AccessCheckByTypeAndAuditAlarm**](/windows/desktop/api/Winbase/nf-winbase-accesscheckbytypeandauditalarma) and [**AccessCheckByTypeResultListAndAuditAlarm**](/windows/desktop/api/Winbase/nf-winbase-accesscheckbytyperesultlistandauditalarma) functions use these values.<br/>   |
| [**AUDIT\_PARAM\_TYPE**](/windows/desktop/api/Adtgen/ne-adtgen-audit_param_type)<br/>                                      | Defines the type of audit parameters that are available.<br/>                                                                                                                                                                                                                   |
| [**AUTHZ\_CONTEXT\_INFORMATION\_CLASS**](/windows/desktop/api/Authz/ne-authz-authz_context_information_class)<br/>       | Specifies the type of information to be retrieved from an existing AuthzClientContext. This enumeration is used by the [**AuthzGetInformationFromContext**](/windows/desktop/api/Authz/nf-authz-authzgetinformationfromcontext) function.<br/>                                                                  |
| [**AUTHZ\_SECURITY\_ATTRIBUTE\_OPERATION**](/windows/desktop/api/Authz/ne-authz-authz_security_attribute_operation)<br/> | Indicates the type of modification to be made to security attributes by a call to the [**AuthzModifySecurityAttributes**](/windows/desktop/api/Authz/nf-authz-authzmodifysecurityattributes) function.<br/>                                                                                                     |
| [**AUTHZ\_SID\_OPERATION**](/windows/desktop/api/Authz/ne-authz-authz_sid_operation)<br/>                                | Indicates the type of SID operations that can be made by a call to the [**AuthzModifySids**](/windows/desktop/api/Authz/nf-authz-authzmodifysids) function.<br/>                                                                                                                                                |
| [**AZ\_PROP\_CONSTANTS**](/windows/win32/api/azroles/ne-azroles-az_prop_constants)<br/>                                    | Defines constants used by Authorization Manager.<br/>                                                                                                                                                                                                                           |
| [**MANDATORY\_LEVEL**](/windows/desktop/api/Winnt/ne-winnt-mandatory_level)<br/>                                         | Lists the possible security levels.<br/>                                                                                                                                                                                                                                        |
| [**MULTIPLE\_TRUSTEE\_OPERATION**](/windows/desktop/api/AccCtrl/ne-accctrl-multiple_trustee_operation)<br/>                  | Contains values that indicate whether a [**TRUSTEE**](/windows/desktop/api/AccCtrl/ns-accctrl-trustee_a) structure is an impersonation trustee.<br/>                                                                                                                                                                  |
| [**PROG\_INVOKE\_SETTING**](/windows/win32/api/accctrl/ne-accctrl-prog_invoke_setting)<br/>                                | Indicates the initial setting of the function used to track the progress of a call to the [**TreeSetNamedSecurityInfo**](/windows/desktop/api/Aclapi/nf-aclapi-treesetnamedsecurityinfoa) or [**TreeResetNamedSecurityInfo**](/windows/desktop/api/Aclapi/nf-aclapi-treeresetnamedsecurityinfoa) function.<br/>                                       |
| [**SE\_OBJECT\_TYPE**](/windows/desktop/api/AccCtrl/ne-accctrl-se_object_type)<br/>                                          | Contains values that correspond to the types of Windows objects that support security.<br/>                                                                                                                                                                                     |
| [**SECURITY\_IMPERSONATION\_LEVEL**](/windows/desktop/api/Winnt/ne-winnt-security_impersonation_level)<br/>              | Contains values that specify security impersonation levels. Security impersonation levels govern the degree to which a server process can act on behalf of a client [process](https://docs.microsoft.com/windows/desktop/SecGloss/p-gly).<br/>                                 |
| [**SI\_PAGE\_TYPE**](/windows/desktop/api/Aclui/ne-aclui-si_page_type)<br/>                                              | Contains values that indicate the types of property pages in an access control editor property sheet.<br/>                                                                                                                                                                      |
| [**SID\_NAME\_USE**](/windows/desktop/api/Winnt/ne-winnt-sid_name_use)<br/>                                              | Contains values that specify the type of a [security identifier](https://docs.microsoft.com/windows/desktop/SecGloss/s-gly) (SID).<br/>                                                                                                                |
| [**TOKEN\_ELEVATION\_TYPE**](/windows/desktop/api/Winnt/ne-winnt-token_elevation_type)<br/>                             | Indicates the elevation type of token being queried by the [**GetTokenInformation**](https://msdn.microsoft.com/library/Aa446671(v=VS.85).aspx) function or set by the [**SetTokenInformation**](https://msdn.microsoft.com/library/Aa379591(v=VS.85).aspx) function.<br/>                                                                          |
| [**TOKEN\_INFORMATION\_CLASS**](/windows/desktop/api/Winnt/ne-winnt-token_information_class)<br/>                        | Contains values that specify the type of information being assigned to or retrieved from an [access token](https://docs.microsoft.com/windows/desktop/SecGloss/a-gly).<br/>                                                                                          |
| [**TOKEN\_TYPE**](/windows/desktop/api/Winnt/ne-winnt-token_type)<br/>                                                   | Contains values that differentiate between a [primary token](https://docs.microsoft.com/windows/desktop/SecGloss/p-gly) and an [impersonation token](https://docs.microsoft.com/windows/desktop/SecGloss/i-gly).<br/>                     |
| [**TRUSTEE\_FORM**](/windows/desktop/api/AccCtrl/ne-accctrl-trustee_form)<br/>                                               | Values that indicate the type of data pointed to by the **ptstrName** member of the [**TRUSTEE**](/windows/desktop/api/AccCtrl/ns-accctrl-trustee_a) structure.<br/>                                                                                                                                                  |
| [**TRUSTEE\_TYPE**](/windows/desktop/api/AccCtrl/ne-accctrl-trustee_type)<br/>                                               | Values that indicate the type of trustee identified by a [**TRUSTEE**](/windows/desktop/api/AccCtrl/ns-accctrl-trustee_a) structure.<br/>                                                                                                                                                                             |
| [**WELL\_KNOWN\_SID\_TYPE**](/windows/desktop/api/Winnt/ne-winnt-well_known_sid_type)<br/>                               | A list of commonly used [security identifiers](https://docs.microsoft.com/windows/desktop/SecGloss/s-gly) (SIDs). Programs can pass these values to the [**CreateWellKnownSid**](https://msdn.microsoft.com/library/Aa446585(v=VS.85).aspx) function to create a SID from this list.<br/> |



 

 

 




