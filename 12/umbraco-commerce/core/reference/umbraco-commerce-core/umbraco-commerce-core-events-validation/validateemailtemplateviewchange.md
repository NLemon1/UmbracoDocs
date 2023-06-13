---
title: ValidateEmailTemplateViewChange
description: API reference for ValidateEmailTemplateViewChange in Umbraco Commerce
---
## ValidateEmailTemplateViewChange

```csharp
public class ValidateEmailTemplateViewChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateEmailTemplateViewChange

```csharp
public ValidateEmailTemplateViewChange(EmailTemplateReadOnly emailTemplate, 
    ChangingValue<string> templateView)
```


### Properties

#### EmailTemplate

```csharp
public EmailTemplateReadOnly EmailTemplate { get; }
```


---

#### TemplateView

```csharp
public ChangingValue<string> TemplateView { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->