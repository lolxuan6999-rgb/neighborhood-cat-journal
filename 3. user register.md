### ⚖️ Product Trade-Offs & Strategic Decisions: The Anonymous-First Model

#### The Choice
I made the conscious strategic decision to prioritize a **completely friction-free, unregistered posting model**. My goal was to eliminate all onboarding barriers so neighbors could instantly contribute data and share local cats the moment a sighting occurs, without being forced to create an account. 

#### Product Limitations (The Constraints)
Choosing accessibility over mandatory authentication introduces specific user experience limitations that I proactively identified:
* **Lack of Direct Notifications:** Because users do not maintain active accounts, they will not receive automated push alerts or updates when new animals are discovered or when their own posts receive updates. 
* **Lack of System-Level Credit:** Contributions default to an "Anonymous" tag, meaning the system cannot natively reward high-contributing users with localized profile metrics. 

#### The Strategic Validation (Why This Model Works Anyway)
Despite these structural limitations, the core value proposition of the product remains intact due to two deliberate design safeguards:

1. **The Retention Loop:** The visual layout operates as an interactive local registry. Users naturally return to the platform out of curiosity to manually browse the board, check for newly added community animals, and review updates across neighborhood sectors. 
2. **The "Self-Sign" Workaround for Attribution:** To counter the anonymity problem, I engineered a community submission protocol. Unregistered users are instructed to include their name or block identifier directly within the post description and use their mobile device to upload an original photo. This manual verification acts as an append-only token of original ownership, proving attribution without the overhead of a database login wall.
