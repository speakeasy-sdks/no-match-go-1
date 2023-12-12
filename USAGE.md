<!-- Start SDK Example Usage [usage] -->
```typescript
import { AccountsTest } from "accounts-test";

async function run() {
    const sdk = new AccountsTest();

    const res = await sdk.pets.createPets();

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->