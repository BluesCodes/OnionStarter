# Core/Domain Layer

## Purpose:
The Core/Domain Layer represents the central part of the Onion Architecture. It contains the core business entities and the rules that govern them. This layer should remain completely independent of other layers and external frameworks.

## Key Responsibilities:
1. Define **Entities**:
   - Represent tables/class/objects in its purest form.
2. Create **Value Objects**:
   - Immutable objects representing a concept (e.g., `Email`, `Money`).
3. Define **Domain Services**:
   - Stateless services encapsulating core business rules that involve multiple entities.
4. Define **Enums**:
   - Enumerations for domain-specific statuses or types (e.g., `OrderStatus`).
5. Handle **Custom Exceptions**:
   - Define exceptions specific to the domain (e.g., `DomainValidationException`).