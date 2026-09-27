# Fitness-project retirement

Decision date: 27 September 2026.

The owner authorized retiring the fitness project and assigning Kinetexa and kinetexa.com to the separate Caloxora-derived informational publication.

## Preservation

The final development commit before retirement is `6f2a0b85585bbbe1a0c86b8a57ab92fcce11c280`. All existing branches, tags, issues, releases and pull requests stay with this repository. Its new name is `StefanDG1/kinetexa-fitness-archive`. The AGPL-3.0-only license remains in force. A verified local Git bundle preserves all fetched refs before changes. Ignored local configuration stays with the original checkout and is not in that bundle.

The old `StefanDG1/Kinetexa` name is intentionally reused for the separate private publication. GitHub will therefore not redirect that old name to this archive. Use the archive URL explicitly when citing or restoring the fitness code. Do not link the publication as this application's corresponding source.

## Retirement actions

Archive the repository and disable its GitHub Actions, including recurring backup and operational-check workflows. Preserve the Vercel project as `kinetexa-fitness-archive`, move the apex and www domains to the publication's existing project, and pause the fitness project after the handover. Keep its staging hostname on the paused archive rather than reusing it for public editorial content.

Keep private fitness storage, identity configuration, deployment credentials and billing resources separate from the publication. Do not delete athlete data, close provider accounts, or copy credentials into the publication. Preserving resources is not a statement that every external service has been cancelled or stopped billing. Record actual external state in the publication's migration record after verification.

The historical app had public registration and payments closed. Do not reopen them during retirement. Do not send new provider correspondence or approve pending activity-provider access requests for this retired project.

## Restoration

Unarchive this repository only on a new owner request. Restore under a different domain and verify private data, callback URLs, mail sender, billing settings, webhooks and access controls before making it reachable. The current kinetexa.com domain belongs to the informational publication. Old credentials and deployment metadata are not safe defaults for a new project.
