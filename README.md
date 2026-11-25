# NIPA
Public release repository for NIPA (NeuroImaging Processing &amp; Analytics) application wheels and release notes.

## Current release

[NIPA 3.0.16](https://github.com/WizardYan/NIPA/releases/tag/nipa3-v3.0.16) fixes HTTP 500 when submitting a persisted BIDS workflow review. It retains the plugin SDK isolation, indexed Data loading and lifecycle improvements from 3.0.15. Download the wheel, release manifest and SHA-256 checksums from that release. The fix passed 312 regression tests; real Clinwulf Slurm submission remains to be verified after upgrading there.

Install the wheel into your existing NIPA 3 Python environment, back up your storage directory, and restart with the same storage root and port. NIPA 4 is managed separately.

The [official plugin repository](https://github.com/WizardYan/nipa-plugins) distributes plugin source, documentation and installable packages. [Official plugins v2.3.5](https://github.com/WizardYan/nipa-plugins/releases/tag/v2.3.5) require NIPA 3.0.15 or newer; compatible older packages remain in the catalog.
