
# Order

## Structure

`Order`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `id` | `?int` | Optional | - | getId(): ?int | setId(?int id): void |
| `petId` | `?int` | Optional | - | getPetId(): ?int | setPetId(?int petId): void |
| `quantity` | `?int` | Optional | - | getQuantity(): ?int | setQuantity(?int quantity): void |
| `shipDate` | `?DateTime` | Optional | - | getShipDate(): ?\DateTime | setShipDate(?\DateTime shipDate): void |
| `status` | [`?string (Status1Enum)`](../../doc/models/status-1-enum.md) | Optional | Order Status | getStatus(): ?string | setStatus(?string status): void |
| `complete` | `?bool` | Optional | - | getComplete(): ?bool | setComplete(?bool complete): void |

## Example (as JSON)

```json
{
  "id": 112,
  "petId": 152,
  "quantity": 68,
  "shipDate": "2016-03-13T12:52:32.123Z",
  "status": "delivered"
}
```

