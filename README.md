# Activitypub Data Portability

Repository for the  ActivityPub Data Portability Task Force of the social web community group at W3C.

We maintain:

* A descriptive report covering the Data Portability problem space, which so far lists all the different data surfaces that end-users might want to include in scope of portability use-cases. The current editor's draft of this report is [here](https://swicg.github.io/activitypub-data-portability/)
* A draft of a Server-to-Server transfer protocol called LOLA. The current editor's draft of this report is [here](https://swicg.github.io/activitypub-data-portability/)

Input documents from the developer community that we've discussed on calls and may be taken on as work items in the future (See the CG's [Staging Process](https://github.com/swicg/potential-charters/blob/main/stage-process.md)):

* Use-case Docs
  * [FEP-6fcd: Migration User Stories](https://codeberg.org/fediverse/fep/src/branch/main/fep/6fcd/fep-6fcd.md)
  * [FEP-cd47: Federation-friendly Addressing and Deduplication Use-Cases](https://fediverse.codeberg.page/fep/fep/cd47/)
* Mastodon-iverse Move Actor Model
  * [FEP-7628: Move actor](https://fediverse.codeberg.page/fep/fep/7628) - Retrospecification of the migration flow between Mastodon API implementations
  * [FEP-e965: Move Activity for Migrations and Announce Activity for Tombstone Events](https://fediverse.codeberg.page/fep/fep/e965) - Written to harmonize/formalize inactive "tombstoned" Actor object behavior
* Server-Independent Approaches
  * [FEP-c390: Identity Proofs](https://fediverse.codeberg.page/fep/fep/c390/) - Make verification of Activities server-independent with assymetrical keys in Actor object
  * [FEP-ef61: Portable Objects](https://fediverse.codeberg.page/fep/fep/ef61/) - Proposes an ap:// URI scheme for server-independent permalinks
  * [FEP-e3e9: Actor-Relative URLs](https://fediverse.codeberg.page/fep/fep/e3e9/) - Proposes a "microserver" per user that just forwards from permalinks to current Outbox server
  * [FEP-6fcd: Account Export Container Format](https://fediverse.codeberg.page/fep/fep/6fcd) - Proposes an AP-wide "data takeout" format similar to but supersetting the Mastodon export file format
  * [FEP-9091: Export Actor Service Endpoint](https://fediverse.codeberg.page/fep/fep/9091) - Proposes a generic AP endpoints for requesting these^ export files from a given outbox server
