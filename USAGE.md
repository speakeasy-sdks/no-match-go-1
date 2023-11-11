<!-- Start SDK Example Usage -->
```typescript
import { AccountsTest } from "accounts-test";

(async () => {
    const sdk = new AccountsTest();

    const res = await sdk.pets.createPets();

    if (res.statusCode == 200) {
        // handle response
    }
})();

```
<!-- End SDK Example Usage -->