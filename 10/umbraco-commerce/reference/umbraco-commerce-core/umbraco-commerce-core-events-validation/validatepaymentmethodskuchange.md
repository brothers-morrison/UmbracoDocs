---
title: ValidatePaymentMethodSkuChange
description: API reference for ValidatePaymentMethodSkuChange in Umbraco Commerce
---
## ValidatePaymentMethodSkuChange

```csharp
public class ValidatePaymentMethodSkuChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidatePaymentMethodSkuChange

```csharp
public ValidatePaymentMethodSkuChange(PaymentMethodReadOnly paymentMethod, 
    ChangingValue<string> sku)
```


### Properties

#### PaymentMethod

```csharp
public PaymentMethodReadOnly PaymentMethod { get; }
```


---

#### Sku

```csharp
public ChangingValue<string> Sku { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->