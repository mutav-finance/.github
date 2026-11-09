# MUTAV Finance

 > Real guarantees with reserves built to be checked
 
MUTAV is an institutional guarantor for Brazilian rentals. Tenants get a rental guarantee (Lei 8.245/91 art. 37 II) instead of a personal guarantor or a multi-month deposit, and real-estate agencies offer it through the leases they already run. Every guarantee is backed by an on-chain reserve that rental agencies can audit.

Transparency stops being a promise and becomes the product.

www.mutav.finance/en

  ## The market
  
Brazil has 17.8M rented households (IBGE, 2024), a 45.4% increase since 2016. High interest rates make mortgages more expensive, pushing more families toward renting. Today, 49% of rental agreements use paid guarantees (Forcecure, 2024), representing a market worth approximately $11B annually. Brazil's 74,000 real-estate agencies sit at the center of this market, connecting tenants, landlords, and guarantee providers.

Yet **the reserves backing these guarantees remain a black box.** Agencies cannot independently verify whether providers have the funds to honor their commitments. In 2025, a big proptech shut down the operation, leaving +45,000 contracts without coverage (InfoMoney, 2025). Even when guarantees hold, payouts can take 60 to 90 days, forcing agencies to advance rent from their own cash.    

  ## How it works

  1. Contract. The agency offers MUTAV as an alternative to a personal guarantor or security deposit.
  2. Monthly fee. The tenant pays a monthly fee alongside rent. Part covers MUTAV's operations; the rest builds the reserve.
  3. Reserve yield. Funds are held in Brazilian bonds, and all generated yield goes back into the reserve.
  4. Late rent. The agency submits a claim, MUTAV verifies it, and the reserve funds the payment to the agency. MUTAV then initiates the debt recovery process with the tenant.
  5. Coverage gate. New guarantees are issued only when the reserve has sufficient coverage for all active contracts. Existing claims are never blocked.
  6. Capital structure. The model allows capital to be allocated to guarantee coverage, with returns generated through fees and reserve yield. All reserve activity is publicly verifiable on Solana.
  
## Protocol repos

The MUTAV protocol is organized across different repositories, covering the Solana and Stellar implementations, core applications and supporting infrastructure:

| Repo                  | What it is                                                                                                   |
|-----------------------|--------------------------------------------------------------------------------------------------------------|
| [mutav-protocol-solana](https://github.com/mutav-finance/mutav-protocol-solana) | The reserve program on Solana. |
| [mutav-app](https://github.com/mutav-finance/mutav-app) | The platform: the agency and operator apps plus the MUTAV API. |
| [mutav-stellar](https://github.com/mutav-finance/mutav-stellar) | Soroban Fund contract and TypeScript SDK, built in the NearX acceleration program.                           |
| [mutav-pulse](https://github.com/mutav-finance/mutav-pulse) | Solvency-gated reserve vault on Stellar, built for the Stellar Pulso hackathon.                              |

## Team
- **[draaujpeg](https://github.com/draaujpeg)**, Cofounder and CEO. Five years building blockchain products and the brands around them; grew up in a family with 30+ years in Brazilian real estate.
- **[jubscodes](https://github.com/jubscodes)**, Cofounder and CTO. Architect, designer and engineer; builds the product end to end, from systems architecture and UX to on-chain infrastructure.

## Access

| Team | Permission | Who |
|------|-----------|-----|
| **builders** | Maintain: push branches, open & merge PRs, manage issues | Core contributors |
| **judges** | Read: view code, issues, and PRs (no write access) | Hackathon & competition evaluators |
