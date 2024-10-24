```mermaid
sequenceDiagram
    participant ClientService
    participant PaymentService
    participant InventoryService
    participant ShippingService

    ClientService->>PaymentService: Request Payment
    PaymentService-->>InventoryService: Update Inventory
    InventoryService-->>ShippingService: Ship Order
    ShippingService-->>InventoryService: Confirm Shipment
    InventoryService-->>PaymentService: Update Payment Status
    PaymentService-->>ClientService: Return Payment Status

```