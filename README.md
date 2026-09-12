# genesis-chronicles [L6]

Genesis Chronicles — **Premium-Flagship-/Reference-Game** auf ATC Genesis Engine (Rollenverteilung gemäß [GEN-PROD-001](https://github.com/A-TownChain-Okosystems/genesis-engine/blob/main/docs/specs/GEN-PROD-001-PRODUCT-STRATEGY.md), SPEC-DRAFT) + ATC-9000-NFTs. AD-025, ehemals Shivamon.

> Die Engine entwickelt die Technologie — dieses Spiel zeigt, was sie leisten kann. Spielspezifische Logik (Contracts, Battle, Breeding, NFT-Mint) bleibt in diesem Repo; generische Features laufen über das Feature-Promotion-Gate in die Engine.

**Vault-Restauration (07.09.2026, AD-020/026/027):** Inhalt aus dem Wiki-Vault
(docs/archive/monorepo-full/) restauriert — vor der Repo-Leerung byte-identisch gesichert. AD-025-Korrektur angewendet: Shivamon-Bezeichner in Genesis Chronicles umbenannt (Contract-IDs, Modul-Dir).

**Module:** atc-shivamon, atc-game

**Meile (AD-027):** M7 CLAIMED — Evidence incomplete (Game Loop + NFT-Mint-TX reproduzierbar nachweisen, SCR-0073): Spiel-Loop + NFT-Mint als Chain-Transaktion

**Hinweis:** Basis fuer den Rebuild; Gate-Kriterien laut LAUFFAEHIGKEITS_ROADMAP
(a-townchain-os-docs/docs/roadmap/).

---

## ATC Compliance & Governance (ATC-STD-201 / 202 / 203)

**ATC COMPLIANCE: R2** — auditiert am 2026-09-07 (atc-repo-audit; R-Level aus `.atc/repository.yaml`).
Architekturentscheidungen: zentral im [DECISIONS_REGISTER](https://github.com/A-TownChain-Okosystems/a-townchain-os-docs/blob/main/docs/DECISIONS_REGISTER.md) (AD-Nummern verbindlich; lokale Entscheidungen in `docs/decisions/`).

- **Purpose:** Genesis Chronicles (vormals Shivamon, AD-025) — das Spiel (L6); Premium-Flagship-/Reference-Game auf ATC Genesis Engine.
- **Scope:** Layer L6, Domain game — genesis-chronicles als GAME in der 23-Repo-Landschaft (AD-024/026).
- **Architecture:** Genesis-Engine-Integration; NFTs per ATC-9000 auf Chain-ID 658467.
- **Features:** Spiel-Module; 20 Dateien AD-025-konform umbenannt.
- **Installation:** Modul-Build je Sprache (rust); Integration via Monorepo-Workspace (a-townchain-os, sync_modules.py).
- **Development:** Conventional Commits; Governance-Regeln aus atc-standards; Naming gemaess ATC-STD-000 §7.
- **Testing:** Spiel-Gate M7: NFT auf Chain.
- **Security:** SECURITY.md; S-Klasse S1; ATC-STD-203 Release-Gates; Emergency-Prozess ATC-STD-000 §32.
- **Roadmap:** Einordnung in die Lauffaehigkeits-Roadmap M1-M8 (AD-027) und Bauhierarchie L0-L7 (AD-026).
- **Version:** CHANGELOG.md; SemVer; Releases als ATC-REL-X.Y.Z.
- **License:** Apache-2.0 — Apache-2.0, Michael Wroblewski / ShivaCore / A-TownChain-Okosystems (ATC-LIC/ATS-LIC).
