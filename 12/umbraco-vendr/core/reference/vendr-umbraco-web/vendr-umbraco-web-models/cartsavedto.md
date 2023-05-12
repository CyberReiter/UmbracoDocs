---
title: CartSaveDto
description: API reference for CartSaveDto in Vendr, the eCommerce solution for Umbraco
---
## CartSaveDto

```csharp
public class CartSaveDto : CartDto, IValidatableObject
```

**Inheritance**

* class [CartDto](../cartdto/)

**Namespace**
* [Vendr.Umbraco.Web.Models](../)

### Constructors

#### CartSaveDto

The default constructor.

```csharp
public CartSaveDto()
```


### Properties

#### DiscountOrGiftCardCode

```csharp
public string DiscountOrGiftCardCode { get; set; }
```


### Methods

#### Validate

```csharp
public IEnumerable<ValidationResult> Validate(ValidationContext validationContext)
```


<!-- DO NOT EDIT: generated by xmldocmd for Vendr.Umbraco.Web.dll -->