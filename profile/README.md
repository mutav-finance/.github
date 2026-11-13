# MUTAV Finance

> Real guarantees with reserves built to be checked

MUTAV is an institutional guarantor for Brazilian rentals. Tenants get a rental guarantee (Lei 8.245/91 art. 37 II) instead of a personal guarantor or a multi-month deposit, and real-estate agencies offer it through the leases they already run. Every guarantee will be backed by an on-chain reserve that rental agencies can audit.

Transparency stops being a promise and becomes the product.

www.mutav.finance/en

## How it works

1. Contract. The agency offers MUTAV as an alternative to a personal guarantor or security deposit.
2. Monthly fee. The tenant pays a monthly fee alongside rent. Part covers MUTAV's operations; the rest builds the reserve.
3. Reserve assets. During the pilot the reserve holds BRS, a BRL stablecoin. Tokenized Brazilian government bonds are planned.
4. Late rent. The agency submits a claim, MUTAV verifies it, and the reserve funds the payment to the agency. MUTAV then initiates the debt recovery process with the tenant.
5. Coverage gate. New guarantees are issued only when the reserve has sufficient coverage for all active contracts. The gate blocks new guarantees only; it does not block claims on active ones.
6. Outside capital. The pilot runs on MUTAV's own capital. Once the operation is proven, the model allows outside capital to back guarantee coverage only through a regulated vehicle, after legal review. All reserve activity will be publicly verifiable on Solana.

## Where we are

- **Today:** a demo at [reserve.mutav.finance](https://reserve.mutav.finance) and the Squads multisig on Solana that operations will start from. There is no operating reserve yet.
- **Next:** the multisig becomes the pilot reserve, holding BRS (a BRL stablecoin), followed by the audited MUTAV vault program.
- The pilot is **not open to public investment**.

## Protocol repos

The MUTAV protocol is organized across different repositories, covering the Solana and Stellar implementations, core applications and supporting infrastructure:

| Repo | What it is | State |
|------|------------|-------|
| [mutav-protocol-solana](https://github.com/mutav-finance/mutav-protocol-solana) | The reserve program on Solana. | Deployed on devnet, pre-external-audit |
| [mutav-app](https://github.com/mutav-finance/mutav-app) | The platform: the agency and operator apps plus the MUTAV API. | Deployed, pre-launch (app, admin) |
| [mutav-stellar](https://github.com/mutav-finance/mutav-stellar) | Soroban reserve contract and TypeScript SDK, built in the NearX acceleration program. | Proof of concept |
| [mutav-pulse](https://github.com/mutav-finance/mutav-pulse) | Reserve vault on Stellar, gated by required coverage, built for the Stellar Pulso hackathon. | Proof of concept (hackathon) |

[mutav-fund](https://github.com/mutav-finance/mutav-fund) is retired.

## Team
- **[draaujpeg](https://github.com/draaujpeg)**, Cofounder and CEO. Five years building blockchain products and the brands around them; grew up in a family with 30+ years in Brazilian real estate.
- **[jubscodes](https://github.com/jubscodes)**, Cofounder and CTO. Architect, designer and engineer; builds the product end to end, from systems architecture and UX to on-chain infrastructure.

## Access

| Team | Permission | Who |
|------|-----------|-----|
| **builders** | Maintain: push branches, open & merge PRs, manage issues | Core contributors |
| **judges** | Read: view code, issues, and PRs (no write access) | Hackathon & competition evaluators |
