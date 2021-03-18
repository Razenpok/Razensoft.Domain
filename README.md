Razensoft.Domain
======================================================

This library supplies base classes for domain-driven development.

## DISCLAIMER

Most of the code in this library is originating from the awesome [CSharpFunctionalExtensions](https://github.com/vkhorikov/CSharpFunctionalExtensions) project which you should definitely check out.

Differences between **Razensoft.Domain** (1.0.0) and **CSharpFunctionalExtensions** (v2.14.5):

- Removed legacy implementation of `ValueObject<T>`
- Renamed `SimpleValueObject<T>` to `ValueObject<T>`
- Renamed root namespace from `CSharpFunctionalExtensions` to `Razensoft.Domain`
- Added `AggregateRoot` and `IDomainEvent`

## Installation

Add this line to your `manifest.json` file:

```
"com.razensoft.functional": "https://github.com/Razenpok/Razensoft.Domain.git?path=src/Razensoft.Domain#1.0.0",
```

UPM should automatically install the package.

## Contributors
A big thanks to the project author, [Vladimir Khorikov](https://github.com/vkhorikov), and to all of the contributors of the original project. Again, [don't forget to check it out](https://github.com/vkhorikov/CSharpFunctionalExtensions)!