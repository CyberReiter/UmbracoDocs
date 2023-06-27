---
title: ValidateShippingMethodAllowInCountryRegion
description: API reference for ValidateShippingMethodAllowInCountryRegion in Umbraco Commerce
---
## ValidateShippingMethodAllowInCountryRegion

```csharp
public class ValidateShippingMethodAllowInCountryRegion : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateShippingMethodAllowInCountryRegion

```csharp
public ValidateShippingMethodAllowInCountryRegion(ShippingMethodReadOnly shippingMethod, 
    Guid countryId, Guid? regionId)
```


### Fields

#### CountryId

```csharp
public Guid CountryId;
```


---

#### RegionId

```csharp
public Guid? RegionId;
```


### Properties

#### ShippingMethod

```csharp
public ShippingMethodReadOnly ShippingMethod { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->